<h1 align="center"><img src="https://ubikloadpack.com/img/ulp.png" alt="UbikLoadPack logo" /></h1>
<h4 align="center">Demo of UbikLoadPack Video Streaming plugin for JMeter using Taurus</h4>
<br>

## What is it?

This is a demo project for running Video Streaming load testing of servers delivering :
- Apple HLS
- MPEG-DASH
- MS Smooth
- Adobe HDS

It uses [Taurus](https://gettaurus.org) and [UbikLoadPack](https://ubikloadpack.com) Video Streaming plugin.

To run the code:

- Install [Taurus](https://gettaurus.org/install/Installation/)
- Install a [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- Request a [trial](https://ubikloadpack.com/tryout.php) version of UbikLoadPack Video Streaming Plugin, you'll receive a mail with an attached trial license and a link to download the bundle. 
- Clone this repository: `git clone https://github.com/ubikloadpack/videostreaming_taurus_demo.git`
- Put the license file `ubik-streaming-plugin.license` sent by Ubik-Ingenierie in this folder
- Put the plugin jar `ubik-jmeter-videostreaming-plugin-X.X.X.jar` (contained in the bundle in lib/ext folder) in this folder
- Run  `bzt ubikloadpack-vs.yml`
- Enjoy the [JMeter HTML report](https://jmeter.apache.org/usermanual/generating-dashboard.html) with custom metrics generated in the output folder
- [Report example](https://a.blazemeter.com/app/?public-token=QxDol44Xh7eqSm7LPXf38M7Gj2qZ96VFcOHcnlPVOJ409V6V5U#reports/r-ext-5b9131e708f56/summary) for a run with 250 VUs