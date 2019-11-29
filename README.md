# Webmin-configuration
#comando para incluir o webmin na lista de ssh

#rodar o comando no terminal linux
iptables -I INPUT 1 -p tcp --dport 10000 -j ACCEPT
