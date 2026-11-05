# Nicolas Kanian

🌐 **[ EN English Version](#-english-version)** | **[ 🇫🇷 Version Française](#-version-française)**

---

<a name="-english-version"></a>
## EN English Version

**Software Engineering, Full-Stack & Biomedical Image Processing**  
Computer Science Engineering - CESI Strasbourg (Anglophone Track)

### About
Computer science engineering student focused on software architecture, scientific computing, and full-stack web applications. I build production-ready tools, automated research pipelines, and custom embedded systems designed for real-world operational constraints.

🎯 **Open to a 5th-year apprenticeship / professionalization contract (Contrat de professionnalisation) for 2027-2028**

---

### Projects

#### 🏥 Research & Enterprise Software

**[MITI2 - 3D OCT Biomedical Image Processing Pipeline](https://github.com/Nicolas-KANIAN/MITI2)**  
Contribution to the European MITI2 project dedicated to applied learning in Optical Coherence Tomography (OCT) imaging, in collaboration with ICube, INSERM UMR 1260, and Lamina Therapeutics. Built an automated Python pipeline for 3D knee cartilage and bone reconstruction, DICOM calibration, denoising, and tissue quantification.  
`Python` `OOP` `scikit-image` `OpenCV` `pydicom` `tifffile` `DuckDB` `Seaborn`

**[Armoni.cloud - Custom Enterprise ERP (CIRPé SAS)](https://armoni.cloud/)**  
Full-stack development across two internships on a production ERP platform: digitization and automation of client audits, technician task and deadline tracking, automated part replacement requests for landlords, grouped intervention billing, attachment thumbnail generation, and critical incident resolution.  
`Symfony` `PHP` `MySQL` `Full-Stack` `ERP` `Project Management`

**[INSERM UMR 1260 - Official Laboratory Platform](https://github.com/UMR1260/Website-UMR1260)**  
Full-stack overhaul of the Regenerative Nanomedicine research unit's web platform. Built a custom back-office and automated scientific publication synchronization connected directly to the national HAL API.  
`Symfony 7` `PHP` `Twig` `EasyAdmin` `Bootstrap 5` `REST API` `MySQL`

**[Auto-École Bourneville - Web Platform](https://github.com/Nicolas-KANIAN/auto_ecole_bourneville)**  
Production showcase web platform and automated contact and SMTP mailing service developed for a driving school.  
`Symfony` `PHP` `Symfony Mailer` `SMTP` `Bootstrap` `HTML5 / CSS3`

---

#### 🧠 AI, Data Science & Operations Research

**[HumanForYou - Employee Turnover Prediction & Ethical AI](https://github.com/Nicolas-KANIAN/AI)**  
Supervised machine learning pipeline predicting employee attrition across 4,410 employees by aggregating 6 data sources (HR records, satisfaction surveys, and 46 MB of badge timestamps). Built in compliance with European ALTAI ethical guidelines (removal of gender, age, and marital status biases). Benchmarks across 7 models led to an optimized Random Forest (`GridSearchCV`, balanced class weights, 0.25 decision threshold) achieving **97.1% accuracy**, **95.2% recall** (198/208 departures detected), and a **0.91 F1-score**.  
`Python` `scikit-learn` `Pandas` `Random Forest` `Feature Engineering` `ALTAI Ethical AI` `Jupyter`

**[Smart Multimodal Mobility - VRP Combinatorial Optimization](https://github.com/Nicolas-KANIAN/Advanced-Algorithms-and-Combinatorics)** *(and [Projet_algo](https://github.com/Low8/Projet_algo))*  
Operations Research project answering an ADEME green mobility challenge. Modeled and solved large-scale Vehicle Routing Problems with Time Windows (VRPTW - thousands of cities) considering multi-truck fleet allocation, 2D/3D capacity footprints, pickup-and-delivery constraints, and time-dependent traffic variations. Included statistical benchmarking on Solomon datasets.  
`Python` `PuLP` `NetworkX` `vrplib` `SciPy` `NumPy` `Joblib` `Operations Research`

---

#### 💻 Software Architecture & Full-Stack Web

**[EasySave - Professional Backup Management Suite (ProSoft)](https://github.com/Nicolas-KANIAN/EasySave)**  
End-to-end software engineering project developed across three major releases (v1.0 Console to v2.0 MVVM GUI to v3.0 parallelized engine). Supports full and differential backups, multi-threading, file encryption, business software detection, and millisecond-level real-time logging via a custom `EasyLog.dll` library (dynamic JSON/XML output). Enforced via a strict DevOps pipeline with xUnit automated testing, `.editorconfig` formatting, and CodeRabbit AI PR reviews.  
`C#` `.NET 8.0` `MVVM` `xUnit` `Multi-threading` `CI/CD` `EasyLog.dll`

**[CESI TON STAGE - Internship & Application Management Platform](https://github.com/Nicolas-KANIAN/Web-development)** *(and [CESI_TON_STAGE](https://github.com/Vore667/CESI_TON_STAGE))*  
Object-oriented PHP 8 web application built from scratch on a custom MVC router and PDO architecture. Features 4-tier role authentication (Admin, Pilot, Student, Guest), company and internship offer management, PDF resume and cover letter uploads, wishlists, 20-point dynamic star ratings, analytical dashboards, and PHPMailer integration.  
`PHP 8` `OOP` `MVC Architecture` `MySQL / PDO` `PHPMailer` `JavaScript` `HTML5 / CSS3`

**[Conway's Game of Life - Object-Oriented Simulation](https://github.com/Nicolas-KANIAN/Programmation-orientee-objet)** *(and [POO](https://github.com/gauthierwbl/POO) / [projet_poo](https://github.com/xX-Miyu-Xx/projet_poo))*  
C++17 object-oriented cellular automaton simulator supporting both toroidal and non-toroidal grids in Console and interactive SFML graphical modes (real-time speed control, step-by-step execution, interactive mouse cell toggling, and text file persistence). Engineered with polymorphic cell cloning and strict memory management (Rule of Five).  
`C++17` `SFML` `OOP` `Rule of Five` `Polymorphism` `Makefile`

---

#### 🔌 Embedded Systems & Hardware Engineering

**[Embedded Linux Automotive Head Unit](https://github.com/Nicolas-KANIAN/Carplay)**  
Custom in-vehicle infotainment system engineered on Raspberry Pi 5. Features a hardware-accelerated UI, background `systemd` services, OBD-II/CAN bus telemetry, reverse camera feed, local audio playback, and offline OpenStreetMap routing.  
`C++` `Qt 6 / QML` `Embedded Linux` `systemd` `CAN Bus / OBD-II` `Raspberry Pi 5`

**[Worldwide Weather Watcher (3W) - Maritime Embedded Weather Station](https://github.com/Nicolas-KANIAN/Systeme-Embarque)** *(and [Projet-Systeme-Embarque](https://github.com/En0ri4n/Projet-Systeme-Embarque))*  
Autonomous embedded maritime weather station built on ATmega328P (Arduino Uno) using PlatformIO. Implements a 4-state finite state machine (Standard, Eco, Maintenance, and Serial CLI Configuration with EEPROM persistence) driven by hardware interrupts. Interfaces with BME280 (I2C), DS1307 RTC (I2C), GPS (UART NMEA `$GPGGA`), light sensor (ADC), FAT32 SD card logger with automatic file rotation (SPI), and P9813 RGB LED diagnostic error codes.  
`C / C++` `ATmega328P` `PlatformIO` `I2C / SPI / UART` `Finite State Machine` `EEPROM` `FAT32 SD`

**[StrongBox3000 - Adaptive Multi-Factor Electronic Vault](https://github.com/Nicolas-KANIAN/StrongBox3000)** *(and [MaxMax6767/StrongBox3000](https://github.com/MaxMax6767/StrongBox3000))*  
Hardware and software co-design of an adaptive security vault prototyped on Tinkercad and Arduino Uno (ATmega328P). Combines a physical sequential 4-button digicode with an analog voltage divider (8 ADC security profiles on pin A0) triggering progressive UART authentication challenges (9600 bauds): Q&A verification, zero-knowledge RSA asymmetric cryptography challenge-response ($n=2881$ with modular exponentiation overflow protection), simulated biometric scans, and agent badge cross-checking.  
`C / C++` `Arduino Uno` `RSA Cryptography` `ADC / UART` `Hardware Security` `Tinkercad`

---

### Tech Stack
- **Scientific, AI & Data** - Python - scikit-learn - Pandas - PuLP - NetworkX - OpenCV - scikit-image - pydicom - tifffile - DuckDB - Seaborn
- **Backend & Software** - PHP 8 (Symfony 7 / Custom MVC) - C# (.NET 8.0 / xUnit) - C++17 (Qt 6 / QML / SFML) - COBOL - SQL (MySQL / IBM Db2)
- **Embedded & Hardware** - C / C++ (ATmega328P / Arduino) - Embedded Linux (Raspberry Pi 5) - PlatformIO - I2C / SPI / UART / CAN Bus
- **Frontend & Tools** - Twig - JavaScript - Bootstrap 5 - Tailwind CSS - HTML5 / CSS3 - Docker - Git - systemd - Bash - PowerShell - Makefile

### Experience
- **INSERM UMR 1260** - Computer Science Engineering Intern (Sept. 2026 - Present)  
  European MITI2 project on OCT imaging, 3D reconstruction of knee cartilage and bone with Lamina Therapeutics & ICube, and full-stack development of the unit's official website.
- **CIRPé SAS** - Full-Stack Developer Intern (Jan. 2026 - Apr. 2026 & Apr. 2025 - Jul. 2025 - 8 months total)  
  Development on the [Armoni.cloud](https://armoni.cloud/) ERP: client audit digitization, technician task tracking, automated landlord replacement requests, grouped intervention billing, and workflow optimization.
- **Euro-Information Développement** - Analyst Developer Intern (Apr. 2024 - Jul. 2024 - 4 months)  
  Project scoping, functional specifications under EID standards, COBOL program development, IBM Db2 database integration, and intranet console output implementation.

### Languages
🇫🇷 **French** - Native - **EN English** - Advanced (Anglophone Engineering Track)

---

<a name="-version-française"></a>
## 🇫🇷 Version Française

<details open>
<summary><b>Afficher / Masquer la version française</b></summary>
<br>

**Ingénierie Logicielle, Full-Stack & Imagerie Biomédicale**  
Cycle Ingénieur Informatique - CESI Strasbourg (Cursus Anglophone)

### À propos
Étudiant ingénieur en informatique spécialisé dans l'architecture logicielle, le calcul scientifique et le développement Full-Stack. Je conçois des outils destinés à la production : pipelines de recherche automatisés, ERP métiers et systèmes embarqués sur mesure.

🎯 **Ouvert à un contrat de professionnalisation (5e année d'ingénieur - A5) pour l'année 2027-2028**

---

### Projets

#### 🏥 Recherche & Logiciels d'Entreprise

**[MITI2 - Pipeline d'Imagerie Biomédicale 3D (OCT)](https://github.com/Nicolas-KANIAN/MITI2)**  
Participation au projet européen MITI2 consacré à l'imagerie OCT (Optical Coherence Tomography) en collaboration avec ICube, l'INSERM UMR 1260 et Lamina Therapeutics. Reconstitution 3D du cartilage et de l'os du genou, calibration DICOM, débruitage et développement d'outils logiciels pour la recherche médicale.  
`Python` `POO` `scikit-image` `OpenCV` `pydicom` `tifffile` `DuckDB` `Seaborn`

**[Armoni.cloud - ERP Métier sur mesure (CIRPé SAS)](https://armoni.cloud/)**  
Développement Full-Stack sur deux stages au sein de l'ERP en production : numérisation et automatisation des audits clients, suivi des tâches techniciens et gestion des délais, automatisation des demandes de remplacement de pièces aux bailleurs, facturation groupée d'interventions, génération de miniatures et résolution d'incidents critiques.  
`Symfony` `PHP` `MySQL` `Full-Stack` `ERP` `Gestion de projet`

**[INSERM UMR 1260 - Plateforme Web Officielle du Laboratoire](https://github.com/UMR1260/Website-UMR1260)**  
Refonte Full-Stack du site de l'unité de recherche en Nanomédecine Régénérative. Développement d'un back-office sur mesure et synchronisation automatisée des publications scientifiques via l'API nationale HAL.  
`Symfony 7` `PHP` `Twig` `EasyAdmin` `Bootstrap 5` `API REST` `MySQL`

**[Auto-École Bourneville - Plateforme Web](https://github.com/Nicolas-KANIAN/auto_ecole_bourneville)**  
Développement d'un site vitrine en production et d'un service automatisé de prise de contact et de messagerie SMTP.  
`Symfony` `PHP` `Symfony Mailer` `SMTP` `Bootstrap` `HTML5 / CSS3`

---

#### 🧠 Intelligence Artificielle, Data Science & Recherche Opérationnelle

**[HumanForYou - Prédiction du Turnover & IA Éthique RH](https://github.com/Nicolas-KANIAN/AI)**  
Système de Machine Learning supervisé prédisant le risque de démission sur 4 410 collaborateurs via l'agrégation de 6 sources de données (données RH, enquêtes de satisfaction et 46 Mo d'horodatages de pointage traités en multithreading). Conçu selon le cadre éthique européen ALTAI (éviction des variables discriminantes : genre, âge, statut marital). Benchmark de 7 algorithmes aboutissant à un Random Forest optimisé (`GridSearchCV`, pondération des classes, seuil à 0.25) atteignant **97.1 % d'accuracy**, **95.2 % de rappel** (198 départs anticipés sur 208) et un **F1-score de 0.91**.  
`Python` `scikit-learn` `Pandas` `Random Forest` `Feature Engineering` `IA Éthique ALTAI` `Jupyter`

**[Smart Multimodal Mobility - Optimisation Combinatoire VRP (ADEME)](https://github.com/Nicolas-KANIAN/Advanced-Algorithms-and-Combinatorics)** *(et [Projet_algo](https://github.com/Low8/Projet_algo))*  
Projet de Recherche Opérationnelle répondant à un appel à projets de l'ADEME sur la mobilité durable. Modélisation et résolution de problèmes de tournées de véhicules à grande échelle (VRP / VRPTW sur plusieurs milliers de villes) intégrant des fenêtres de temps, flottes multi-camions, capacités 2D/3D, points de collecte spécifiques et variations de trafic temporelles. Étude statistique et benchmark sur les instances de Solomon.  
`Python` `PuLP` `NetworkX` `vrplib` `SciPy` `NumPy` `Joblib` `Recherche Opérationnelle`

---

#### 💻 Architecture Logicielle & Développement Web

**[EasySave - Progiciel de Gestion de Sauvegardes (ProSoft)](https://github.com/Nicolas-KANIAN/EasySave)**  
Développement complet d'un logiciel de sauvegarde professionnel sur 3 versions majeures (v1.0 Console vers v2.0 GUI MVVM puis v3.0 parallélisée). Gestion de sauvegardes complètes et différentielles, exécution parallèle en multi-threading, chiffrement, détection de logiciels métiers et journalisation temps réel à la milliseconde via une DLL dédiée (`EasyLog.dll` en JSON/XML). Pipeline CI/CD intégrant tests unitaires automatisés xUnit, `.editorconfig` et revue de PR par IA (CodeRabbit).  
`C#` `.NET 8.0` `MVVM` `xUnit` `Multi-threading` `CI/CD` `EasyLog.dll`

**[CESI TON STAGE - Plateforme de Gestion de Stages et Candidatures](https://github.com/Nicolas-KANIAN/Web-development)** *(et [CESI_TON_STAGE](https://github.com/Vore667/CESI_TON_STAGE))*  
Application web développée en PHP 8 orienté objet selon une architecture MVC sur mesure avec PDO. Authentification multirôle (Administrateur, Pilote, Étudiant, Invité), gestion des entreprises et offres de stage, dépôt de CV (PDF) et lettres de motivation, système de wishlist, notation dynamique en étoiles, tableau de bord statistique et messagerie PHPMailer.  
`PHP 8` `POO` `Architecture MVC` `MySQL / PDO` `PHPMailer` `JavaScript` `HTML5 / CSS3`

**[Jeu de la Vie de Conway - Simulation Orientée Objet](https://github.com/Nicolas-KANIAN/Programmation-orientee-objet)** *(et [POO](https://github.com/gauthierwbl/POO) / [projet_poo](https://github.com/xX-Miyu-Xx/projet_poo))*  
Implémentation en C++17 orienté objet de l'automate cellulaire de Conway (grilles toriques et non-toriques) avec double moteur d'exécution : mode Console et interface graphique interactive SFML (contrôle de vitesse à la volée, mode pas-à-pas, activation de cellules à la souris et persistance sur fichiers texte). Architecture reposant sur le clonage polymorphique et la Règle des 5.  
`C++17` `SFML` `POO` `Règle des 5` `Polymorphisme` `Makefile`

---

#### 🔌 Systèmes Embarqués & Électronique

**[Système Multimédia Automobile Linux Embarqué](https://github.com/Nicolas-KANIAN/Carplay)**  
Conception d'un Head Unit embarqué sur Raspberry Pi 5. Interface graphique accélérée matériellement, services système `systemd`, télémétrie OBD-II / CAN bus, caméra de recul, lecteur audio local et navigation hors-ligne OpenStreetMap.  
`C++` `Qt 6 / QML` `Linux Embarqué` `systemd` `CAN Bus / OBD-II` `Raspberry Pi 5`

**[Worldwide Weather Watcher (3W) - Station Météo Maritime Embarquée](https://github.com/Nicolas-KANIAN/Systeme-Embarque)** *(et [Projet-Systeme-Embarque](https://github.com/En0ri4n/Projet-Systeme-Embarque))*  
Prototype de station météorologique autonome pour navires sur microcontrôleur ATmega328P (Arduino Uno) sous PlatformIO. Architecture basée sur une machine à états finis à 4 modes (Standard, Économique, Maintenance, et Configuration par console série avec sauvegarde en EEPROM) pilotée par interruptions matérielles. Acquisition multi-capteurs (BME280 en I2C, horloge RTC DS1307 en I2C, GPS UART NMEA `$GPGGA`, capteur optique ADC), enregistrement sur carte SD FAT32 avec rotation automatique des fichiers `.log` (SPI) et diagnostic de pannes par codes couleurs sur LED RGB chaînable P9813.  
`C / C++` `ATmega328P` `PlatformIO` `I2C / SPI / UART` `Machine à États` `EEPROM` `Carte SD FAT32`

**[StrongBox3000 - Coffre-Fort Électronique à Sécurité Adaptative](https://github.com/Nicolas-KANIAN/StrongBox3000)** *(et [MaxMax6767/StrongBox3000](https://github.com/MaxMax6767/StrongBox3000))*  
Co-design matériel et logiciel d'un coffre-fort à défense en profondeur modélisé sous Tinkercad et déployé sur Arduino Uno (ATmega328P). Combine un sas physique (digicode séquentiel à 4 boutons-poussoirs) et un pont diviseur de tension (8 profils ADC sur broche A0) déclenchant des protocoles d'authentification progressifs sur liaison série UART (9600 bauds) : QCM, défi-réponse par cryptographie asymétrique RSA à divulgation nulle ($n=2881$ avec exponentiation modulaire protégée contre l'overflow), scans biométriques simulés et contrôle croisé d'identifiant de badge.  
`C / C++` `Arduino Uno` `Cryptographie RSA` `ADC / UART` `Sécurité Matérielle` `Tinkercad`

---

### Stack Technique
- **Imagerie, IA & Data** - Python - scikit-learn - Pandas - PuLP - NetworkX - OpenCV - scikit-image - pydicom - tifffile - DuckDB - Seaborn
- **Backend & Logiciel** - PHP 8 (Symfony 7 / MVC sur mesure) - C# (.NET 8.0 / xUnit) - C++17 (Qt 6 / QML / SFML) - COBOL - SQL (MySQL / IBM Db2)
- **Systèmes Embarqués** - C / C++ (ATmega328P / Arduino) - Linux Embarqué (Raspberry Pi 5) - PlatformIO - I2C / SPI / UART / CAN Bus
- **Frontend & Outils** - Twig - JavaScript - Bootstrap 5 - Tailwind CSS - HTML5 / CSS3 - Docker - Git - systemd - Bash - PowerShell - Makefile

### Expériences Professionnelles
- **INSERM UMR 1260** - Stagiaire Ingénieur Informatique (Sept. 2026 - Aujourd'hui)  
  Participation au projet européen MITI2 (imagerie OCT), reconstitution 3D du cartilage et de l'os du genou en collaboration avec Lamina Therapeutics et ICube, développement d'outils logiciels pour la recherche médicale et refonte du site web de l'unité.
- **CIRPé SAS** - Stagiaire Développeur Full-Stack (Janv. 2026 - Avr. 2026 & Avr. 2025 - Juil. 2025 - 8 mois)  
  Développement sur l'ERP [Armoni.cloud](https://armoni.cloud/) : numérisation et automatisation des audits clients, suivi des tâches techniciens, automatisation des demandes de remplacement de pièces aux bailleurs, facturation groupée d'interventions et résolution d'incidents critiques.
- **Euro-Information Développement** - Stagiaire Analyste Développeur (Avr. 2024 - Juil. 2024 - 4 mois)  
  Étude initiale, rédaction des spécifications fonctionnelles aux normes EID, développement de programmes en COBOL avec IBM Db2 et affichage des résultats dans la console intranet.

### Langues
🇫🇷 **Français** - Langue maternelle - **EN Anglais** - Courant (Cursus Ingénieur Anglophone)

</details>
