# Éclaireur — votre projet face à la loi

**Défi du Hackathon 2026 de l'Assemblée nationale** · « Le parcours de la loi : vers une IA de confiance » · 3-4 juillet 2026

## Le défi en une phrase

Un radar législatif citoyen : l'outil confronte un projet innovant aux données
ouvertes du Parlement et de Légifrance — ce que la loi permet déjà, où le
projet percute le droit, comment s'adapter, et quoi remonter au législateur
pour instruire le débat **avant** la crise.

## Démonstration

🔗 **https://avec-moa.com** — parcours complet en 4 étapes :
1. Présenter son projet (dépôt de fichier ou description libre)
2. « Votre projet face à la loi » : fiche sourcée en 4 blocs (ce que le droit
   prévoit · signaux au Parlement · points de friction · s'adapter & proposer)
3. Dossier de présentation au député (note éditable — pas une proposition de
   loi toute faite : c'est le travail du législateur)
4. Transmission au bon interlocuteur (député ou commission) — **aucun envoi
   automatique** : relecture et geste d'envoi humains, toujours.

## Cas d'école

**MOA** (avec-moa.com) — IA conversationnelle supervisée de prévention du
post-partum, classée « à haut risque » par l'AI Act, sans case claire dans le
droit existant : l'exemple type du projet utile freiné faute de cadre. Le
citoyen porteur de projet est un capteur d'anticipation pour le législateur.

## IA de confiance — principes de conception

- Chaque affirmation renvoie à sa source officielle (chaîne de preuve vérifiable).
- Aucune conclusion juridique définitive : l'outil accélère le repérage,
  il ne remplace ni le juriste ni l'administrateur. L'IA éclaire, l'humain décide.
- Aucun envoi automatisé vers les élus : toute transmission passe par la
  relecture et le geste du citoyen.

## Données et outils mobilisés

- **Serveur MCP « an-et-co » / Canutes** (LexImpact) : schémas `assemblee`
  (dossiers, amendements, scrutins, comptes rendus, acteurs), `legifrance`,
  `senat`, `annuaire`, `droits_et_demarches` — https://mcp.hackathon2026.leximpact.dev/mcp
- Open data Assemblée nationale (XVIIe législature) : dossiers législatifs,
  amendements, votes, comptes rendus — data.assemblee-nationale.fr
- Légifrance (textes en vigueur) · dump Tricoteuses/canutes.

## Reproduire

L'application est une page web statique autonome (`app/index.html`) : aucun
backend requis pour la démo ; le branchement API (an-et-co / jeton) se
configure dans la section « Sources de données » de la page, et reste
mémorisé localement dans le navigateur.

## Équipe

Défi porté par Frédéric Lallier (The Flow Fabric) — hackathon AN 2026.
