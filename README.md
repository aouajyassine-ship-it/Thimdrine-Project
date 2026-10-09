# Thimdrine — Site vitrine d’une coopérative du Rif

## Présentation du projet

Thimdrine est un site vitrine réalisé dans le cadre du Brief 1 à YouCode Nador. Il présente une coopérative de 25 femmes de la région de Nador, spécialisée dans la production de miel de thym, d’huile d’olive et de confiture de figue de barbarie.

Le site permet aux visiteurs de découvrir la coopérative, de consulter ses produits et d’envoyer une demande de commande.

## Objectifs du projet

* Présenter la coopérative Thimdrine et son savoir-faire.
* Mettre en valeur les produits du terroir du Rif.
* Faciliter la navigation entre les différentes pages.
* Permettre aux visiteurs d’envoyer une demande de commande.
* Adapter le site aux ordinateurs et aux téléphones mobiles.

## Pages du site

### 1. Accueil

Présentation de la coopérative, mise en avant des produits phares et appel à l’action vers la page Contact.

### 2. Nos produits

Présentation de six produits sous forme de cartes contenant une image, un nom, une description et un prix.

### 3. À propos

Présentation de l’histoire de la coopérative, de ses valeurs et de son savoir-faire traditionnel.

### 4. Contact

Formulaire de demande de commande comprenant les coordonnées du client, le produit souhaité, la quantité, un message et une case de consentement.

## Technologies utilisées

* **HTML5** : structure des pages et balises sémantiques.
* **CSS3** : mise en forme, couleurs, typographies et responsive design.
* **Flexbox** : organisation des éléments et des cartes.
* **Media queries** : adaptation aux différentes tailles d’écran.
* **Google Fonts** : utilisation des polices Lora et Source Sans 3.

Le projet est réalisé avec HTML et CSS natifs, sans framework ni JavaScript, conformément aux contraintes du brief.

## Charte graphique

### Couleurs

| Couleur   | Code hexadécimal | Utilisation                   |
| --------- | ---------------- | ----------------------------- |
| Vert thym | `#294D36`        | Navigation, boutons et footer |
| Miel      | `#D6A15D`        | Accents et éléments visuels   |
| Figue     | `#6B2D45`        | Bandeau de la page Contact    |
| Lin       | `#F7F3EA`        | Fond général                  |
| Sable     | `#EFE9DE`        | Fonds secondaires             |
| Terre     | `#2B2B2B`        | Texte principal               |

### Typographies

* **Lora** : titres.
* **Source Sans 3** : textes, navigation et formulaires.

## Fonctionnalités

* Navigation commune entre les quatre pages.
* Présentation des produits sous forme de cartes CSS.
* Formulaire de demande de commande.
* Validation native HTML des champs du formulaire.
* Mise en page responsive avec Flexbox et media queries.
* Utilisation d’images avec des attributs `alt` adaptés.

**Remarque :** le formulaire permet la saisie et la validation des informations dans le navigateur. L’envoi réel des commandes nécessite un système de réception adapté.

## Structure du projet

```text
Thimdrine/
├── index.html
├── images/
├── produits/
│   ├── produits.html
│   └── produits.css
├── a-propos/
│   ├── a-propos.html
│   └── a-propos.css
├── contact/
│   ├── contact.html
│   └── contact.css
└── README.md
```

*Remarque : adapter cette structure aux noms réels des fichiers et dossiers du projet.*

## Installation et visualisation

1. Cloner ou télécharger le dépôt GitHub.
2. Ouvrir le dossier du projet dans un éditeur de code.
3. Ouvrir `index.html` dans un navigateur.
4. Naviguer entre les pages grâce au menu principal.

## Vérifications avant la livraison

* [ ] Les quatre pages sont accessibles depuis la navigation.
* [ ] Tous les liens et chemins des images fonctionnent.
* [ ] Chaque image possède un attribut `alt` pertinent.
* [ ] Chaque page possède un seul titre principal `h1`.
* [ ] Le formulaire contient les attributs de validation nécessaires : `required`, `type`, `pattern` si nécessaire et `min` pour la quantité.
* [ ] Le site est lisible sur mobile.
* [ ] Le HTML est vérifié avec le validateur W3C.
* [ ] L’accessibilité de la page d’accueil est vérifiée avec Lighthouse.
* [ ] Les captures d’écran sont ajoutées au README.
* [ ] Le site est déployé sur GitHub Pages.

## Captures d’écran

Ajouter des captures d’écran des quatre pages :

* Accueil
* Nos produits
* À propos
* Contact

## Liens du projet

* **Dépôt GitHub :** À compléter
* **Site déployé sur GitHub Pages :** À compléter
* **Maquette Figma :** À compléter
* **Board Jira / GitHub Projects :** À compléter

## Réalisation

Projet individuel réalisé dans le cadre du Brief 1 à **YouCode Nador**.

© 2026 — Thimdrine
