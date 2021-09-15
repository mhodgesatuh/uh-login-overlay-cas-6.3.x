Update the CAS version in gradle.properties and rebuild/redeploy.

The text message for non-prod environments is located in src/main/resources/static/css/cas/css, entry **.uh-not-prod-warning:before**.
There is a line for prod and one for non-prod, one of which is to be commented out, depending on the environment.

![UH Login image](https://raw.githubusercontent.com/mhodgesatuh/uh-login-overlay-cas-6.3.x/master/uh_login_ui.png)
