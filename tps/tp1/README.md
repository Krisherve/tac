# Ajoutez dans ce dossier les notebooks pour le TP1

# TP1 : Web scraping et API

Ce dossier contient les notebooks réalisés pour découvrir le corpus CAMille et interroger une API.

## Notebooks

- `s3_scrape.ipynb` trouve les liens PDF sur le site de CAMille et télécharge les 51 fichiers dans `data/camille`, à la racine du dépôt.
- `s2_api.ipynb` interroge l’API de Wikipédia en français pour obtenir une courte présentation de Bruxelles, un lieu présent dans les textes.

## Résultats

Le notebook de scraping vérifie le nombre de liens trouvés et contrôle que les fichiers téléchargés sont bien des PDF. La requête Wikipédia renvoie un extrait de la page consacrée à Bruxelles.