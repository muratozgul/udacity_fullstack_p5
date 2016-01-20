## Linux Server Configuration

###i)
####IP address: 52.33.118.142
####SSH port: 2200

###ii)
####URL: http://52.33.118.142/

###iii)
####Software installed and configuration changes made:
*Created new users
*Changed local time to UTC  
`sudo dpkg-reconfigure tzdata`
*Removed root login
*Added created users to sudoers
*Updated/upgraded packages
*Configured firewall (ufw)
*Removed password ssh, only key based ssh
*Installed apache + mod_wsgi, sqlite3, postgres, python, flask, git
*First tested app with sqlite than migrated to postgres
*Updated relative paths to absolute paths in python files
*Changed sqlite db paths to postgres server in python files
*Created psql user "catalog", configured permissions to create db only


###iv)
####List of third-party resources:
https://www.digitalocean.com/community/tutorials/how-to-configure-ssh-key-based-authentication-on-a-linux-server  
https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-on-an-ubuntu-vps 
https://www.digitalocean.com/community/tutorials/how-to-configure-the-apache-web-server-on-an-ubuntu-or-debian-vps  
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps  
http://unix.stackexchange.com/questions/2022/is-it-possible-to-break-long-lines-in-sshd-config  
http://unix.stackexchange.com/questions/127886/how-can-i-restart-the-ssh-daemon-on-ubuntu  
https://code.djangoproject.com/wiki/NewbieMistakes#DjangosaysUnabletoOpenDatabaseFilewhenusingSQLite3  
http://www.jakowicz.com/flask-apache-wsgi/  
http://serverfault.com/questions/83508/purpose-of-debian-sites-available-and-sites-enabled-dirs  
https://www.youtube.com/watch?v=yoR9WhM3EiA  
http://wsgi.tutorial.codepoint.net/  
https://www.digitalocean.com/community/tutorials/apache-vs-nginx-practical-considerations  


