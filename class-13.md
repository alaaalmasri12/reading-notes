# Local Storage
what is Local Storage??
Simply put it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies
theres multiple browsers support html5 storage support
IE  	FIREFOX	 SAFARI	 CHROME	 OPERA	 IPHONE 	ANDROID
8.0+	 3.5+	 4.0+	 4.0+	 10.5+ 	 2.0+	     2.0+
From your JavaScript code  you’ll access HTML5 Storage through the localStorage object on the global window object Before you can use it you should detect whether the browser supports it.
how to check of html storage using this code
`function supports_html5_storage() {`
  `try {`
   ` return 'localStorage' in window && window['localStorage'] !== null;`
  `} catch (e) {`
  `  return false;`
`  }`
`}`
Instead of writing this function yourself, you can use Modernizr to detect support for HTML5 Storage.
`if (Modernizr.localstorage) {`
  `// window.localStorage is available!`
`} else {`
  `// no native support for HTML5 storage`
 ` // maybe try dojox.storage or a third-party solution`
`}`
Modernizr is an open source, MIT-licensed JavaScript library that detects support for many HTML5 & CSS3 features

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string
