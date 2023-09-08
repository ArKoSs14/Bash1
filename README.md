[lien vers le killercoda](https://killercoda.com/emelin)

[lien vers un guide du markdown](https://www.markdownguide.org/cheat_sheet/)

# Bash_2023

## 1.1
- ouvrir un terminal <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>T</kdb>
- Chemin absolu du home de *sasha* : `/home/john`
- `/home/` est un dossier qui contient tous les dossier personnels des utilisateurs
- flèche du haut ou bas pour l'historique des commandes
- flèche droite ou gauche pour corriger dans la ligne

## 1.2
### cd : Change directory
- Pour se déplacer dans l'arborescense on utilise `cd home <nom du fichier>`
- Pour aller en arrière on utilise `cd ..`
- Pour retourner a son home home on utilise `cd`, repéré par le ~

### ls : list
- Pour voir le contenu du fichier actuel on utilise `ls`

## 1.3
- `cat <nom du fichier>` permet de lire le contenu d'un fichier
- <kdb>Tab</kdb> : autocomplétion du début d'une commande

## 1.4
### Chemin absolu
- le chemin absolu est un chemin qui indique l'intégralité du chemin de destination et il commence **Toujours** par `/`, appelé racine
- `ls /<nom du fichier>` : permet d'utiliser ls en prenant le chemin absolu
- `ls ..` : permet de visualiser le dossier parent
- `cat /<nom du fichier>` : permet d'utiliser cat en prenant le chemin absolu

### Chemin relatif
- le chemin relatif est un chemin qui prends pour point de départ l'endroit ou l'on se situe et n'affiche pas l'intégralité du chemin

## 1.5
`/bin/` : répertoire contenant les commandes les plus indispensables
`/usr/bin/` : commandes accessibles par tous les users
`/sbin/` : commandes accessibles par des administrateurs uniquement

### Construction d'une ligne bash
Exemple : `mkdir -v dossier1 dossier2 dossier3`
- `mkdir` est la commande
- `-v` est une option
- `dossier1,2,...` sont des arguments

### Options
- Simple tiret : on utilise qu'une lettre pour regrouper plusieurs options, c'est la version "simplifiée"
- Double tiret : on écrit la commande complète, elle est plus longue mais plus comphrénsible

Exemple :  
-`du -sh /usr/` : Version simple car `-sh`  
-`du --summarize --human-readable /usr/` : Version longue car `--`
