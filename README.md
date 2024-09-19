# Télédétection

## Utiliser l'invite de commandes

- `> dir` : afficher les répertoires du dossier courant
- `> cd [Repertoire cible]` : se déplacer vers le répertoire cible
- `> cd [chemin\vers\le\repertoire\cible]` : se déplacer vers le répertoire cible se situant à plusieurs répertoires du répertoire courant
- `> cd..` : revenir au répertoire précédent
- `> D:` : changer de disque
 

## Règles d'interprétation des bandes spectrales (réflectance)

| **Type de surface**           | **Bleu**     | **Vert**    | **Rouge**   | **Infrarouge proche (NIR)** |
|-------------------------------|--------------|-------------|-------------|-----------------------------|
| **Eau**                       | Modéré       | Modéré      | Faible      | Très faible                 |
| **Végétation saine**           | Faible       | Modéré      | Faible      | Très élevé                  |
| **Sol nu / surfaces urbaines** | Modéré à élevé | Modéré à élevé | Modéré à élevé | Modéré                     |
| **Neige / Glace**              | Très élevé   | Très élevé  | Élevé       | Modéré à élevé              |
| **Nuages**                     | Très élevé   | Très élevé  | Élevé       | Modéré à élevé              |
| **Végétation sèche**           | Faible à modéré | Faible à modéré | Modéré à élevé | Modéré à faible         |


### Longeurs d'ondes
Bleu : ~450-495 nm
Vert : ~495-570 nm
Rouge : ~620-750 nm
Infrarouge proche (NIR) : ~700-1100 nm

### Réflectance
Faible réflectance : La surface absorbe beaucoup de lumière dans cette bande et en reflète peu.
Modéré : La surface reflète une quantité moyenne de lumière.
Élevé : La surface réfléchit une grande quantité de lumière.
