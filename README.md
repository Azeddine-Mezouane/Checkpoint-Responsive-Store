# Documentation du site Oaken

## 1. Aperçu général

Le site "Oaken" est une landing page moderne et élégante conçue pour promouvoir une gamme de produits artisanaux en bois haut de gamme. Elle inclut les sections suivantes :

* Navigation principale
* Section Hero
* Section Produits
* Formulaire de contact
* Pied de page

Elle est construite avec :

* **HTML5 / CSS3**
* **Tailwind CSS (via CDN)**
* **Fonts personnalisées**

---

## 2. Structure des fichiers

### Fichiers principaux :

* `index.html` : Page principale contenant la structure du site.
* `style.css` : Feuille de style custom complétant Tailwind.
* `Assets/` : Contient les images, polices et icônes du projet.

---

## 3. Choix de conception du site

### Conception visuelle

#### Palette de couleurs

La palette est dominée par des tons naturels et chauds :

* Beige clair (`#F2E1D2`, `#E5C6AA`) : fond principal, cartes produits.
* Brun foncé (`#584129`) : textes et titres.
* Doré clair (`#D3A57D`, `#C68C5A`) : boutons, accents.

Ces choix évoquent une ambiance haut de gamme, artisanale et chaleureuse, en cohérence avec l'identité "bois + luxe fonctionnel".

#### Typographie

Deux polices principales :

* **Magica** (police personnalisée) : pour le mot "Oaken" et les titres. Donne une identité forte et mémorable.
* **Poppins** : pour les textes descriptifs et fonctionnels. Moderne, lisible, minimaliste.

#### Images

Les visuels produits (OakLift, OakDock...) sont intégrés dans des cartes avec un fond neutre et élégant. Ils mettent en valeur :

* La texture du bois
* Le détail artisanal
* L'utilité des produits dans un contexte moderne (supports PC, montres, etc.)

---

## 4. Détails techniques

### Navigation

* Barre de navigation responsive (cachée sur mobile, menu icône visible).

### Hero

* Image de fond pleine largeur
* Texte superposé : slogan + marque "Oaken"

### Section produits

* Cartes produits disposées horizontalement (wrap responsive)
* Chacune contient : visuel produit, nom, description, prix, bouton
* Positionnement via `relative/absolute` pour superposition image et carte

### Contact

* Formulaire stylisé avec focus sur l'accessibilité et la lisibilité
* Bouton illustré (svg) pour l'envoi

### Footer

* Footer minimaliste, centré, rappel identitaire

---



## 5. Fonts utilisées

* Magica (via `Assets/font/Magica.otf`)
* Poppins (Google Fonts)

---

## 6. Technologies

* **Tailwind CSS** : via CDN + config personnalisée (dark mode, fonts)
* **Boxicons** : pour les icônes (via CDN)
* **Google Fonts** : Poppins
* **HTML/CSS pur** (sans framework JS pour l'instant)

---

## 7. Responsivité

Le site est entièrement responsive :

* `max-md:` pour réduire la taille des éléments sur petits écrans
* Adaptation des polices, espacements et layout produit

---

Fin de la documentation.
