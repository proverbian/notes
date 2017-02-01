# Notes

### Setup WordPress Using WP-CLI ###

- wp core download
- wp core config --dbname=wp --dbuser=root
- wp core install  --url=http://local.dev/wp --title=test --admin_user=shiloh --admin_password=test123 --admin_email=me@shiloh.me


### Remove Files Except ###

    find . ! -name '*.gz' -type d -exec rm -rf {} +
    
 
### Keep Files

    # daily - keep for 14 days
    find /tmp/backup.daily/ -maxdepth 1 -mtime +14 -type d -exec rm -rv {} \;

    # weekly - keep for 60 days
    find /tmp/backup.weekly/ -maxdepth 1 -mtime +60 -type d -exec rm -rv {} \;

    # monthly - keep for 300 days
    find /tmp/backup.monthly/ -maxdepth 1 -mtime +300 -type d -exec rm -rv {} \;


### Other Useful Note ###
