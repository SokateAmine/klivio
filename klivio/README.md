# 🎓 KLIVIO - Intégration Web (Reproduction Figma)

Ce projet est une intégration **"pixel-perfect"** (reproduction fidèle) d'une maquette Figma pour la plateforme d'apprentissage en ligne **KLIVIO**, spécialisée dans le développement personnel.

Le projet est divisé en deux approches d'intégration pour démontrer différentes techniques de développement :

1. **Version CSS Classique (Vanilla CSS) :** Située à la racine, elle propose une structure sémantique propre et du style vanilla optimisé et entièrement responsive.
2. **Version Tailwind CSS :** Située dans le dossier `KlivioTailwinds/`, elle utilise une approche Utility-First moderne.

---

## 🚀 Fonctionnalités et Sections intégrées

* **En-tête (Header) :** Barre de navigation avec barre de recherche, liens d'authentification et menu burger responsive interactif (animé en forme de croix).
* **Bannière (Hero Section) :** Accroche principale avec CTA et gestion des dégradés complexes.
* **Catalogue de Formations :** Grilles de cartes (Cards) adaptatives pour les formations "Populaires" et "Récentes", avec positionnement dynamique des badges de prix.
* **Avantages & Création :** Présentation structurée des atouts élèves/formateurs avec des icônes sémantiques.
* **Témoignages Clients :** Section d'avis clients soignée.
* **Contact :** Formulaire de contact moderne, validé en HTML5, accessible (attributs `aria` et labels pour lecteurs d'écran).
* **Pied de page (Footer) :** Liens utiles, coordonnées, réseaux sociaux et mentions légales.

---

## 🛠️ Stack Technique

### Version Classique (Vanilla)
* **HTML5** sémantique.
* **CSS3** moderne (Flexbox, variables, transitions).
* **Vanilla JavaScript** pour la gestion de la responsivité du menu burger.

### Version Tailwind
* **HTML5** sémantique.
* **Tailwind CSS** (mise en page Grid/Flexbox, responsive natif, configuration de thème).
* **FontAwesome** pour les icônes.

---

## 📁 Structure du Projet

```text
klivio/
├── Assets/              # Images, polices (Montserrat) et logos
├── Index.html           # Page d'accueil (Version CSS Classique)
├── style.css            # Styles de la version CSS Classique
├── KlivioTailwinds/     # Version du projet utilisant Tailwind CSS
├── Readme.mk            # Documentation alternative
└── README.md            # Documentation principale (ce fichier)
```

---

## 💻 Comment lancer le projet en local ?

### Lancement direct
Double-cliquez simplement sur le fichier **`Index.html`** pour l'ouvrir dans votre navigateur.

### Serveur de développement (Recommandé)
Pour tester le site sous protocole HTTP, lancez un serveur local dans le dossier racine :

* **Avec Python :**
  ```bash
  python3 -m http.server 8000
  ```
  Accédez ensuite à [http://localhost:8000](http://localhost:8000).

* **Avec Node.js / npm :**
  ```bash
  npx serve .
  ```
