Ported an old code from 

http://jabtunes.com/labs/qrcode.js  
http://www.d-project.com/

This is sometimes useful.



## usage

```javascript
var canvasEl = QR.generateQRCodeCanvas({
	text:   'hello world',
	scale:  7,
	margin: 10
});
```

This returns a canvas element you can append to the DOM.  
Text can't be longer than 119 charaters long.

Check the examples.
