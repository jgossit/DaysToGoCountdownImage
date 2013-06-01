DaysToGoCountdownImage
======================

DaysToGo Countdown Image is a java servlet that simply takes a date and creates a dynamic countdown image/png showing 'x days to go' until that date.


Usage
=====

The war directory contains a sample WEB-INF/web.xml for deploying the servlet to your app server.

Calling the DaysToGo servlet requires a date parameter be included in the query string

e.g. for a countdown to July 1, 2013<br>
http://hostname/daystogo?date=2013-07-01


Demo
====

Available at jgossit.appspot.com/daystogo?date=yyyy-mm-dd


Output
======

<p align="center" >
  <img src="https://raw.github.com/jgossit/DaysToGoCountdownImage/master/example/daystogo.png"/>
</p>


Requirements
============

Your App server of choice to deploy the servlet<br>
Apache Commons Codec


License
=======
See the LICENSE file
