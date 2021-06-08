# openfortivpn : la version linux de fortivpn

### Installation

sudo apt-get install -y openfortivpn


### Configuration de openfortivpn

cd /etc/openfortivpn/
sudo nano config

host = le host
port = 10443 (par défaut)
username = username
password = le passeword

lancer sudo openfortivpn

editer à nouveau le fichier ****config**** en complétant trusted-cert par le trusted-cert généré 

lancer à nouveau sudo openfortivpn 
