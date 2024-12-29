# Italian


# Sito E-commerce di Vendita di Oggetti Usati

Benvenuto nel progetto **Presto Shop**! Questo progetto è stato sviluppato con **Laravel**, **Bootstrap 5.3**, **Bootstrap Icons** e utilizza **Google AI Vision** per migliorare l'esperienza utente. 

L'applicazione offre una piattaforma completa per la gestione e la pubblicazione di annunci di vendita, inclusa una sezione dedicata ai revisori e funzionalità avanzate come CRUD completo, autenticazione utenti e supporto multilingua.

---

## Caratteristiche Principali

- **E-commerce**: Consente la vendita di oggetti usati.
- **CRUD Funzionante**: Gestione completa di annunci, utenti e categorie.
- **Pagina Revisore**: Per accettare o rifiutare gli annunci pubblicati.
- **Google AI Vision**: Implementato per analizzare e classificare le immagini caricate.
- **Login e Registrazione**: Sistema completo di autenticazione utente.
- **Form Avanzato**: Modulo per l'inserimento di annunci.
- **Traduzione Completa**: Supporto per più lingue per migliorare l'accessibilità globale.

---

## Tecnologie Utilizzate

- **Backend**: PHP 8.3, Laravel 11, Livewire
- **Frontend**: Bootstrap 5.3
- **Icone**: Bootstrap Icons
- **Gestione Pacchetti**: Node.js con npm
- **AI**: Google AI Vision

---

## Requisiti di Sistema

- **PHP**: >= 8.3
- **Composer**: Installato sul sistema
- **Node.js**: >= 16.x
- **Database**: MySQL o altro compatibile

---

## Installazione e Configurazione

Segui questi passaggi per clonare e configurare il progetto:

1. **Clona la repository**:
   ```bash
   git clone <chiave-ssh-della-repository>
   cd <nome-cartella-repository>
   ```

2. **Installa le dipendenze PHP**:
   ```bash
   composer install
   ```

3. **Crea il file `.env`**:
   ```bash
   cp .env.example .env
   ```

4. **Genera la chiave dell'applicazione**:
   ```bash
   php artisan key:generate
   ```

5. **Esegui le migrazioni per creare il database**:
   ```bash
   php artisan migrate
   ```

6. **Installa le dipendenze JavaScript**:
   ```bash
   npm install
   ```

7. **Compila i file CSS e JavaScript**:
   ```bash
   npm run dev
   ```

8. **Avvia il server di sviluppo**:
   ```bash
   php artisan serve
   ```

Accedi all'applicazione visitando [http://localhost:8000](http://localhost:8000) nel tuo browser.

---

## Pacchetti Utilizzati

- **google/cloud-vision**: ^1.10
- **laravel/fortify**: ^1.25
- **laravel/framework**: ^11.31
- **laravel/scout**: ^10.11
- **laravel/tinker**: ^2.9
- **livewire/livewire**: ^3.5
- **outhebox/blade-flags**: ^1.5
- **spatie/image**: ^3.7
- **teamtnt/laravel-scout-tntsearch-driver**: ^14.0

---

## Utilizzo dell'Applicazione

1. **Homepage**:
   - Visualizza gli annunci più recenti.
   
2. **Login e Registrazione**:
   - Accedi o crea un account per gestire i tuoi annunci.

3. **Inserimento Annunci**:
   - Crea un nuovo annuncio compilando il modulo dedicato.

4. **Sezione Revisore**:
   - Gli amministratori possono accettare o rifiutare gli annunci pubblicati dagli utenti.

---

## Funzionalità per gli Sviluppatori

- **Gestione CRUD**: Puoi facilmente aggiungere, modificare o eliminare annunci, utenti e categorie.
- **Integrazione con Google AI Vision**: Analizza le immagini degli annunci per garantire conformità e qualità.
- **Sistema Multilingua**: Tutti i testi sono tradotti per supportare più lingue.

---

Grazie per aver scelto questo progetto! Se hai domande o suggerimenti, non esitare a contattarmi.

# English

# Presto Shop

Welcome to the **Presto Shop** project! This e-commerce platform is developed using **Laravel**, **Bootstrap 5.3**, **Bootstrap Icons**, and **Google AI Vision** to provide a seamless experience for buying and selling used items.

The application offers a comprehensive set of features, including a dedicated reviewer section, full CRUD functionality, multilingual support, and more.

---

## Key Features

- **E-commerce**: Facilitates buying and selling of used items.
- **CRUD Functionality**: Full management of ads, users, and categories.
- **Reviewer Page**: For approving or rejecting published ads.
- **Google AI Vision**: Utilized for analyzing and classifying uploaded images.
- **Login and Registration**: Secure user authentication system.
- **Advanced Form**: Dedicated module for ad submission.
- **Full Translation**: Multilingual support for enhanced accessibility.

---

## Technologies Used

### Backend:
- PHP 8.3
- Laravel 11
- Livewire

### Frontend:
- Bootstrap 5.3
- Bootstrap Icons

### AI:
- Google AI Vision

### Package Management:
- Node.js with npm

---

## System Requirements

- **PHP**: >= 8.3
- **Composer**: Installed on the system
- **Node.js**: >= 16.x
- **Database**: MySQL or compatible

---

## Installation and Setup

Follow these steps to clone and configure the project:

1. **Clone the repository**:
   ```bash
   git clone <your-repository-ssh-key>
   cd <repository-folder-name>
   ```

2. **Install PHP dependencies**:
   ```bash
   composer install
   ```

3. **Create the `.env` file**:
   ```bash
   cp .env.example .env
   ```

