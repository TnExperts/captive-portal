# Captive portal example

## Overview

This is a captive portal example. A captive portal is a DNS server that
points to itself to all DNS queries. This is used to route all Web requests
to a specified web page.

Build and flash this example. It'll start a WiFi access point Mongoose_XXXXXXX.
Join that access point (the password is `Mongoose`). Open your browser
and go to "http://example.com".
You'll end up on the simple web page that this app runs:

![screenshot](screenshot.png)

## How to install this app

- Install and start [mos tool](https://mongoose-os.com/software.html)
- Switch to the Project page, find and import this app, build and flash it:

<p align="center">
  <img src="https://mongoose-os.com/images/app1.gif" width="75%">
</p>
