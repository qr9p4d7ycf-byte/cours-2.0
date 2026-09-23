# Révis GEII

Application web de révision pour le BUT GEII : matières organisées par semestre (onglet « Gérer »), cours, fiches avec formules (LaTeX), cartes de révision, QCM, exercices extraits ou générés, et estimation du temps de travail restant.

Tout tourne dans le navigateur (un seul fichier `index.html`, aucun serveur). L'IA passe par ta propre clé API [Groq](https://console.groq.com/keys) (gratuite).

## Utiliser

**En local** : ouvre `index.html` dans Chrome, Firefox ou Edge.

**En ligne avec GitHub Pages** :
1. Crée un dépôt GitHub et envoie-y ces fichiers.
2. Va dans *Settings → Pages*.
3. Sous *Build and deployment*, choisis *Deploy from a branch*, la branche `main` et le dossier `/ (root)`, puis *Save*.
4. Au bout d'une minute, le site est disponible sur `https://TON-PSEUDO.github.io/NOM-DU-DEPOT/`.

## Première utilisation

1. Ouvre l'onglet **Réglages** et colle ta clé Groq.
2. Ouvre une matière, colle ton cours dans **Cours**.
3. Génère fiches, cartes, QCM et exercices.

## Vie privée

- Tes cours et résultats sont enregistrés dans le navigateur (`localStorage`), jamais dans le dépôt.
- La clé API reste dans ton navigateur et n'est envoyée qu'à Groq. Ne l'écris jamais dans le code.
- Utilise *Réglages → Exporter une sauvegarde* pour ne rien perdre (la sauvegarde ne contient pas la clé).
