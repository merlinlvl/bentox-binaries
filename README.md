# Binaires de BentoX

Copies, à l'identique, des binaires que BentoX télécharge (`catalog/binaries/*.toml`) : leurs
sources d'origine purgent les anciennes versions, ces copies gardent une adresse stable. Chaque
recette vérifie l'empreinte sha256 de l'archive avant de l'installer.

## ffmpeg

Builds statiques GPL de [BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds), non
modifiés. FFmpeg est distribué sous licence GPL-3.0-or-later (fichier `LICENSE.txt` de chaque
archive) ; les bibliothèques intégrées ont leurs propres licences, listées par BtbN.

Chaque publication contient aussi le **code source correspondant** : celui de FFmpeg à la révision
exacte du build (`*-source.tar.gz`), et les scripts de construction de BtbN à la même date
(`FFmpeg-Builds-*.tar.gz`), qui désignent les versions des bibliothèques intégrées.
