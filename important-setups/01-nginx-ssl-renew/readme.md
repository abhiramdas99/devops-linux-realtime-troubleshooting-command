# Linux View Users Cronjob command
- Use the following syntax to view cronjob for a user:
```git
sudo crontab -u root -l
```
- Use the following syntax to view all job r:
```git
sudo crontab -u root -l
```
- auto renew the ssl by cronjob at night
```git
#########################################################
# Job : Auto renew of ssl before license expired
# Create By : Abhiram , abhiramdas99@gmail.com
# Create Dt : 03/10/2023
#########################################################
 0 12 * * * /usr/bin/certbot renew --quiet

```

# information source 
https://www.cyberciti.biz/faq/linux-show-what-cron-jobs-are-setup/

