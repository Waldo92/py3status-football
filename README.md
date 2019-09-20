# py3status-football
A module py3status for football fans

# Goal

You like football and you are afraid to miss the match of the day, I propose module that will let you know the matches of the day by displaying it on your i3bar.

# Pre-requis

- You need to register [here](https://www.football-data.org/client/register).
- Get your token

# Config your py3status
- Find your i3 modules file (e.g ~/.config/py3status/modules)
- Add the module file **football.py** in your path
- Go update your **i3status.conf**

For example, if you want to show the match of the day in the ligue 1 
```
order += "football"
football {
       	token = "XXXXXXXXXXXXXXXXXX"
        competition = "ligue 1"
        dateOfmatch = "today"
}
```

Competitions:
- ligue 1
- premier league
- bundesliga
- liga

DateOfmatch:
- today
- tomorrow
- aftertomorrow
