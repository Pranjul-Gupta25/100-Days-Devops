 1  clear 
    2  sudo yum install iptables iptables-service -y
    3  sudo yum install iptables iptables-services -y
    4  sudo systemctl enable iptables
    5  sudo systemctl start iptalbes 
    6  sudo systemctl start iptables 
    7  iptable -F
    8  iptable -f
    9  iptables -f
   10  iptables -F
   11  sudo iptables -F
   12  suod iptables -A INPUT -p tcp --destination-port 8082 -s 172.16.238.14 -j ACCEPT
   13  sudo iptables -A INPUT -p tcp --destination-port 8082 -s 172.16.238.14 -j ACCEPT
   14  sudo iptables -A INPUT -p tcp --destination-port 8082 -j DROP
   15  sudo service iptables save 
   16  sudo systemctl restart iptables



   install ip tables in each app server and Allow traffic from LBR to port 8082


   Drop all other incoming traffic to port 8082
