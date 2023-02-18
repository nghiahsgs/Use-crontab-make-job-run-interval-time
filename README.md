# Use-crontab-make-job-run-interval-time
Use crontab make job run interval time


1/ Open your terminal and enter the following command to open the crontab file:
```
crontab -e
````

2/ Add the following line at the end of the file to run the backup.sh script at 2 AM every day:
```
0 2 * * * /bin/bash /path/to/backup.sh
```
Replace /path/to/backup.sh with the actual path to your backup.sh script.

```
0 2 * * * is cron tab expression
```

3 / You can make cron tab expression online using 
```
https://crontab.cronhub.io/
```
