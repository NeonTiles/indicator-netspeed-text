# Indicator Netspeed Text

![indicator](https://github.com/rojaro/unity-netspeed-text/raw/master/images/screenshot.png)

A basic text based Ubuntu [indicator](http://unity.ubuntu.com/projects/appindicators/) to display the current upload and download speeds, the local host gateway interface as well as public gateway IPv4 address.

The public gateway IPv4 address is looked up via "A" record DNS query for the "myip.opendns.com" host address at the public OpenDNS servers (resolver1.opendns.com, resolver2.opendns.com).

If the [Net Activity Viewer](http://netactview.sourceforge.net/) (`netactview`) is installed, it can be opened from the indicator menu.

## Requirements

This script requires the python bindings for libappindicator as well as the DnsPython library which can be installed on Ubuntu systems using the following command:

```
sudo apt-get install python-appindicator python-dnspython
```

## Installation

  1. Checkout source code.
  2. Auto-run `indicator-netspeed-text` on system start-up.


