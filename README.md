# Beagle Bone Black Logic Level Analyser
Just project is just a fun way to play around with AngularJS, graphs, NVD3 and my Beagle Bone Black.
It is a webapplication (well, it's only a few lines, so not much of an application) written in [AngularJS](https://angularjs.org/) and using the [Angular-NVD3 module](http://krispo.github.io/angular-nvd3/) to create a real-time graph of the output of a GPIO pin of my beagle bone black.
It connects to the Beagle Bone Black through socket.io and updates the GPIO-pin state real-time in the graph as soon as the connection is setup. 
