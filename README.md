# MacAddress plugin for Phonegap 3 (Android) #

This Plugin is inspired from MacAddress plugin

[here](https://github.com/phonegap/phonegap-plugins/tree/master/Android/MacAddress)

## Adding the Plugin to your project ##

for phonegap 3 (CLI)
phonegap local plugin add https://github.com/mohamed-salah/MacAddressPlugin.git

## Using the plugin ##

<pre>
	var successCallback = function(macAddress){console.log(macAddress)};
	var failureCallback = function(){};
	window.MacAddress.getMacAddress(successCallback,failureCallback);
</pre>