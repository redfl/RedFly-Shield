RedFly-Shield Software Package
==============================
  Visit github.com/watterott/RedFly-Shield for updates.


Installation
------------
  Copy the content of /examples/ and /libraries/ to your 
  Arduino folder: /arduino/examples/ and /arduino/libraries/
  If there are existing folders from a previous installation,
  delete them before copying.


Documentation
-------------
  See docu.htm


Third party software
--------------------
  digitalWriteFast
    http://code.google.com/p/digitalwritefast/

  ArdOSC
    http://recotana.com/
    http://github.com/recotana/ArdOSC/


License
-------
  See license.txt


History
-------
         2012  v0.12  socketClose() now clears the input buffer.
  
  Feb 26 2012  v0.11  Added ArdOSC Lib.

  Jan 07 2012  v0.10  Compatible with Arduino 1.0.
                      Added UDP Client+Server API.
                      Added basic NBNS support.
                      Added gettime().
                      Added getlocalip().
                      Added getbssid().
                      Added gettype().
                      Bugfix in enable() and disable().
                      Updated examples and docu.

  Dec 02 2011  v0.08  Added AutoIP support.
                      Added Multicast support.
                      Updated examples and docu.

  Sep 10 2011  v0.07  Updated examples.
                      More robust Client and Server class.
  
  Sep 02 2011  v0.06  Minor changes in Socket API.
                      Bugfix in getrssi().
                      Bugfix in socketRead().
                      Updated examples.

  Aug 17 2011  v0.05  Added DNS client, FW >= 4.3.0 required.

  Aug 08 2011  v0.04  Updated examples.
                      Added Client+Server API.

  Jul 02 2011  v0.03  Updated docu.

  May 13 2011  v0.02  Updated WebServer example.

  Apr 28 2011  v0.01  First release.