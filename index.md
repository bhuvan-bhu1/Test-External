<html>
  <body>
    <script type='text/javascript'>
        function initEmbeddedMessaging() {
                try {
                    embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
    
                    embeddedservice_bootstrap.init(
                        '00DDi000000F9yW',
                        'A3_Embedded_Web_Deployments',
                        'https://carefirst-hc360--devcc4.sandbox.my.site.com/ESWA3EmbeddedWebDeploy1743434116252',
                        {
                            scrt2URL: 'https://carefirst-hc360--devcc4.sandbox.my.salesforce-scrt.com'
                        }
                    );
                } catch (err) {
                    console.error('Error loading Embedded Messaging: ', err);
                }
            };
    </script>
    <script type='text/javascript' src='https://carefirst-hc360--devcc4.sandbox.my.site.com/ESWA3EmbeddedWebDeploy1743434116252/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script
    
  </body>
</html>
