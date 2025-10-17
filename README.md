
# 🧠 Projet : Créez la page d’accueil du site **Booki**

## 🎯 Objectif du projet

Vous débutez votre alternance en tant que **développeur web** au sein de la start-up **Booki**.
L’entreprise souhaite développer un site qui permette aux usagers de **trouver des hébergements et des activités** dans la ville de leur choix.

Votre mission : **intégrer l’interface du site** à partir de maquettes, en utilisant uniquement **HTML et CSS**.

Vous travaillerez à partir :

* des **maquettes** (desktop, tablette et mobile) ;
* d’une **note de synthèse** précisant les contraintes techniques ;
* d’une **base de code** contenant une structure de départ.

---

## 📂 Structure du projet fournie

* `index.html` : squelette de base à compléter ;
* `css/` : dossier contenant un ou plusieurs fichiers CSS à enrichir ;
* `images/` : dossier avec les images à utiliser.

Conservez **cette structure de fichiers** pour toute la durée du projet.
Versionnez votre code avec **Git** dès le début du développement et hébergez le projet sur **GitHub** (repository public).

---

## ⚙️ Étape 1 — Préparer l’environnement de développement

### ✅ Objectifs

* Installer votre éditeur de code (VS Code recommandé).
* Cloner ou créer le projet Booki sur votre machine.
* Initialiser le dépôt Git et le publier sur GitHub.
* Vérifier que le site s’affiche dès le départ avec le code fourni.

### 🧩 Conseils

* Conservez bien les balises `<link>` d’import des polices et icônes déjà présentes dans le HTML.
* Si le CSS ne s’applique pas, vérifiez que le lien vers le fichier CSS est correct.
* Utilisez les outils de développement (Inspecteur, Console, etc.) pour debugger.

---

## ✂️ Étape 2 — Découper la maquette

### ✅ Objectif

Analyser les maquettes pour identifier les zones principales et planifier le HTML.

### 🔍 Questions à se poser

* Quels sont les éléments visibles sur la maquette ? (logo, navigation, formulaire, cartes, filtres, etc.)
* Comment sont regroupés ces éléments ?
* Quelle balise HTML correspond à chaque composant ?
* Les éléments doivent-ils être positionnés horizontalement (ex. filtres) ou verticalement (ex. liste d’hébergements) ?

L’objectif est d’obtenir un **plan clair** du futur code HTML avant de commencer l’intégration.

---

## 🧱 Étape 3 — Intégrer le header

### ✅ Objectif

Intégrer l’en-tête du site à partir de la maquette desktop :

* logo à gauche ;
* navigation à droite (liens Hébergements / Activités).

### 💡 Conseils

* Utilisez **Flexbox** ou **Grid** pour le positionnement.
* Ajoutez une **bordure bleue** sur le lien actif (au survol ou selon la maquette).
* Faites attention à l’ordre du code HTML et aux marges/paddings.

### ⚠️ Points de vigilance

* En desktop, la bordure bleue est en haut ; en mobile, elle passe en bas.
* Privilégiez les **pixels** pour marges et paddings (plus stables entre formats d’écran).

---

## 🔎 Étape 4 — Ajouter le formulaire de recherche

### ✅ Objectif

Intégrer le formulaire de recherche de la page d’accueil.

### 💡 Conseils

* Reprenez la structure HTML du formulaire selon la maquette.
* Assurez-vous que le champ de saisie et le bouton s’affichent correctement.
* Utilisez des balises accessibles (`label`, `placeholder`, `aria-label`).

---

## 🧭 Étape 5 — Intégrer les filtres

### ✅ Objectif

Créer la barre de filtres présente sous la recherche.

### 💡 Conseils

* Utilisez **Flexbox** pour aligner les filtres horizontalement.
* Les boutons doivent changer de **couleur de fond au survol**.
* Utilisez des marges cohérentes entre les boutons.

### ⚠️ Points de vigilance

