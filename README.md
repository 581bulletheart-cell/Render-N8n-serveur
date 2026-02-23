# n8n sur Render.com

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)
Déploiement de n8n sur Render.com avec base de données Supabase.

## Comment installer

1. Clique sur le bouton "Deploy to Render" ci-dessous
2. Entre ton mot de passe Supabase quand Render te le demande
3. Une fois déployé, va dans Dashboard > n8n > Environment
4. Copie ton URL et colle-la comme valeur de WEBHOOK_URL
5. Attends une minute que l'instance redémarre
6. Profite !

## Variables d'environnement importantes

- `WEBHOOK_URL` : l'URL publique de ton instance n8n
- `DB_POSTGRESDB_PASSWORD` : ton mot de passe Supabase

## Modèles IA

Ce setup utilise [Groq](https://console.groq.com) comme fournisseur IA (gratuit et rapide).
Crée un compte sur Groq et connecte ta clé API directement dans n8n.
