apt-get install supervisor -y

yum install -y epel-release
yum install -y supervisor
systemctl start supervisord
systemctl enable supervisord


/datadisk

nohup python3 client-linux.py USER=s06 >/dev/null 2>&1 &




systemctl stop supervisor
systemctl diable supervisor
mv /lib/systemd/system/supervisor.service /lib/systemd/system/supervisord.service
systemctl start supervisord
systemctl enable supervisord