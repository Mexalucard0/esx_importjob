# esx_importjob

ESX IMPORT JOB


[REQUIREMENTS]

* Player management (billing and boss actions)
  * esx_society => https://github.com/ESX-Org/esx_society
  * esx_billing => https://github.com/ESX-Org/esx_billing

* Items effects (hunger, thirst, drunk)
  * esx_status => https://github.com/ESX-Org/esx_status
  * esx_basicneeds => https://github.com/ESX-Org/esx_basicneeds
  * esx_optionalsneeds => https://github.com/ESX-Org/esx_optionalneeds


[INSTALLATION]

1) CD in your resources/[esx] folder

3) Import esx_importjob.sql in your database

4) Add this in your server.cfg :

```
start esx_importjob
