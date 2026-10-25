FINDIT AI - paquet de déploiement Netlify

Contenu :
- index.html : interface mise à jour
- netlify/functions/search.mjs : fonction serveur qui appelle l'API OpenAI sans exposer la clé au navigateur

IMPORTANT : la variable OPENAI_API_KEY doit être définie dans le contexte Production de Netlify.
Ensuite, déployer ce dossier comme un nouveau déploiement manuel Netlify (publier le contenu du dossier, pas le dossier parent lui-même, si l'interface le demande).

Cette version utilise l'API OpenAI payante à l'usage. Vérifiez la facturation et les limites avant les tests. La clé reste côté serveur.
