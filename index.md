<html>
  <body>
	  <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DgK000002ilAC',
				'Web_Chat',
				'https://orgfarm-760e4bb960-dev-ed.develop.my.site.com/ESWWebChat1745845251851',
				{
					scrt2URL: 'https://orgfarm-760e4bb960-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://orgfarm-760e4bb960-dev-ed.develop.my.site.com/ESWWebChat1745845251851/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
