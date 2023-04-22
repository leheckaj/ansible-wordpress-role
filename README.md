# Základní ansible role pro nainstalování Wordpressu na localhostu pro potřeby BSA

Pro spuštění je potřeba mít vhodně upravený soubor wordpress.yml:

apache_domain: bsa-152.kiv.zcu.cz

dle svého serveru

--------------------
Přidám server key 
-------------------


git clone git@github.com:leheckaj/ansible-wordpress-role.git

git add .

git commit -am "init"

git push


Co dělat po klonování repository
-------------------------------

Máte-li repo naclonované stačí OBSAH složky ansible přesunout do /etc/ansible
