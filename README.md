# py3status-football
A module py3status for football fans

# Pre-requis

- You need to register [here](https://www.football-data.org/client/register).
- Get your token

# Config your py3stats
- In your modulme path (e.g ~/.config/py3status/modules), add the module file
- Update your i3status.conf

For example, if you want to show the match of the day in the ligue 1 
```
football {
       	token = "XXXXXXXXXXXXXXXXXX"
        competition = "ligue 1"
        dateOfmatch = "today"
}
```
