Steps to use the Cordova plugin for the Salesforce Mobile SDK
------------------------

<pre>
npm install cordova -g

cordova create TestApp
cd TestApp
cordova plugin add https://github.com/forcedotcom/SalesforceMobileSDK-CordovaPlugin
cordova platform add android
cordova platform add ios
cordova prepare
</pre>

Note, the above order is important. If you add the plugin after adding the Android platform you must then remove and re-add the platform in order for the plugin to configure the AndroidManifest.xml file. 

For more information, check out [Salesforce Mobile SDK Development Guide](https://github.com/forcedotcom/SalesforceMobileSDK-Shared/blob/master/doc/mobile_sdk.pdf?raw=true)
