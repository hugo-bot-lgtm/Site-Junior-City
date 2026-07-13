# Site Junior City — Maquette

Maquette de refonte du site [juniorcity.fr](https://juniorcity.fr/), institut d'études quantitatives et qualitatives spécialisé sur la cible enfants & familles.

## 🚀 Voir la maquette

Ouvrir `index.html` dans un navigateur — aucun build ni serveur nécessaire, chaque page est autonome (HTML + CSS + JS intégrés).

## 📄 Pages

| Fichier | Contenu |
|---|---|
| `index.html` | Accueil — hero avec smiley interactif, mission, offre, actus |
| `offre.html` | Méthodologies quali & quanti, livrables |
| `clients.html` | Secteurs d'expertise, emplacements logos clients |
| `equipe.html` | Équipe (avatars et noms en placeholder) |
| `actualite.html` | Articles avec filtres par catégorie |
| `paneliste.html` | Recrutement panel parents — étapes, FAQ, formulaire (démo) |
| `contact.html` | Formulaire de contact (démo), coordonnées |

## 🎨 Personnalisation

Les couleurs sont centralisées dans les variables `:root` en haut de chaque fichier :

```css
:root{
  --sun:   #FFC933;  /* jaune smiley */
  --sky:   #1E78D2;  /* bleu */
  --coral: #F4573B;
  --leaf:  #59B94C;
  ...
}
```

Palette et polices (Baloo 2 / Nunito Sans, via Google Fonts) inspirées de l'identité actuelle de Junior City — à ajuster avec les codes exacts de la future charte graphique.

## ⚠️ Notes

- Les formulaires sont factices (aucune donnée envoyée).
- Les noms de l'équipe et les logos clients sont des placeholders à remplacer.
- Maquette de démonstration, sans brief ni charte — libre d'évoluer !
