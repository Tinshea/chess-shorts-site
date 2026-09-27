# Chess Shorts Publisher — site

Pages publiques exigées par TikTok for Developers pour l'application qui
publie les vidéos de [chess-shorts-renderer](https://github.com/Tinshea/chess-shorts-renderer) :

| Page | Rôle |
|---|---|
| `index.html` | Présentation, bouton « Connect TikTok account » |
| `terms.html` | Conditions d'utilisation (champ obligatoire) |
| `privacy.html` | Politique de confidentialité (champ obligatoire) |
| `callback.html` | Adresse de retour OAuth : transmet `code` et `state` au serveur de la maison |
| `icon.png` | Icône 1024×1024, cavalier dessiné par le moteur du projet |

Aucun secret ici : la clé secrète de l'application ne quitte jamais le serveur.
