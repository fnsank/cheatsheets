### Install
```
Download Nessus https://www.tenable.com/downloads/nessus
sudo dpkg -i Nessus-*.deb"
sudo systemctl start nessusd"
```

### Update plugins
```
sudo systemctl stop nessusd
sudo /opt/nessus/sbin/nessuscli fetch --register <key>
sudo systemctl start nessusd
```

### Listen only  on localhost
```
/opt/nessus/sbin/nessuscli fix --set listen_address=127.0.0.1
```

### Web interface
https://localhost:8834  

