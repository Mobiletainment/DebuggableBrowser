# DebuggableBrowser
This browser allows you to inspect and debug your web page with Chrome DevTools while it's running on the Android native browser. This should help web developers and web designers identify and solve problems that are specific to the Android stock browser.

### Why oh why would I need this?
Does your web site look broken on the Android stock browser?<br />
Do you have Android specific defects you want to understand and solve?<br />

### What is it exactly?
A debug-enabled WebView, allowing you to use Chrome DevTools to inspect and debug your web app while its running on your device.

![Screenshot](http://www.pertiller.net/projects/Remote-Debugging-Android-Native-Browser/Debuggable-Browser.png)

### Explanation
It sometimes happens that a web app doesn't work on mobile browsers, even though it's working fine on desktop browsers. Even worse, sometimes defects occur only on (certain) mobile devices, so you cannot simulate and reproduce it on a desktop browser. This is where [remote debugging with Chrome's DevTools](https://developer.chrome.com/devtools/docs/remote-debugging) proves to be useful. While Chrome for Android perfectly supports this already, the Android stock browser doesn't. This is unfortunate, since a lot of Android bugs seem to occur only on the stock browser and not on Chrome anyways.<br/>So this app lets you run web sites within the native browser (WebView), while giving you the possibility to inspect and debug the page with the Chrome DevTools.

### How to enable remote debugging?
1. Get a device running on Android 4.4 or higher
2. Enable Developer Mode on your device and connect it to your PC/Mac
3. Navigate to your web site by entering the URL in the app
4. On your PC/Mac, open Chrome and type "chrome://inspect" into the address bar
5. In Chrome, check "Discover USB Devices" and it will list the web page you've opened on your device
6. Hit inspect and enjoy remote debugging the app with the Chrome Developer Tools
