# ArcGIS Secure services test #

A test of calling secure services.

## Getting started ##

1. Create a copy of `sample.proxy.config` and call it `proxy.config`.
2. Provide values for the `agolUser` and `agolPassword` settings in `proxy.config`.
3. Set the project to use IIS Express.
4. Set the _SSL Enabled_ property to _True_. This will populate the _SSL URL_ property.
5. Open the project properties window.
6. Under the _Web_ tab in the _Servers_ section, under the _Use Local IIS Web Server_ radio button, set the _Project Url_ to match the _SSL URL_.

## Development environment ##

This project was created in Visual Studio 2012.
