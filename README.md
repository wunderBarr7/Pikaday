Pikaday - With Time Picker
===========
This is a crude merge of [@owenmead's](https://github.com/owenmead) work on adding a Timepicker to [Pikaday/Pikaday](https://github.com/Pikaday/Pikaday).

### Key Config Changes

```javascript
showTime: true
showMinutes: true
showSeconds: false
use24hour: false
incrementHourBy: 1
incrementMinuteBy: 1
incrementSecondBy: 1
autoClose: true
timeLabel: null // optional string added to left of time select
```

### Time support added to [Pikaday/Pikaday][david Pika]

This fork allows the user to specify the time along with their date. Done so by adding a couple select inputs to manipulate the date Pikaday is generating.
* Used to set time aspects of date.
* Will not change the currently selected date.
* If no date is selected, will select today. Any of the arguments may be null, and will not affect the date.


## Authors

* Owen Mead-Robins [owenmead](https://github.com/owenmead)
* Modified by: Patrick Barr [@wunderBarr7](https://github.com/wunderBarr7)

[david Pika]:   https://github.com/Pikaday/Pikaday                              "Pikaday"
