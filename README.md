# 🌍 Projet : Créez la page d’accueil du site **Booki**

## 🔗 Ressource principale

➡️ **Lien vers les maquettes Figma à respecter :**
[https://www.figma.com/design/r9YJyUkpVdrxzBBKGH7reY/Maquettes-Booki--desktop--mobile--tablette-?node-id=3-0](https://www.figma.com/design/r9YJyUkpVdrxzBBKGH7reY/Maquettes-Booki--desktop--mobile--tablette-?node-id=3-0)

---

## 🎯 Objectif du projet

Vous débutez votre alternance en tant que **développeur web** au sein de la start-up **Booki**.
L’entreprise souhaite développer un site Internet qui permette aux usagers de **trouver des hébergements et des activités** dans la ville de leur choix.

Votre mission : **intégrer l’interface du site** à partir des maquettes fournies, en utilisant uniquement **HTML** et **CSS**.

Vous travaillerez à partir :

* des **maquettes** (desktop, tablette et mobile) ;
* d’une **note de synthèse** précisant les contraintes techniques ;
* d’une **base de code** contenant une structure de départ.

---

## 📂 Structure du projet fournie

* `index.html` — squelette HTML à compléter
* `css/` — dossier contenant le ou les fichiers CSS à enrichir
* `images/` — dossier avec les images à utiliser

Conservez **cette structure de fichiers** tout au long du développement.
Versionnez votre code avec **Git** dès le début et hébergez le projet sur **GitHub** (repository public).

---

## ⚙️ Étape 1 — Préparer l’environnement de développement

### ✅ Objectifs

* Installer votre éditeur de code (VS Code recommandé).
* Récupérer la base de code sur votre machine.
* Vérifier que le site s’affiche dès le départ avec le code fourni.

### 🧩 Conseils

* Conservez bien les balises `<link>` d’import de polices et d’icônes déjà présentes dans le HTML.
* Si le CSS ne s’applique pas, vérifiez que le lien vers le fichier est correct.
* Utilisez les **outils de développement** de votre navigateur pour debugger.

---

## ✂️ Étape 2 — Découper la maquette

### ✅ Objectif

Analyser les maquettes pour identifier les zones principales et planifier la structure HTML.

### 🔍 Questions à se poser

* Quels sont les éléments visibles sur la maquette ? (logo, navigation, recherche, filtres, cartes, etc.)
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
* Privilégiez les **pixels** pour marges et paddings.

---

## 🔎 Étape 4 — Ajouter le formulaire de recherche

### ✅ Objectif

Intégrer le formulaire de recherche de la page d’accueil.

### 💡 Conseils

* Respectez la structure HTML indiquée dans la maquette.
* Utilisez des balises accessibles (`label`, `placeholder`, `aria-label`).
* Vérifiez la cohérence du design avec les trois versions (desktop, tablette, mobile).

---

## 🧭 Étape 5 — Intégrer les filtres

### ✅ Objectif

Créer la barre de filtres située sous la recherche.

### 💡 Conseils

* Utilisez **Flexbox** pour aligner les filtres horizontalement.
* Les boutons doivent changer de **couleur de fond au survol**.
* Respectez les espacements et les arrondis visibles sur les maquettes.

### ⚠️ Points de vigilance

* Utilisez les **pixels** pour les espacements (pas de pourcentages).
* Structurez le HTML pour que chaque bouton soit réutilisable.

---

## 🏠 Étape 6 — Créer une carte “Hébergement”

### ✅ Objectif

Réaliser une première **carte d’hébergement** conforme à la maquette.

### 💡 Conseils

* Les cartes “hébergements” et “les plus populaires” ont une structure similaire.
* Définissez les largeurs en **%** et les hauteurs fixes en **px**.
* Utilisez `object-fit: cover` pour ajuster les images.
* Ajoutez un attribut `alt` pertinent à chaque image.

### ⚠️ Points de vigilance

* Vérifiez la présence de bordures arrondies et d’ombres.
* Ne dupliquez pas inutilement le code.

---

## 🏙️ Étape 7 — Mettre en page “Hébergements à Marseille”

### ✅ Objectif

Afficher les **6 cartes d’hébergements** et la section **“Les plus populaires”**.

### 💡 Conseils

* Dupliquez la carte réalisée à l’étape précédente.
* Utilisez **Flexbox** pour organiser la grille.
* Remplissez chaque carte avec le contenu exact des maquettes.
* N’oubliez pas le titre, l’icône et le lien “Afficher plus”.

### ⚠️ Points de vigilance

* L’ordre d’affichage change selon le format d’écran.
* Utilisez des balises sémantiques (`section`, `article`, etc.).

---

## 🌆 Étape 8 — Intégrer “Activités à Marseille”

### ✅ Objectif

Créer la section présentant les **activités** à Marseille.

### 💡 Conseils

* Disposez les cartes verticalement ou en grille selon la version.
* Uniformisez la hauteur des images.
* Utilisez `object-fit: cover`.
* Respectez les espacements et les bordures visibles sur la maquette.

---

## 🧩 Étape 9 — Créer le footer

### ✅ Objectif

Mettre en place le pied de page en **3 colonnes égales**.

### 💡 Conseils

* Utilisez **Flexbox** pour l’organisation.
* Supprimez les marges par défaut des listes (`ul`).
* Respectez la hiérarchie des titres et des liens.

---

## 📱 Étape 10 — Mettre en place le responsive design

### ✅ Objectif

Adapter le site aux **tablettes et mobiles**.

### 💡 Conseils

* Utilisez des **media queries** :

  * `max-width: 1024px` → affichage tablette
  * `max-width: 768px` → affichage mobile
* Conservez la meta `<viewport>` dans le HTML.
* Fixez une largeur max à `1440px` et une min à `320px`.
* Ajustez les couleurs de fond selon la maquette.

---

## ✅ Étape 11 — Vérifier la qualité du code

### 💡 Contrôles à effectuer

* Validez le code avec les validateurs HTML et CSS du W3C.
* Vérifiez la lisibilité et la cohérence du nommage (`.main-wrapper`, `.filter-button`, etc.).
* Testez la navigation au clavier.
* Vérifiez les contrastes de couleur et l’accessibilité.

### 🧹 Conseils de finition

* Corrigez les erreurs critiques signalées.
* Nettoyez le code (pas de styles inutilisés).
* Vérifiez le rendu sur plusieurs navigateurs et tailles d’écran.

---

## 🏁 Résultat final attendu

À la fin du projet, vous devez livrer :

1. Un **site complet et conforme** aux maquettes (desktop, tablette, mobile).
2. Un **code propre, accessible et responsive**, validé par les validateurs W3C.
3. Un **dépôt GitHub public** ou un zip contenant :

   * le code complet du site,
   * un `README.md` expliquant votre travail,
   * un mini rapport d’accessibilité (facultatif).
