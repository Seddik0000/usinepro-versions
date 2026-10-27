# UsinePro — versions publiées

Ce dépôt sert uniquement à distribuer les mises à jour d'UsinePro.

- Chaque version est une **Release** contenant l'installateur (`UsinePro-x.y.z-installation.exe`) et le catalogue `serveur.json`.
- Le catalogue est **signé** (Ed25519) : le serveur installé à l'usine refuse toute version dont la signature ou l'empreinte ne correspond pas.
- Le serveur de l'usine consulte chaque jour `releases/latest/download/serveur.json` et propose la mise à jour à l'administrateur.

Aucun code source ni aucune donnée d'entreprise ne se trouve ici.
