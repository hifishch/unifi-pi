# Cooking Recipe
The following script snippets were used to build the current Unifi Pi builds.
```
apt-get update -y
apt-get upgrade -y
curl -o setup-repos.sh https://raw.githubusercontent.com/webmin/webmin/master/setup-repos.sh
sh setup-repos.sh
apt-get install webmin --install-recommends -y
apt-get install ca-certificates curl -y
curl -sO https://get.glennr.nl/unifi/install/install_latest/unifi-latest.sh && bash unifi-latest.sh
```
This JSON snippet is used to add the menu-options to Webmin
```
{
 "extra" : [
   {
   "title" : "Local UniFi Network Server",
   "icon" : "fa fa-cog fa-fw",
   "link" : "/",
   "target" : "_blank",
   "port" : "8443"
  },
  {
   "level" : "0,1,2,3,4",
   "link" : "https://unifi.ui.com",
   "title" : "UniFi Site Manager",
   "target" : "_blank",
   "icon" : "fa fa-cog fa-fw"
  }
 ]
}
```
