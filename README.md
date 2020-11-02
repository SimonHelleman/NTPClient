Fork Of  NTPClient
-Adds functioanlity for dates
# NTPClient

## Function documentation
`getHours(void)` returns an int containing the hour of the day (00-24).
`getMinutes(void)` returns an int containing the minutes of the current hours (00-59).
`getSeconds(void)` returns an int containing the seconds of the current minute (00-59).

`getDate(void)` returns an int containing the day of the current month - not in original library
`getMonth(void)` returns an int containing the current month (0-12) - not in original library
`getYear(void)` returns an int containing the current year - not in original library

`getEpochTime` returns the unix epoch, which are the seconds elapsed since 00:00:00 UTC on 1 January 1970 (leap seconds are ignored, every day is treated as having 86400 seconds). **Attention**: If you have set a time offset this time offset will be added to your epoch timestamp.

See original repository for more details
