Automatic Script Installer by elang overdosis

==========
# INSTALL all menu
```
cd
wget https://raw.githubusercontent.com/denysiswanto/autoscript2/master/almenu.sh && chmod +x almenu.sh && ./almenu.sh
```
# debian7
```

cd
wget https://raw.githubusercontent.com/denysiswanto/autoscript2/master/debian7.sh && chmod +x debian7.sh && ./debian7.sh

```

# Debian7x64
```
cd
wget https://raw.githubusercontent.com/denysiswanto/autoscript2/master/debian7x64.sh && chmod +x debian7x64.sh && ./debian7x64.sh
```
# Virtual Ram
```
wget https://raw.githubusercontent.com/denysiswanto/autoscript2/master/ram/swapram.sh && chmod +x swapram.sh && ./swapram.sh
```
# Menu
```
cd
wget https://raw.githubusercontent.com/denysiswanto/autoscript2/master/menu/menu
mv ./menu /usr/local/bin/menu
chmod +x /usr/local/bin/menu
```
# Shc
```
sudo add-apt-repository ppa:neurobin/ppa
sudo apt-get update
sudo apt-get install shc
```
# Unshc.sh
```
wget "https://raw.githubusercontent.com/denysiswanto/autoscript2/master/latest/unshc.sh"
mv ./unshc.sh /root/latest/
chmod +x /root/latest/unshc.sh
```
# Bannerssh
```
wget https://raw.githubusercontent.com/denysiswanto/autoscript2/master/menu/bannersshlink.sh && chmod +x bannersshlink.sh && ./bannersshlink.sh
```
# webmin 1.820
```
wget "http://prdownloads.sourceforge.net/webadmin/webmin_1.820_all.deb"
dpkg --install webmin_1.820_all.deb
apt-get -y -f install
rm /root/webmin_1.820_all.deb
sed -i 's/ssl=1/ssl=0/g' /etc/webmin/miniserv.conf
service webmin restart
```

## By deeniedoank-elangoverdosis-denysiswanto
