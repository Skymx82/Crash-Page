# Crash Page

Page de redirection et de désindexation pour Vercel. Cette configuration permet de :
- Rediriger automatiquement vers www.appforge-tech.fr
- Désindexer complètement les pages des moteurs de recherche
- Gérer les redirections 301 permanentes
- Bloquer l'indexation via robots.txt

## Configuration

Le projet contient :
- `vercel.json` : Configuration Vercel avec redirections et en-têtes
- `404.html` : Page de redirection personnalisée
- `_redirects` : Règles de redirection Vercel/Netlify
- `robots.txt` : Configuration pour les robots des moteurs de recherche

## Déploiement

1. Importez ce dépôt sur Vercel
2. Aucune configuration supplémentaire n'est nécessaire
3. Le site redirigera automatiquement vers www.appforge-tech.fr
