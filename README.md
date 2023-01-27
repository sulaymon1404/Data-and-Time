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





# Date Get Methods
[](/images/getmethods.PNG)



# now()

# The Date.now() static method returns the number of milliseconds elapsed since the epoch, which is defined as the midnight at the beginning of January 1, 1970, UTC.

[](/images/now.PNG)





## getFullYear()

# The getFullYear() method returns the year of a date as a four digit number:
[](/images/fullyear.PNG)
# getMonth()
# The getMonth() method returns the month of a date as a number (0-11).
[](/images/month.PNG)

# getDate()
# The getDate() method returns the day of a date as a number (1-31):
[](/images/date.PNG)
# getDay()
# The getDay() method returns the day of the week for the specified date according to local time, where 0 represents Sunday. 
[](/images/day.PNG)

# getHours()
# The getHours() method returns the hours of a date as a number (0-23):

[](/images/hours.PNG)

# getMinutes()
# The getMinutes() method returns the minutes of a date as a number (0-59):

[](/images/minute.PNG)

# Set Date Methods
[](/images/set.PNG)

# setFullYear()
# The setFullYear() method sets the year of a date object.
# The setFullYear() method can optionally set month and day:
[](/images/setfullyear.PNG)


# setMonth()
# The setMonth() method sets the month of a date object (0-11):

[](/images/setmonth.PNG)

# setDate()
# The setDate() method sets the day of a date object (1-31):
[](/images/setdate.PNG)