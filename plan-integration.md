# Plan d’intégration HTML / CSS

## 1. Présentation du projet

- **Nom du projet :** Booki  
- **Objectif :** Créer une page web responsive en HTML/CSS à partir d’une maquette Figma.  
- **Technologies utilisées :**
  - HTML5
  - CSS3 


## 2. Structure du projet

/Projet 2
├── index.html
├── css/
│    └── style.css
├── images/
│    └── activites
│    └── hebergements
│    └── logo
├── README.md


## 3. Découpage de la page

1. **Header (navbar)**
    - logo Booki
    - Menu (Hébergements, Activités)
2. **Section recherche (research section)**
    - Titre
    - Champ de recherche (form)
    - Filtres
    - Champ information
3. **Section hébergements**
    - Titre
    - Cards (cliquables)
    - Titre
4. **Section populaires**
    - Titre + icon
    - Cards (cliquables)
5. **Section activités**
    - Titre
    - Cards (cliquables)
6. **Footer**
    - Section "A propos"
    - Section "Nos hébergements"
    - Section "Assistance"

## 4. Intégration HTML

    - Balises sémantiques: <header>, <nav>, <h1>, <h2>, <h3>, <main>, <section>, <article> et <footer>
    - Champ de saisie englobé dans un <form> pour la section recherche
    - Liens pour le menu de la nav-bar et les cards
    - Images et icônes


## 5. Intégration CSS

    - Couleurs: **bleu (#0065FC)**, **bleu clair (#DEEBFF)** et **gris pour le fond (#F2F2F2)**.
    - Police (google fonts) : Raleway
    - Icones sur Font Awesome
    - Mise en page: Flexbox
    - Hover pour les filtres et le menu
    - Media Queries pour responsive design (maquettes desktop, tablette et mobile)
    - Breakpoints:  1024 px et 768 px :
        - >1024 px pour les écrans d’ordinateurs ;
        - >=768 px pour les tablettes ;
        - et tout ce qui est en dessous de 768 pour les téléphones portables.
    - Largeur min - max: 320px - 1440px
    

## 6. Tests et validation

    - Contrôle de la validation par W3C
    - Tester la compatibilité avec Google Chrome et Mozilla Firefox
    - Vérifier l'affiche sur desktop, tablette et mobile


## 7. Livrable
    - Fichier TXT ou PDF contenant le lien vers le projet du code sur GitHub
    - Dans le repo doivent être présents:
        - Un fichier index.html
        - Un dossier CSS comprenant un ou plusieurs fichiers style.css
        - Un dossier images contenant l'ensemble des images utilisées
        - Déposer le livrable sur la plateforme OC 48h avant la soutenance