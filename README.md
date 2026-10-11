# GS Compta — Visionneuse iPhone

Visionneuse de sauvegardes Graphite chiffrées GRC1 et de JSON compatibles.

## Installer sur iPhone

Ouvrir le site publié via **Safari**, puis **Partager → Sur l’écran d’accueil → Ajouter**. Lancer l’application une fois avec Internet pour laisser terminer sa mise en cache. Ensuite, les sauvegardes sont traitées localement, en lecture seule, sans connexion requise tant que le cache iOS est conservé.

## Confidentialité

L’application n’utilise ni compte ni serveur pour traiter les sauvegardes. Le déchiffrement AES-256-GCM est effectué dans le navigateur. Aucune sauvegarde, clé ou information comptable n’est incluse dans ce dépôt. **Ne jamais ajouter de fichiers privés ou clés GRC1 dans GitHub**.

## Limites

La clé GRC1 correspondant à la sauvegarde est nécessaire. L’application n’effectue pas de restauration vers GS Compta. iOS peut supprimer le cache hors ligne après un nettoyage ou un manque d’espace. Le moteur JavaScript autonome n’a pas fait l’objet d’un audit cryptographique indépendant.

## Publier sur GitHub Pages

Dans les paramètres du dépôt, **Settings → Pages → Build and deployment → Source : Deploy from a branch → Branch : main → Folder : /(root) → Save**.

Ouvrir ensuite le site dans Safari et tester l’ajout à l’écran d’accueil et l’ouverture en mode avion.
