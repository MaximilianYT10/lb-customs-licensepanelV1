# 🧾 lb-customs-licensepanelV1

[![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-Backend-black?logo=flask)](https://flask.palletsprojects.com/)
[![PHP](https://img.shields.io/badge/PHP-Frontend-777bb4?logo=php)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/MySQL-Database-00618a?logo=mysql)](https://www.mysql.com/)
[![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-UI-orange?logo=html5)](https://developer.mozilla.org/)
[![Status](https://img.shields.io/badge/Status-Legacy-yellow)]()
[![License](https://img.shields.io/badge/License-None-lightgrey)]()

---

> ⚠️ **Legacy Code Notice**  
> This project was built when I was still learning. The code may not be perfect — but it works flawlessly.  
> Feel free to explore, refactor, and improve it!  
>
> ⚠️ **Legacy-Code Hinweis**  
> Dieses Projekt entstand, als ich noch Anfänger war. Der Code ist vielleicht nicht der schönste, funktioniert aber zuverlässig.  
> Verbesserungen sind ausdrücklich willkommen!

---

## 🧭 Overview / Übersicht

A lightweight **license management panel** built using **Flask**, **MySQL**, **PHP**, **HTML**, and **CSS** —  
connecting a Python backend with a PHP-based frontend.

Ein leichtgewichtiges **Lizenzverwaltungspanel**, entwickelt mit **Flask**, **MySQL**, **PHP**, **HTML** und **CSS** —  
eine Kombination aus Python-Backend und PHP-Frontend.

---

## ⚡ Features / Funktionen

✅ Terms of Service / Nutzungsbedingungen  
✅ General Terms and Conditions / Allgemeine Geschäftsbedingungen  
✅ Panel Announcements / Panel-Ankündigungen  
✅ Customer Overview / Kundenübersicht  
✅ Manage Discord Bots / Discord-Bots verwalten  
✅ Ticket System / Ticketsystem  
✅ License Key Validation / Lizenzschlüssel-Validierung  
✅ MySQL Integration / MySQL-Integration  
✅ PHP Frontend / PHP-Frontend  
✅ Flask API Backend / Flask-API-Backend  

---

## 🛠 Tech Stack

| Technology   | Purpose / Verwendung        |
|---------------|-----------------------------|
| **Flask**     | Backend API (Python)        |
| **MySQL**     | Database / Datenbank        |
| **PHP**       | Frontend Logic / Logik      |
| **HTML/CSS**  | UI & Layout / Benutzeroberfläche |

---

## ⚙️ Setup Guide / Einrichtung

### 1️⃣ Clone the Repository / Repository klonen
```bash
git clone https://github.com/MaximilianYT10/lb-customs-licensepanelV1.git
cd lb-customs-licensepanelV1
```

### 2️⃣ Configure MySQL / MySQL konfigurieren
Create a database named ```licensepanel```
Import the provided ```database.sql``` (if available)
Update your credentials in ```mysql.php```

### 3️⃣ Configure the Backend / Backend konfigurieren
Open ```home/discord-backend/main.py```
Add a random API token:
```Python
API_TOKEN = os.getenv("API_TOKEN", "YourRandomBackendToken123!")
```
Save the file

### 4️⃣ Configure the Website / Website konfigurieren
Open ```html/backend/config.php```
Replace the placeholder with your random token:
```php
$authorizationToken = "YourRandomBackendToken123!";
```
Replace every occurrence of
```https://license.your-domain.xyz```
with your actual domain, e.g.
```https://license.myawesomeserver.de```

### ▶️ Run / Starten
Backend:
```bash
cd home/discord-backend
python main.py
```
Website:
Upload the ```website``` folder to your web server or run it locally via XAMPP, MAMP, etc.

### 🤝 Contributing / Mitwirken
Feel free to fork, refactor, and submit pull requests.
Du darfst gerne forken, refactoren und Pull Requests senden.

### 📄 License / Lizenz
No license provided – use at your own risk.
Keine Lizenz angegeben – Nutzung auf eigene Gefahr.

### 📬 Contact / Kontakt
GitHub: @MaximilianYT10
Discord: ```max_zocker```
