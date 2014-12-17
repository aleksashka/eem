eem-updown-desc
===============

Cisco EEM applet for generating syslog messages with interfaces' descriptions

To use just go in configuration mode (configure terminal) and paste the code

Example for IOS **12.4(24)T2**:
```
*Dec 17 22:14:00.745: %LINK-3-UPDOWN: Interface Loopback1, changed state to up
*Dec 17 22:14:01.745: %LINEPROTO-5-UPDOWN: Line protocol on Interface Loopback1, changed state to up
*Dec 17 22:14:01.941: %HA_EM-5-LOG: EEM-UPDOWN-DESC: Loopback1 (TEST) -> up
```
Example for IOS **15.0(2)SE5**:
```
.Dec 17 22:12:19.660: %LINK-5-CHANGED: Interface Loopback1, changed state to administratively down
.Dec 17 22:12:20.666: %LINEPROTO-5-UPDOWN: Line protocol on Interface Loopback1, changed state to down
.Dec 17 22:12:20.859: %EEMUPDOWN-5-LOG: EEM-UPDOWN-DESC: Loopback1 (no description) -> down
```
