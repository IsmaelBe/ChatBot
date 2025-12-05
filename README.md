Création d'un chatbot idiot avec page React complète (front-end) branchée sur OpenRouter (API externe) pour l'épreuve de la Nuit de l'Info 2025.


IMPORTANT: Ceci fait partie d'un ensemble de défis avec mon équipe, accessible sur:
https://github.com/MiniPoin/NuitDeL-Info-DefiNational.git

Le but est de faire un chatbot idiot avec des réponses étranges.

- Pré-requis

    Node v22.21.1 + npm 10.9.4
    Clé API OpenRouter (gratuite ou payante) → https://openrouter.ai/keys
    Compte OpenRouter pour suivre les crédits

- Installation

git clone <ce-repo>
cd chatbot
npm install
npm install gsap

Si problème:
(
npm install mime
npm install --legacy-peer-deps)
npm start

npm start        # dev server  http://localhost:3000
npm run build    # build de prod


- Configuration OpenRouter

Ajouter la clé API
Crée un fichier .env à la racine du projet :
.env:

REACT_APP_OPENROUTER_KEY=xxxxxxxxxx
Remplacer xxxxx par la clé

Préfixe obligatoire par REACT_APP_ pour Create-React-App.

Précision:
Peu de token pour avoir un model gratuit, donc 3,4 requêtes possibles par npm start