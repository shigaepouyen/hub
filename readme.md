# Hub de Liens - Template Personnalisable

Un template simple, élégant et 100% personnalisable pour créer votre propre page de liens ("link-in-bio"). Idéal pour regrouper tous vos profils sociaux et projets en un seul endroit. Le tout dans un unique fichier `index.html`, sans aucune dépendance complexe.

![Aperçu du Hub de Liens](https://i.imgur.com/vHq4g5a.png)
> Pensez à remplacer le lien de l'image ci-dessus par une capture d'écran de votre page personnalisée !

---

## ✨ Fonctionnalités

* **Fichier Unique** : Tout le code (HTML, CSS, JS) est dans un seul fichier `index.html`.
* **Personnalisation Facile** : Modifiez simplement un objet JavaScript pour changer votre nom, bio, avatar et tous vos liens.
* **Design Épuré et Moderne** : Une interface sobre et professionnelle qui met en valeur vos liens.
* **Responsive** : S'adapte parfaitement aux écrans d'ordinateurs, de tablettes et de mobiles.
* **Icônes Incluses** : Utilise [Font Awesome](https://fontawesome.com/search?m=free&s=brands) pour ajouter facilement des icônes à vos liens.
* **Léger et Rapide** : Aucune bibliothèque lourde, pour un chargement quasi instantané.

---

## 🚀 Installation et Utilisation

Suivez ces étapes pour mettre en place votre propre page de liens en quelques minutes.

### 1. Récupérer le code

Clonez ce dépôt sur votre machine locale avec la commande suivante :
```bash
git clone [https://github.com/VOTRE_PSEUDO/NOM_DU_DEPOT.git](https://github.com/VOTRE_PSEUDO/NOM_DU_DEPOT.git)
```
(Ou téléchargez simplement le ZIP du projet).

### 2. Personnaliser le contenu

Ouvrez le fichier `index.html` dans un éditeur de code comme **VS Code**. Toute la configuration se trouve dans la balise `<script>` vers la fin du fichier, à l'intérieur de l'objet `config`.

```javascript
const config = {
  profile: {
    name: "Votre Nom ou Pseudo",
    bio: "Une description de vous, votre activité...",
    avatarUrl: "URL_de_votre_photo.jpg" 
  },
  links: [
    {
      title: "Mon Blog",
      url: "[https://mon-site.com](https://mon-site.com)",
      icon: "fa-solid fa-blog"
    },
    // ... ajoutez vos autres liens ici
  ]
};
```

Modifiez les champs `name`, `bio`, `avatarUrl` et la liste de `links` avec vos propres informations.

> **Astuce** : Pour les icônes, rendez-vous sur [Font Awesome](https://fontawesome.com/search?m=free) et cherchez l'icône de votre choix. Copiez ensuite ses classes (ex: `fa-brands fa-linkedin`) dans le champ `icon`.

### 3. Mettre en ligne

Une fois que votre page est personnalisée, vous pouvez l'héberger gratuitement sur plusieurs plateformes :

* **GitHub Pages** : La solution la plus simple si votre code est déjà sur GitHub. Allez dans les paramètres de votre dépôt > Pages > et choisissez de déployer depuis la branche `main`.
* **Netlify** : Glissez-déposez simplement votre fichier `index.html` sur leur site.
* **Vercel** : Très simple d'utilisation, se connecte directement à votre dépôt GitHub.

---

## 📄 Licence

Ce projet est distribué sous la licence MIT. Voir le fichier `LICENSE` pour plus de détails. Cela signifie que vous pouvez l'utiliser, le modifier et le distribuer librement, même pour des projets commerciaux.

> Copyright (c) 2025 Shigaepouyen