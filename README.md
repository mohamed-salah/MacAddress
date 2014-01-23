# MacAddress plugin for Phonegap 3 (Android, iOS) #

This Plugin is inspired from MacAddress plugin

[Android here](https://github.com/phonegap/phonegap-plugins/tree/master/Android/MacAddress)
[iOS here](https://github.com/jcesarmobile/my-phonegap-plugins/tree/master/iOS/MacAddressPlugin)


## Adding the Plugin to your project ##

for phonegap 3 (CLI)
<pre>
phonegap local plugin add https://github.com/mohamed-salah/MacAddressPlugin.git
</pre>
## Using the plugin ##

<pre>
	var successCallback = function(macAddress){console.log(macAddress)};
	var failureCallback = function(){};
	window.MacAddress.getMacAddress(successCallback,failureCallback);
</pre>
