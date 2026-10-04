# BARO Québec V3.1

## Ce que cette version ajoute
- architecture en couches : officiel / enrichi / à confirmer
- fiche détaillée plus riche
- recherche par NEQ et titulaire
- filtre d'ancienneté prêt pour les données historiques
- catégories éditoriales prêtes pour l'enrichissement
- programmation hebdomadaire prête
- carte prête pour les coordonnées GPS
- synchronisation RACJ automatisée par GitHub Actions
- transparence des sources

## Installation
1. Créer un dépôt GitHub.
2. Copier tout le contenu du dossier dans le dépôt.
3. Settings → Pages → Source: GitHub Actions.
4. Lancer l'action **BARO — synchronisation et publication**.
5. Le site sera publié par GitHub Pages.

## Sources
Le registre RACJ / Données Québec est la base officielle : permis de bar, restaurant, centre de vinification et brassage, épicerie, vendeur de cidre et permis accessoires. La ressource est disponible en CSV/JSON/Excel et sous licence CC-BY 4.0.

Le Registre des entreprises du Québec peut compléter une fiche à partir du NEQ, notamment pour les noms utilisés, adresses d'établissements, dirigeants/administrateurs et bénéficiaires ultimes. Cette information doit être traitée séparément et ne doit pas être assimilée automatiquement au propriétaire de l'établissement.

## Enrichissement
Les champs `foundedYear`, `events`, `website`, `phone`, `editorialTypes` et les coordonnées GPS sont volontairement vides dans la base officielle. Ils sont prêts à recevoir une couche d'enrichissement vérifiée.
