# LINUX SERVER CONFIGURATION
An Ubuntu instance was created using AWS Lightsail and ocnfigured to hot a flask app with all the appropiate security measures. 

## Access
Static IP Address: `34.195.4.45`
SSH port: `22`
URL: `demo.suarez.pw`

## Configuration:
* Updated security packages
* Configured Lightsail firewall
* Changed default ports and activated UFW
* Created new users with sudo access
* Disabled root remote access
* Configured RSA keypair access
* Disabled password login
* Configured new public domain
### Installations made:
* Apache2
* mod_wsgi
* SQLAlchemy
* SQLite
* Flask
* oauth2client
* requests
