poxy-box
========

Vagrant Box based on Scotch Box (scotch.io)


SSH Database commands
========

Import Database
mysql -u root -proot scotchbox < ../../var/www/scotchbox_db.sql

Backup Database
mysqldump -u root -proot scotchbox > ../../var/www/scotchbox_db.sql
