<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
  <link rel="stylesheet" type="text/css" href="https://ruby-customer-1927-dev-ed.scratch.my.salesforce.com/prefcenter/preference-center-1.2.0/css/pref-center-slds.css">
</head>
<body>

<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
			embeddedservice_bootstrap.init(
				'00D3J0000001Jh4',
				'Messaging_service_using_web',
				'https://arc-phss--digitaleng.sandbox.my.site.com/ESWMessagingserviceusin1707397130493',
				{
					scrt2URL: 'https://arc-phss--digitaleng.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://arc-phss--digitaleng.sandbox.my.site.com/ESWMessagingserviceusin1707397130493/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
</html>
