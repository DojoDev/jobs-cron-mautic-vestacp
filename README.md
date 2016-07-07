#Documento para ativar o Cron Jobs Do Mautic versão 1.4.1  no Vestacp Hospedado na Digital Ocean

> php -q /home/user_name/web/yourdomain.com/public_html/mautic/app/console mautic:leadlists:update --env=prod

> php -q /home/user_name/web/yourdomain.com/public_html/mautic/app/console mautic:campaigns:update -f --env=prod

> php -q /home/user_name/web/yourdomain.com/public_html/mautic/app/console mautic:campaigns:trigger -f --env=prod

> php -q /home/user_name/web/yourdomain.com/public_html/mautic/app/console mautic:email:process --env=prod

