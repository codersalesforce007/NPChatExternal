<html>
  <body>
    <script type='text/javascript'>
    	function initEmbeddedMessaging() {
    		try {
    			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
    
    			embeddedservice_bootstrap.init(
    				'00DcW000000gSRK',
    				'Admissions_Chat_3_0',
    				'https://newportacademy--npchat.sandbox.my.site.com/ESWAdmissionsChat301728044092179',
    				{
    					scrt2URL: 'https://newportacademy--npchat.sandbox.my.salesforce-scrt.com'
    				}
    			);
       embeddedservice_bootstrap.settings.reloadOnChatEnd = true;
    		} catch (err) {
    			console.error('Error loading Embedded Messaging: ', err);
    		}
    	};
    </script>
    <script type='text/javascript' src='https://newportacademy--npchat.sandbox.my.site.com/ESWAdmissionsChat301728044092179/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
