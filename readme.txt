
http://stackoverflow.com/questions/410616/increasing-the-maximum-number-of-tcp-ip-connections-in-linux


ulimit -n 204800    //~/.bashrc

sysctl -p

ifconfig eth0 txqueuelen 5000
