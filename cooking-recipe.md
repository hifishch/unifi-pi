# Cooking Recipe
The following script snippeds were used to build the current Unifi Pi builds.
```
apt-get update -y
apt-get upgrade -y
curl -o setup-repos.sh https://raw.githubusercontent.com/webmin/webmin/master/setup-repos.sh
sh setup-repos.sh
apt-get install webmin --install-recommends -y
apt-get install ca-certificates curl -y
curl -sO https://get.glennr.nl/unifi/install/install_latest/unifi-latest.sh && bash unifi-latest.sh
```
