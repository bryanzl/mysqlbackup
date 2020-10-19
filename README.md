# mysqlBackUp
mysql备份脚本

git clone https://github.com/bryanzl/mysqlbackup.git

chmod +x /XXXXXX/mysqlbackup.sh

crontab -e

00 03 * * * /XXXXXX/mysqlbackup.sh

恢复

mysql -u username -p databse < backup.sql
