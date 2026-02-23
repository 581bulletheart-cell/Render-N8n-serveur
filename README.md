# n8n sur Render.com

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

## Comment installer

1. Clique sur le bouton "Deploy to Render" ci-dessous
2. Entre ton mot de passe Supabase quand Render te le demande
3. Une fois déployé, va dans Dashboard > n8n > Environment
4. Copie ton URL et colle-la comme valeur de WEBHOOK_URL
5. Attends une minute que l'instance redémarre
6. Profite !

## Variables d'environnement importantes

- `DB_POSTGRESDB_HOST` : ton mot de passe Supabase
- `DB_POSTGRESDB_PORT` : ton mot de passe Supabase
- `DB_POSTGRESDB_USER` : ton mot de passe Supabase
- `DB_POSTGRESDB_PASSWORD` : ton mot de passe Supabase
- `DB_POSTGRESDB_DATABASE` : ton mot de passe Supabase

Une fois installé, ajouter la variable d'environnement 
- `WEBHOOK_URL` : l'URL publique de ton instance n8n

## Modèles IA

Ce setup utilise [Groq](https://console.groq.com) comme fournisseur IA (gratuit et rapide).
Crée un compte sur Groq et connecte ta clé API directement dans n8n.
