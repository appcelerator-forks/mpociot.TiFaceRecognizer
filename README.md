TiFaceRecognizer
===========================================

** IOS ONLY **

This module allows CoreImage face detection.


Features
========
* Detect faces on a given image
* Returns coordinates for left eye, right eye, mouth


Usage
====================


	var TiFaceRecognizer = require('de.marcelpociot.facerecognizer');
	
	var result = TiFaceRecognizer.detectFaces({
		image: imageView.image
	});

Right now , take a look at the example app.js for further instructions :)

![image](http://www.marcelpociot.de/github/tifacedetection.png)

Sample image taken from http://beautysaloon.wordpress.com

ABOUT THE AUTHOR
========================
I'm a web enthusiast located in germany.

Follow me on twitter: @marcelpociot

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/mpociot/tifacerecognizer/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

