poxy-box (NodeJS) (Testing)
========

Vagrant Box based on Scotch Box (scotch.io)


URL
========
http://192.168.33.10/


SSH Database commands
========

Import Database
mysql -u root -proot scotchbox < ../../var/www/scotchbox_db.sql

Backup Database
mysqldump -u root -proot scotchbox > ../../var/www/scotchbox_db.sql
