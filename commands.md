python odoo-bin -r odoo -w animal13 --addons-path=addons -d odoo

python odoo-bin -r odoo -w animal13 --addons-path=addons -d odoo -i base 

python odoo-bin scaffold nombre-modulo-nuevo modules

python odoo-bin -r odoo -w animal13 --addons-path=addons,modules -d odoo

python odoo-bin -r odoo -w animal13 --addons-path=addons,modules -d odoo -u nombre-modulo-nuevo
