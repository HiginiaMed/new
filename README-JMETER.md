# README - JMeter Performance test for TrackGenix App

Hi! This is the readme for performance test in TrackGenix app. We will use Apache JMeter™ application that is designed to load test functional behavior and measure performance.


------------

<br>

## What we test?

This test is to analyze overall performance of the app under different load types.
We will simulate a heavy user load to check if requests fail and what the response time is.

------------

<br>

## Quick Start

### Download:

At least JAVA version 8
```console
<a href="https://www.oracle.com/java/technologies/javase/javase8u211-later-archive-downloads.html" target="_blank">Java SE 8 Archive Downloads (JDK 8u211 and later)</a>
```

JMeter
```console
<a href="https://jmeter.apache.org/download_jmeter.cgi" target="_blank">Download Apache JMeter</a>
```

Firefox
```console
<a href="https://www.mozilla.org/en-US/firefox/new/" target="_blank">Download Firefox Browser from Mozilla</a>
```

### Configure Firefox proxy

a. Menu

b. Settings

c. On the searchbar we writte proxy

d. Click on settings on network settings

e. Select "Manual proxy configuration".

f. HTTP Proxy: local host - Port: 3000 (Remember that the port number must be the same as the one we set in JMeter)


------------

<br>