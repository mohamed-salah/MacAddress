# MacAddress plugin for Phonegap 3 (Android, iOS) #

This Plugin is inspired from MacAddress plugin

[Android plugin here](https://github.com/phonegap/phonegap-plugins/tree/master/Android/MacAddress)

[iOS plugin here](https://github.com/jcesarmobile/my-phonegap-plugins/tree/master/iOS/MacAddressPlugin)


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


## MIT Licence

Copyright 2013 Monday Consulting GmbH

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
