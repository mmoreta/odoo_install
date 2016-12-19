# odoo_install
Instalación Odoo 9 en ubuntu 16.04
******************************************************************************

1- Ejecutar siguiente comando.
sudo wget https://raw.githubusercontent.com/Yenthe666/InstallScript/All/odoo_install.sh

2- Abrir archivo y editar parametros.
sudo nano odoo_install.sh

3- Convertir archivo a ejecutable.
sudo chmod +x odoo_install.sh

4- Correr el script.
./odoo_install.sh

5- Comenzar a utilizar el Odoo, al finalizar debe aparecer este detalle.
-----------------------------------------------------------
Done! The Odoo server is up and running. Specifications:
Port: 8069
User service: odoo
User PostgreSQL: odoo
Code location: odoo
Addons folder: odoo/odoo-server/addons/
Start Odoo service: sudo service odoo-server start
Stop Odoo service: sudo service odoo-server stop
Restart Odoo service: sudo service odoo-server restart
-----------------------------------------------------------
