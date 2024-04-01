<h1 align="left">Backup</h1>

<p align="center">
 <a href="./README.md">
 English
 </a>
 /
 <a href="./README-fa.md">
 فارسی
 </a>
</p>

###

<p align="left">With this script, you can backup important information such as database from the x-ui, marzban, and hiddify panels and send it to Discord with the help of the Telegram bot so that it is always available!</p>

###

<br clear="both">

<p align="left">‏<br>‏</p>

###

<h1 align="left">How does it work</h1>

###

<h3 align="left">Step 1: run the script</h3>

###

<p align="left">First, you run this command on your server<br><br></p> 

```bash
bash <(curl -Ls https://github.com/mikeesierrah/backup/raw/main/backup.sh)
``` 

###

<h3 align="left">Step 2 : Webhook setting</h3>

###

<p align="left">Then it asks us for Webhook - if you dont know how to get Discord webhook just say Google it</p>


###

<h3 align="left">Step 3 : Caption setting</h3>

###

<p align="left">The next step asks you for a caption, which you can leave blank</p>

###

<h3 align="left">Step 4 : Cronjob setting</h3>

###

<p align="left">The next step asks you to run a cron job to determine when the robot will back up and send<br>whose format is like this:<br>0 1<br>The first value, which is 0, is the minute, and the second value, which is 1, is the hour<br>The minimum number for minutes is 0 and the maximum is 60<br>The minimum number for the hour is 0 and the maximum is 24<br>Enter 0 for both to set backup once every minute<br>In the example above, it is backed up once every hour<br>Note that there is a space between both values</p>

###

<h3 align="left">Step 5 : Panel selection</h3>

###

<p align="left">The next step will ask you which panel you want to backup<br>You have to choose one from marzbn, x-ui, and hiddify <br>The value of m means marzban, the value of x means x-ui, and the value of h means hiddify <br>Enter an option between x/m/h as per your requirement</p>

###

<h3 align="left">Step 6 : question of removing previous crown jobs</h3>

###

<p align="left">Then it will ask you if you want to delete the previously defined cron jobs or not?<br>Enter y if you want it to be cleared otherwise enter n</p>

###

<h1 align="left">Possible problems</h1>

###

<p align="left">If you have entered everything correctly, the backup file should be sent to you once, otherwise there is a problem in this process and you can raise your problem from the issues</p>

###

<h1 align="left">Help the original Developer</h1>

###

<p align="left">this is just a fork i made that sends the backup to Discord instead of telegram - if you like it give me a star and Donate to the original developer </p>

###

<h1 align="left">Donation</h1>

###

<p align="left">https://nowpayments.io/donation/ACLover</p>

###


## Stargazers over time

[![Stargazers over time](https://starchart.cc/mikeesierrah/backup.svg)](https://starchart.cc/mikeesierrah/backup)

