# Data-and-Time

## Data and Time
## In JavaScript, date and time are represented by the Date object. The Date objectprovides the date and time information and also provides various methods.A JavaScript date defines the EcmaScript epoch that represents millisecondssince 1 January 1970 UTC. This date and time is the same as the UNIX epoch(predominant base value for computer-recorded date and time values).

## There are four ways to create a date object.
- new Date()
- new Date(milliseconds)
- new Date(Date string)
- new Date(year, month, day, hours, minutes, seconds, 
milliseconds)




# new Date()

# You can create a date object using the new Date() constructor
[](/images/newdate.PNG)


# new Date(milliseconds)

# JavaScript stores dates as number of milliseconds since January 01, 1970.Zero time is January 01, 1970 00:00:00 UTC.One day (24 hours) is 86 400 000 milliseconds.Now the time is: 1674814226841 milliseconds past January 01, 1970
[](/images/miliseconds.PNG)

# new Date (date string)
# new Date(date string) creates a date object from a date string:
[](/images/string.PNG)

# new Date (year, month, day, hours, minutes, seconds, milliseconds)

- new Date(year, month, ...) creates a date object with a specified date and time.
7 numbers specify year, month, day, hour, minute, second, and millisecond (in that order):

[](/images/number.PNG)


# Note
- JavaScript counts months from 0 to 11:
- January = 0.
- December = 11.