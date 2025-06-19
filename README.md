# 🧰 Usine à projets – Automatisation GitHub + Latenode + ChatGPT

Ce dépôt permet de générer automatiquement du code HTML / JS / CSS depuis un fichier `instructions.md` en utilisant Latenode et ChatGPT.

## ⚙️ Fonctionnement

1. Tu remplis `instructions.md` (un ou plusieurs fichiers à générer)
2. Tu déclenches le scénario Latenode
3. ChatGPT interprète les instructions
4. Les fichiers sont créés/écrasés dans le dépôt, avec commit automatique
5. Un test automatique est lancé
6. S’il y a une erreur, un fichier `log-erreur.txt` est généré

## 🚀 Exemple de déclenchement

Tu peux déclencher :
- Manuellement dans Latenode
- Via webhook plus tard (avancé)

## 📁 Structure recommandée

- `instructions.md`
- `.latenode.json`
- `.github/workflows/full-check.yml`
- `README.md`
