KONFIGURASI APACHE2

root@manusa:~# apt install apache2

root@manusa:~# nano /etc/apache2/sites- available/000-default.conf

ServerName mail.smkmanusa.sch.id

ServerAdmin webmaster@mail.smkmanusa.sch.id

DocumentRoot /var/lib/roundcube

root@manusa:~# systemctl restart apache2

root@manusa:~#