* Préférez les **pixels** aux pourcentages pour les espacements.
* Gardez une structure claire et réutilisable : chaque filtre doit pouvoir être dupliqué facilement.

---

## 🏠 Étape 6 — Créer une carte “Hébergement”

### ✅ Objectif

Réaliser une première **card d’hébergement** conforme à la maquette.

### 💡 Conseils

* Les cartes “hébergements” et “les plus populaires” ont une structure similaire.
* Définissez des largeurs en **%** et des hauteurs fixes en **px**.
* Pour les images, utilisez `object-fit: cover` pour éviter la déformation.
* Intégrez toujours les images via le HTML avec des attributs `alt` descriptifs.

### ⚠️ Points de vigilance

* Vérifiez la présence de bordures arrondies et d’ombres sur les cartes.
* Ne dupliquez pas de styles inutiles.

---

## 🏙️ Étape 7 — Mettre en page la section “Hébergements à Marseille”

### ✅ Objectif

Afficher les **6 cartes hébergements** et la colonne **“Les plus populaires”**.

### 💡 Conseils

* Dupliquez la carte réalisée à l’étape 6.
* Utilisez **Flexbox** pour organiser la grille.
* Remplissez chaque carte avec les contenus exacts des maquettes.
* N’oubliez pas le **titre**, l’icône, et le lien “Afficher plus”.

### ⚠️ Points de vigilance

* En responsive, l’ordre d’affichage change entre desktop, tablette et mobile.
* Conservez la sémantique HTML correcte (`section`, `article`, etc.).

---

## 🌆 Étape 8 — Intégrer la section “Activités à Marseille”

### ✅ Objectif

Créer la section présentant les **activités**.

### 💡 Conseils

* Présentez les activités sous forme de **cartes verticales** ou en **grille** selon la maquette.
* La hauteur des images doit être uniforme.
* Utilisez à nouveau `object-fit: cover`.
* Intégrez chaque image en HTML avec un `alt` cohérent.

---

## 🧩 Étape 9 — Créer le footer

### ✅ Objectif

Mettre en place le pied de page en **3 colonnes** égales.

### 💡 Conseils

* Utilisez Flexbox pour l’organisation.
* Si vous utilisez des listes (`ul`), pensez à supprimer le `padding-left` par défaut.
* Respectez l’ordre des éléments et la hiérarchie des titres.

---

## 📱 Étape 10 — Mettre en place le responsive design

### ✅ Objectif

Adapter le site aux **tablettes et mobiles**.

### 💡 Conseils

* Utilisez les **media queries** :

  * `max-width: 1024px` → affichage tablette
  * `max-width: 768px` → affichage mobile
* Conservez la meta `<viewport>` dans le HTML.
* Fixez une largeur maximum à `1440px` et une largeur minimum à `320px`.
* Les couleurs de fond de certaines sections changent entre les versions.

---

## ✅ Étape 11 — Vérifier la qualité du code

### 💡 Contrôles à effectuer

* Validez le HTML et le CSS via les **validateurs W3C**.
* Vérifiez la **lisibilité du code** et la **cohérence du nommage** (kebab-case).
* Assurez-vous que les balises HTML sont correctement imbriquées.
* Vérifiez les **contrastes de couleurs** et la **navigation clavier**.

### 💬 Conseils de finition

* Corrigez les erreurs signalées par les validateurs.
* Supprimez les commentaires ou styles inutilisés.
* Votre projet doit être **fonctionnel et responsive** sur tous les écrans.

---

## 🏁 Résultat final attendu

À la fin du projet, vous devez livrer :

1. Un **site web complet** conforme aux maquettes (desktop, tablette, mobile).
2. Un **code propre, accessible et responsive**, validé par les outils W3C.
3. Un **dépôt GitHub public** contenant :

   * le dossier complet du site,
   * un fichier `README.md` décrivant votre travail,
   * (facultatif) un rapport d’accessibilité.

