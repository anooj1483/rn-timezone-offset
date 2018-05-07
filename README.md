# rn-timezone-offset

[![npm version](https://badge.fury.io/js/rn-timezone-offset.svg)](https://badge.fury.io/js/rn-timezone-offset)


![Easy time manager (based on UTC offset) for different timezones in React Native app.](https://raw.githubusercontent.com/anooj1483/rn-timezone-offset/master/rn_tz_offset.png?raw=true)


Easy time manager (based on UTC offset) for different timezones in React Native app.

This stand-alone library will setup the date based on timezone offset.
Mostly this will be helpful in setting date in DatePickers in React-Native.

This library takes help from great date and timezone management libraries, "Moment" and "Moment-Timezone".

# Usage

> **npm i rn-timezone-offset**

 ```javascript
 var tZoner = require('rn-timezone-offset');
 console.log(tZoner.toLocalTZ("1971-07-05"));
```
The library was created as a fix for timezone issue where RDS was saving the date in
UTC format and client DatePickers (iOS and Android) were setting the date
one day prior to the normal date in certain timezones.