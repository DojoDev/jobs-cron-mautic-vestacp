#Documento para ativar o Cron Jobs Do Mautic no Vestacp
>> php -q /home/user_name/web/yourdomain.com/public_html/mautic/app/console mautic:leadlists:update --env=prod

>> php -q /home/user_name/web/yourdomain.com/public_html/mautic/app/console mautic:campaigns:update -f --env=prod

>>  php -q /home/user_name/web/yourdomain.com/public_html/mautic/app/console mautic:campaigns:trigger -f --env=prod

>>  php -q /home/user_name/web/yourdomain.com/public_html/mautic/app/console mautic:email:process --env=prod

