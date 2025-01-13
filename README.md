# INSCOUT
## Un Social Network Scoutistico

Benvenuto in Inscout, il social network dedicato agli appassionati di scouting!

## Descrizione del Progetto

Questo progetto è un social network sviluppato nell'ambito del corso di Tecnologie Web. Si tratta di una piattaforma pensata per gli amanti dello scouting, dove gli utenti possono connettersi, condividere esperienze scout, e molto altro.

## Sviluppatori

- Annibalini Lorenzo
- Buda Francesco
- Ceredi Tommaso

## Caratteristiche Principali

- Profili utente personalizzati
- Feed per condividere foto
- Medaglie per personalizzare il profilo

## Tecnologie Utilizzate

- Frontend: HTML, CSS, JavaScript, Bootstrap
- Backend: Apache, Php
- Database: MySql
- Version Control: Git
- Hosting: Raspberry Pi 4 Model B 4GB

## Setup local development

- Installare XAMPP
- Clonare il repository nella cartella htdocs di XAMPP
- Avviare Apache
- Creare il file `conf.env` nella cartella `connection` con il seguente contenuto:
- Eseguire il comando per installare JWT `sudo composer require firebase/php-jwt`
- Eseguire il comando per installare SendGrid `sudo composer require sendgrid/sendgrid`

## Comandi utili per il deploy su Raspberry Pi 4
- Copiare il contenuto `sudo cp -rf /home/tom/Documenti/inscout-wp24/* ./`
- Controllare le autorizzazioni `sudo chmod 775 ./static/*` e `sudo chown -R www-data:www-data ./static/*`
- Riavviare Apache `sudo service apache2 restart`



```
DB_HOST=[server ip]
DB_USER=[db username]
DB_PASSWORD=[db password]
DB_NAME=[db name]
JWT_SECRET_TOKEN=[jwt secret]
SHA_SECRET_TOKEN=[sha secret]
SENDGRID_API_KEY=[sendgrid api key]
```
