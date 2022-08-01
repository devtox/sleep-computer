
## Save screen

Stop infinity jail, attention economy. Don't waste life!

Auto turn off screen computer at times
cronjob and bash script

Change sleep.sh script to your display (xrandr)

```
# turn off/on screen automatically
30 00 * * *  export DISPLAY=:1 && xset dpms force off
36 00 * * *  export DISPLAY=:1 && xset dpms force off
00 08 * * *  export DISPLAY=:1 && xset dpms force on
```


<img src="https://github.com/devtox/sleep-computer/blob/main/jail.png?raw=true" alt="stop computer addiction">
