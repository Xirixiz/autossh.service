# autossh.service
Setup autossh service with systemd.

Assuming you have some basic knowledge of key based auth.
Key based auth has to be in place before autossh can be used.

Files:
- /etc/systemd/system/autossh.service
- /home/xxx/.ssh/config

sudo systemctl daemon-reload
sudo systemctl start autossh.service
sudo systemctl enable autossh.service
