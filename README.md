# MacAddress plugin for Cordova / PhoneGap

This Plugin is inspired from MacAddress plugins
[here](https://github.com/purplecabbage/phonegap-plugins/tree/master/Android/MacAddress)
and [here](https://github.com/jcesarmobile/my-phonegap-plugins/tree/master/iOS/MacAddressPlugin),Using this plugins 
device MacAddress could be retrieved for Android/iOS devices.

It has been successfully tested on Cordova version 3.1.0.

## Adding the Plugin to your project ##

**For phonegap 3 (CLI)**
<pre>
phonegap local plugin add https://github.com/mohamed-salah/MacAddress.git
</pre>

**Example Usage:**

```js
window.MacAddress.getMacAddress(
function(macAddress) {alert(macAddress);},function(fail) {alert(fail);}
);
```

## Installation 

for Cordova >= 3.0.0

phonegap local plugin add https://github.com/mohamed-salah/MacAddress.git

cordova plugin add https://github.com/mohamed-salah/MacAddress.git

for Cordova >= 5.0.0

cordova plugin add com-badrit-macaddress

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
