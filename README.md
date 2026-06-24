# IFCAR Solutions — Proposition 4

Quatrième proposition de design pour le site vitrine d'IFCAR Solutions.
Site statique (HTML/CSS/JS, sans dépendance ni build) respectant le cahier des charges.

## Direction artistique — « Editorial Corporate »
Un parti pris plus **moderne et premium**, nettement différent des propositions précédentes :

- **Palette** : navy profond (`#0c1320`) + accent **doré** (`#c79a3e`) et bleu IFCAR secondaire.
- **Typographie** : *Fraunces* (serif éditorial) pour les titres + *Inter* pour le texte.
- **Mises en page** : héros sombre avec carte « verre », **grille bento**, bandeau de chiffres
  sur fond foncé, cartes à liseré doré, marquees de logos, timeline, accordéons.
- **Header** sticky en verre dépoli, animations d'apparition au scroll, 100 % responsive.

## Pages (conformes au cahier des charges)
- `index.html` — Accueil : Rubrique 1 (4 métiers), Rubrique 2 (références par secteur),
  Rubrique 3 (contact : formulaire **ou** coordonnées).
- `recrutement.html` · `formation.html` · `conseil.html` · `accompagnement.html` — prestations.
- `a-propos.html` — histoire, mission/vision, valeurs, équipe.
- `contact.html` — formulaire + coordonnées + plan d'accès.

Haut de page (logo + nav + « Un besoin ? Contactez-nous ») et bas de page
(Accueil, À propos, Contact, prestations, Plan d'accès) repris du cahier des charges.

## Aperçu
Ouvrir `index.html` dans un navigateur.

## À compléter avant mise en production
Coordonnées (téléphone, fax, ICE, adresse exacte), liens réseaux sociaux,
vrais logos clients (`assets/img/clients/`), fiche PDF à télécharger, et
branchement du formulaire à un backend / Formspree (actuellement démo côté client).
