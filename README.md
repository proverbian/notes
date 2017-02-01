# Notes

### Setup WordPress Using WP-CLI ###

- wp core download
- wp core config --dbname=wp --dbuser=root
- wp core install  --url=http://local.dev/wp --title=test --admin_user=shiloh --admin_password=test123 --admin_email=me@shiloh.me


### Remove Files Except ###

    find . ! -name '*.gz' -type d -exec rm -rf {} +

### Other Useful Note ###
