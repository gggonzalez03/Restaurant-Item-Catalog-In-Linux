# Restaurant-Item-Catalog-In-Linux
IP Address: 34.203.97.167
Port: 2200
Restaurant-Item-Catalog URL: http://34.203.97.167/ or http://34.203.97.167/login
Software Installed:
    libapache2-mod-wsgi
    python-dev
    virtualenv
    Flask
    bleach
    oauth2client
    requests
    httplib2
    redis
    passlib
    itsdangerous
    flask-httpauth
Configurations:
    Changed SSH port number using /etc/ssh/sshd_config plus Lightsail firewall.
    Configured Linux UFC to allow certain ports
    Enforced SSH login
    Set linux system timezone to UTC
    Blocked linux root login using /etc/ssh/sshd_config
    Disallowed database remote connections
    Changed .git folder permissions
Third-party resources:
    Deploy Flask Application with mod_wsgi:
        https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
    Disable remote ssh root login:
        http://askubuntu.com/questions/27559/how-do-i-disable-remote-ssh-login-as-root-from-a-server
    Postgres Roles and Permissions:
        https://www.digitalocean.com/community/tutorials/how-to-use-roles-and-manage-grant-permissions-in-postgresql-on-a-vps--2
    Adding and Removing Virtual Hosts:
        https://www.abeautifulsite.net/adding-and-removing-virtual-hosts-on-ubuntu-1404
    mod_wsgi(Apache)
        http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi/
    Udacity Lessons and Forums
        https://www.udacity.com/
