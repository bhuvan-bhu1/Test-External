<html>
  <body>
    <script type='text/javascript'>
    	function initEmbeddedMessaging() {
    		try {
    			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
    
    			embeddedservice_bootstrap.init(
    				'00DDi000000F9yW',
    				'Test',
    				'https://carefirst-hc360--devcc4.sandbox.my.site.com/ESWTest1744289778970',
    				{
    					scrt2URL: 'https://carefirst-hc360--devcc4.sandbox.my.salesforce-scrt.com'
    				}
    			);
    		} catch (err) {
    			console.error('Error loading Embedded Messaging: ', err);
    		}
    	};
    </script>
    <script type='text/javascript' src='https://carefirst-hc360--devcc4.sandbox.my.site.com/ESWTest1744289778970/assets/js/bootstrap.min.js'   onload='initEmbeddedMessaging()'></script>
    
  </body>
</html>
