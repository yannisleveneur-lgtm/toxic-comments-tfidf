# Dataset attendu

Le notebook attend un fichier `offensive_comments.csv` dans ce dossier.

Colonnes minimales :

- `text` : contenu du commentaire ;
- `toxicity` : score numérique compris entre 0 et 1.

La cible binaire vaut 1 lorsque `toxicity >= 0.5`. Le fichier original n'est pas
versionné afin d'éviter de publier un dataset volumineux sans sa licence et sa
source exactes.

