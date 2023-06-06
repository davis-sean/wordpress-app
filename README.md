## Docker Compose for Wordpress-App

This is a docker compose file to build the Wordpress-App docker containers.
It is composed of:
- MySQL Container for Database
- Wordpress Container for Data
- Cloudflare Container for Tunnel

This App Package requires 3 environment variables to be defined in the starup script: start.sh
- SERVICE is the name of the Web Application
- SQLPASSWORD is the SQL password
- TOKEN is the CloudFlare Tunnel Token
