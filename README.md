
## Save screen

Stop infinity jails, attention economy. Don't waste life and get some sleep!

Auto turn off screen computer at times with cronjob (bash script?)

Change sleep.sh script to your display (xrandr)

```
crontab -e
```

Add these and change the times, change display to yours.

```
# turn off/on screen automatically
30 00 * * *  export DISPLAY=:1 && xset dpms force off
36 00 * * *  export DISPLAY=:1 && xset dpms force off
00 08 * * *  export DISPLAY=:1 && xset dpms force on
```


<img src="https://github.com/devtox/sleep-computer/blob/main/jail.png?raw=true" alt="stop computer addiction">
