# PhoneGap Build Java API and Maven Plugin

This project aims to provide a stand-alone Java API for communicating with the PhoneGap Build REST API and a Maven Plugin which makes use of the API to turn WAR projects into binaries for mobile platforms.

[Website](http://chrisprice.github.com/phonegap-build/)

[Blog](http://www.scottlogic.co.uk/2012/06/using-phonegap-build-with-maven/)

[![Build Status](https://buildhive.cloudbees.com/job/chrisprice/job/phonegap-build/badge/icon)](https://buildhive.cloudbees.com/job/chrisprice/job/phonegap-build/)

# Cordova Build Maven Plugin

Running:

1.  Go to the Cordova for Android GitHub page and download the zipped
    version of the framework (the rest of this guide assumes version 2.7.0).
    
    Open the command line, and install that zip to your local Maven repository
    like so:
      mvn install:install-file -Dfile=cordova-android-2.7.0.zip
        -DgroupId=org.apache.cordova -DartifactId=cordova-android
        -Dversion=2.7.0 -Dpackaging=zip
        

