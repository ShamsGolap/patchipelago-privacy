# Patchipelago — site de confidentialité

Site statique officiel GolApp Studio, sans CDN, publicité, cookies analytiques ni formulaire transmettant des données.

La politique existe en six langues (FR/EN/ES/PT/IT/DE), décrit séparément Preview et Production et peut être consultée sans JavaScript. Contact : golappstudio.support@gmail.com.

## Publication GitHub Pages

Le code est présent à la fois sur `main` et sur la branche **`gh-pages`**.

**Action de configuration nécessaire, une seule fois par dépôt :**

1. Ouvrir `https://github.com/ShamsGolap/patchipelago-privacy/settings/pages` avec le compte propriétaire.
2. Dans **Build and deployment**, sélectionner **Deploy from a branch**.
3. Choisir **gh-pages** et **/(root)**, puis **Save**.
4. Attendre que GitHub termine le déploiement puis visiter `https://shamsgolap.github.io/patchipelago-privacy/`.

La connexion GitHub utilisée pour produire les fichiers n'expose pas la commande d'activation GitHub Pages. La présence d'une branche `gh-pages` ne garantit donc **pas** à elle seule que le site soit accessible.

## Maintenance

Les fichiers publics résident à la racine. Pas de framework ni étape de compilation. Pour une modification, faire évoluer `main` puis mettre `gh-pages` sur la même révision. Éviter les GitHub Actions non nécessaires.

© 2026 GolApp Studio.
