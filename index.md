<html>
  <body>
    <script type='text/javascript'>
    	function initEmbeddedMessaging() {
    		try {
    			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
          window.addEventListener("onEmbeddedMessagingReady", () => {            
          	console.log( "Inside Prechat API!!" );
          	embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields( { "First_Name" : "Bhuvan" } );
          });
    			embeddedservice_bootstrap.init(
    				'00DDi000000F9yW',
    				'A3_MyAccounts',
    				'https://carefirst-hc360--devcc4.sandbox.my.site.com/ESWA3MyAccounts1746010772755',
    				{
    					scrt2URL: 'https://carefirst-hc360--devcc4.sandbox.my.salesforce-scrt.com'
    				}
    			);
    		} catch (err) {
    			console.error('Error loading Embedded Messaging: ', err);
    		}
    	};
  </script>
  <script type='text/javascript' src='https://carefirst-hc360--devcc4.sandbox.my.site.com/ESWA3MyAccounts1746010772755/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
  </body>
</html>
