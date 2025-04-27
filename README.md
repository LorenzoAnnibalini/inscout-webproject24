# 🌍 INSCOUT - Un Social Network Scoutistico

Benvenuto in **Inscout**, il social network dedicato agli appassionati di scouting!  
Questo progetto è stato sviluppato nell'ambito del corso di **Tecnologie Web** e mira a creare una piattaforma per gli amanti dello scouting, dove gli utenti possono connettersi, condividere esperienze e molto altro.

---

## 📖 Descrizione del Progetto

**Inscout** è un social network pensato per chi condivide la passione per lo scouting. Gli utenti possono creare profili personalizzati, condividere foto, e ottenere medaglie virtuali che rendono il loro profilo unico. L'intera piattaforma è progettata per essere semplice e interattiva, con un'attenzione particolare alla creazione di una comunità attiva e dinamica.

---

## 👨‍💻 Sviluppatori

- **Annibalini Lorenzo**
- **Buda Francesco**
- **Ceredi Tommaso**

---

## ⚙️ Caratteristiche Principali

- **Profili utente personalizzati**: Ogni utente ha la possibilità di creare e personalizzare il proprio profilo.
- **Feed per condividere foto**: Gli utenti possono condividere le loro esperienze scout in un feed fotografico.
- **Medaglie per il profilo**: Guadagna medaglie e personalizza il tuo profilo in base alle tue attività scout.

---

## 🛠️ Tecnologie Utilizzate

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Apache, PHP
- **Database**: MySQL
- **Version Control**: Git
- **Hosting**: Raspberry Pi 4 Model B 4GB

---

## 🖥️ Setup per lo sviluppo locale

- Installare XAMPP
- Clonare il repository nella cartella htdocs di XAMPP
- Avviare Apache
- Creare il file `conf.env` nella cartella `connection` con il seguente contenuto:
- Eseguire il comando per installare JWT `sudo composer require firebase/php-jwt`
- Eseguire il comando per installare SendGrid `sudo composer require sendgrid/sendgrid`

## 🍓Comandi utili per il deploy su Raspberry Pi 4
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

