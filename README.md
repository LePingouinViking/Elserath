
# La Sainte Pioche — Forum & Taverne (Netlify)

Ce package ajoute :
- `/forum.html` avec **Giscus** (forum intégré) prérempli pour `LePingouinViking/elserath` et **Widget Discord**
- Navigation mise à jour
- Pages Chapitre I–IV prêtes pour les textes canons

## Déployer
1) Dézippez ce dossier
2) Glissez le **dossier** dans https://app.netlify.com/drop

## Giscus (Forum intégré)
- Créez le repo GitHub public `LePingouinViking/elserath`, activez **Discussions**, créez la catégorie `RP`
- Sur https://giscus.app, récupérez `repo-id` et `category-id`
- Dans `/forum.html`, remplacez `REPO_ID_A_METTRE` et `CAT_ID_A_METTRE`

## Discord (Taverne)
- Dans Discord : Paramètres serveur → **Widget** → Activer → Copiez l’ID du serveur
- Remplacez `TON_SERVER_ID` dans l’iframe de `/forum.html`