4. **Generate the application key**:
   ```bash
   php artisan key:generate
   ```

5. **Run migrations to create the database**:
   ```bash
   php artisan migrate
   ```

6. **Install JavaScript dependencies**:
   ```bash
   npm install
   ```

7. **Compile CSS and JavaScript files**:
   ```bash
   npm run dev
   ```

8. **Start the development server**:
   ```bash
   php artisan serve
   ```

Access the application by visiting [http://localhost:8000](http://localhost:8000) in your browser.

---

## Used Packages

- **google/cloud-vision**: ^1.10
- **laravel/fortify**: ^1.25
- **laravel/framework**: ^11.31
- **laravel/scout**: ^10.11
- **laravel/tinker**: ^2.9
- **livewire/livewire**: ^3.5
- **outhebox/blade-flags**: ^1.5
- **spatie/image**: ^3.7
- **teamtnt/laravel-scout-tntsearch-driver**: ^14.0

---

## Application Usage

1. **Homepage**:
   - View the most recent ads.

2. **Login and Registration**:
   - Log in or create an account to manage your ads.

3. **Ad Submission**:
   - Create a new ad by filling out the dedicated form.

4. **Reviewer Section**:
   - Administrators can approve or reject ads submitted by users.

---

## Developer Features

- **CRUD Management**: Easily add, edit, or delete ads, users, and categories.
- **Integration with Google AI Vision**: Analyze ad images to ensure compliance and quality.
- **Multilingual System**: All text is translated to support multiple languages.

---



Thank you for choosing **Presto Shop**! If you have any questions or suggestions, feel free to contact me.

---
# Français
# Presto Shop (FR)

Bienvenue dans le projet **Presto Shop** ! Cette plateforme e-commerce est développée avec **Laravel**, **Bootstrap 5.3**, **Bootstrap Icons**, et utilise **Google AI Vision** pour offrir une expérience fluide pour l'achat et la vente d'objets d'occasion.

L'application propose un ensemble complet de fonctionnalités, notamment une section dédiée aux réviseurs, un CRUD complet, une prise en charge multilingue, et bien plus encore.

---

## Principales Fonctionnalités

- **E-commerce** : Permet l'achat et la vente d'objets d'occasion.
- **CRUD Fonctionnel** : Gestion complète des annonces, utilisateurs et catégories.
- **Page Réviseur** : Pour accepter ou rejeter les annonces publiées.
- **Google AI Vision** : Utilisé pour analyser et classer les images téléchargées.
- **Connexion et Inscription** : Système sécurisé d'authentification des utilisateurs.
- **Formulaire Avancé** : Module dédié à la soumission d'annonces.
- **Traduction Complète** : Prise en charge multilingue pour une meilleure accessibilité.

---

## Technologies Utilisées

### Backend :
- PHP 8.3
- Laravel 11
- Livewire

### Frontend :
- Bootstrap 5.3
- Bootstrap Icons

### IA :
- Google AI Vision

### Gestion de Paquets :
- Node.js avec npm

---

## Configuration Système

- **PHP** : >= 8.3
- **Composer** : Installé sur le système
- **Node.js** : >= 16.x
- **Base de Données** : MySQL ou compatible

---

## Installation et Configuration

Suivez ces étapes pour cloner et configurer le projet :

1. **Clonez le dépôt** :
   ```bash
   git clone <votre-clé-ssh-du-dépôt>
   cd <nom-du-dossier-du-dépôt>
   ```

2. **Installez les dépendances PHP** :
   ```bash
   composer install
   ```

3. **Créez le fichier `.env`** :
   ```bash
   cp .env.example .env
   ```

4. **Générez la clé de l'application** :
   ```bash
   php artisan key:generate
   ```

5. **Exécutez les migrations pour créer la base de données** :
   ```bash
   php artisan migrate
   ```

6. **Installez les dépendances JavaScript** :
   ```bash
   npm install
   ```

7. **Compilez les fichiers CSS et JavaScript** :
   ```bash
   npm run dev
   ```

8. **Démarrez le serveur de développement** :
   ```bash
   php artisan serve
   ```

Accédez à l'application en visitant [http://localhost:8000](http://localhost:8000) dans votre navigateur.

---

## Paquets Utilisés

- **google/cloud-vision** : ^1.10
- **laravel/fortify** : ^1.25
- **laravel/framework** : ^11.31
- **laravel/scout** : ^10.11
- **laravel/tinker** : ^2.9
- **livewire/livewire** : ^3.5
- **outhebox/blade-flags** : ^1.5
- **spatie/image** : ^3.7
- **teamtnt/laravel-scout-tntsearch-driver** : ^14.0

---

## Utilisation de l'Application

1. **Page d'Accueil** :
   - Consultez les annonces les plus récentes.

2. **Connexion et Inscription** :
   - Connectez-vous ou créez un compte pour gérer vos annonces.

3. **Soumission d'Annonces** :
   - Créez une nouvelle annonce en remplissant le formulaire dédié.

4. **Section Réviseur** :
   - Les administrateurs peuvent approuver ou rejeter les annonces soumises par les utilisateurs.

---

## Fonctionnalités pour les Développeurs

- **Gestion CRUD** : Ajoutez, modifiez ou supprimez facilement des annonces, utilisateurs et catégories.
- **Intégration avec Google AI Vision** : Analysez les images des annonces pour garantir leur conformité et leur qualité.
- **Système Multilingue** : Tous les textes sont traduits pour prendre en charge plusieurs langues.

---

Merci d'avoir choisi **Presto Shop** ! Si vous avez des questions ou des suggestions, n'hésitez pas à me contacter.

