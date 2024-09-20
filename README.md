# Télédétection

> Site de Marc Lang : https://mlang.frama.io/cours-marc-lang/

## Utiliser l'invite de commandes

- `C:\>` **`dir`** *afficher les répertoires du dossier courant*
- `C:\>` **`cd [repertoire_cible]`** *se déplacer vers le répertoire cible*
- `C:\repertoire_cible>` **`cd [chemin\vers\le\repertoire\cible]`** *se déplacer vers le répertoire cible se situant à plusieurs répertoires du répertoire courant*
- `C:\repertoire_cible\chemin\vers\le\repertoire\cible>` **`cd..`** *revenir au répertoire précédent*
- `C:\repertoire_cible\chemin\vers\le\repertoire>` **`D:`** *changer de disque*
- `D:\>`

## Activer OTB

`C:\>` **`cd OTB-9.0.0-Win64`**

`C:\OTB-9.0.0-Win64>` **`otbenv.bat`**
 

## Composition colorée vraies couleurs

|**Canal**|**Domaine spectral**|
|-----------|------------------|
|Rouge|Rouge|
|Vert|Vert|
|Bleu|Bleu|

## Composition colorées IRC fausses couleurs
Cette composition est utilisée pour mettre en avant la végétation

|**Canal**|**Domaine spectral**|
|-----------|------------------|
|Rouge|Infra-Rouge|
|Vert|Rouge|
|Bleu|Vert|




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
