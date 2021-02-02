# Ultities

## Stand Up Discussions

```
on:
  schedule:
    - cron:  '0 4 * * 1-5' # Runs M-F at 4:00am UTC
```

Guide for cron job:
```
┌───────────── minute (0 - 59)
│ ┌───────────── hour (0 - 23)
│ │ ┌───────────── day of the month (1 - 31)
│ │ │ ┌───────────── month (1 - 12)
│ │ │ │ ┌───────────── day of the week (0 - 6)
│ │ │ │ │                                   
│ │ │ │ │
│ │ │ │ │
* * * * *
```

`team_slugs:` "ADD Pod slug from GitHub Teams separated by `,`"