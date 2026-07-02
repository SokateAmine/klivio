# KLIVIO — L'allié de votre progression

Ce projet est une intégration et reproduction fidèle et responsive d'une maquette web pour la plateforme **KLIVIO**, un site moderne d'apprentissage et de formations en ligne dédié au développement personnel.

---

## 🚀 Fonctionnalités intégrées

* **Bannière d'accueil (Hero Section) :** Une introduction immersive avec un dégradé dynamique sur image de fond et un bouton d'appel à l'action.
* **Grilles de Formations (Populaires & Récentes) :** Des listes de formations présentées sous forme de cartes élégantes avec des badges de prix adaptatifs (prix réduit et prix barré) et des notes par étoiles.
* **Menu Burger Responsive :** Un menu de navigation horizontal sur desktop qui se transforme en menu burger interactif (animé en forme de croix au clic) sur tablette et mobile.
* **Section Avantages :** Une présentation structurée des atouts de Klivio avec des icônes sémantiques.
* **Espace Créateurs de Contenu :** Une zone dédiée incitant les formateurs à rejoindre la plateforme.
* **Témoignages Clients :** Une section d'avis clients soignée avec photos de profil arrondies.
* **Formulaire de Contact :** Un formulaire sémantique, sécurisé (validation HTML5) et accessible aux lecteurs d'écran via des attributs d'accessibilité.

---

## 🛠️ Stack Technique

* **HTML5 :** Structure sémantique respectant les normes du W3C (balises `header`, `section`, `footer`, formulaires d'accessibilité).
* **CSS3 :** Mise en page moderne avec Flexbox pour aligner de façon fluide les éléments et les cartes.
* **JavaScript (Vanilla) :** Script léger pour gérer l'interaction responsive du menu burger mobile.
* **Polices & Icônes :**
  * Police **Montserrat** intégrée localement.
  * **Font Awesome** (via CDN kit) pour les icônes de recherche et de notation.

---

## 📁 Structure du Projet

```text
klivio/
├── Assets/
│   ├── Fonts/         # Polices Montserrat (Variable et Statiques)
│   └── Img/           # Logos, icônes et illustrations
├── Index.html         # Structure HTML principale de la page d'accueil
├── style.css          # Styles CSS globaux, composants et requêtes médias (breakpoints)
└── README.md          # Documentation du projet
```

---

## 💻 Comment lancer le projet en local ?

### Option 1 : Lancement direct
Double-cliquez simplement sur le fichier **`Index.html`** pour l'ouvrir directement dans votre navigateur internet préféré.

### Option 2 : Serveur de développement (Recommandé)
Pour tester le site avec un vrai protocole HTTP, lancez un serveur local dans le dossier racine :

* **Avec Python :**
  ```bash
  python3 -m http.server 8000
  ```
  Ouvrez ensuite votre navigateur sur [http://localhost:8000](http://localhost:8000).

* **Avec Node.js / npm :**
  ```bash
  npx serve .
  ```