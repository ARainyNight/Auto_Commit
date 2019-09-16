# Auto_Commit

crontab -e

0 5 * * * /home/ubuntu/auto_commit.sh > /dev/null 2>&1 &

service cron start
