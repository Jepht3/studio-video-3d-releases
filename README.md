# Studio Vidéo 3D — installateurs

Ce dépôt public contient **uniquement les installateurs Windows et les fichiers de mise à jour automatique** de Studio Vidéo 3D. Le code source n'est pas publié.

**Studio Vidéo 3D** crée des vidéos 3D explicatives verticales (30 secondes ou 1 minute) à partir d'un simple sujet : script, animation, voix off et sous-titres.

- Présentation et abonnement : https://lewebmax.com/studio-video-3d/
- Espace client (clé de licence, factures) : https://my.lewebmax.com/clientarea.php
- Télécharger : onglet **Releases**, version marquée « Latest », fichier `Studio-Video-3D-…-Windows.exe`

## À savoir

- **Licence payante** : le studio s'active avec une clé de licence (abonnement mensuel). Sans clé, il ne démarre pas.
- **Mises à jour automatiques** : le studio vérifie ce dépôt, télécharge les nouvelles versions et vous propose de redémarrer pour les installer. Vos vidéos et vos réglages sont conservés.
- **Windows 10 ou 11 (64 bits)**. L'installateur n'est pas encore signé numériquement : Windows peut afficher « Windows a protégé votre ordinateur ». Cliquez sur *Informations complémentaires*, puis *Exécuter quand même*.
- **Comptes à connecter** : un abonnement Claude (ou un compte ChatGPT avec Codex), et un compte ElevenLabs pour la voix off (facultatif). Ils se paient séparément auprès de leurs éditeurs.

## Composants tiers

- **MinGit** (Git pour Windows, licence GPL v2) est inclus pour le fonctionnement de Claude Code : https://github.com/git-for-windows/git
- **Claude Code** (Anthropic) et **Codex** (OpenAI) ne sont pas inclus : le studio les télécharge au premier besoin depuis le registre officiel npm.

## Aide

https://lewebmax.com/contact/
