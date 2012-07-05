micro-cdn
=========

This is the README file.

In order to view images delivered from the cdn in projects created with the
php mysql micro framework, it is necessary to setup the micro cdn.

The micro cdn is really micro in the sense that it is a simple redirect to
the image server.

So in this case the cdn is serving only images, but I am going to change it
to server other assets as js and css.

The setup is done by creatiing a virtual host under apache httpd configuration.

The file [httpd-cdn-sample.conf](micro-cdn/blob/master/httpd-cdn-sample.conf) contains a sample used by the shop app example.
