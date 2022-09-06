# Jenkins

CRON job that runs every minute


Minute (0-59) – tells at what minute of the hour the Job should build.
Hour (0-23 With 0 is the midnight) - tells at what hour the job should build in the 24-hour clock.
Day of the month (1-31) - tells on which day of the month your job should build, e.g., 23rd of each month.
Month (1-12) - tells the month when your job should build. You can number or name the month as well. i.e., April, May, etc.
Day of the week (0-7 With 0 or 7 both being Sunday) - tells the day of the week when you want to build your job. It can also be a number or name like Mon etc.

cron('* * * * *')

