# Description de Projet: Projet Compile 02 USTHB M1 IL

> Le but de ce projet est de créer un mini-compilateur en passant par les différentes phases de compilation à savoir l'analyse lexicale en utilisant l'outil
FLEX et l'analyse syntaxico-sémantique en utilisant l'outil BISON, du langage « Lang».La structure et les détails de projet sont disponibles dans l'énoncé.

##  Outils et environnement de développement 
<div align="center">
       <b> Flex </b>
    -- <b> Bison </b>
    -- <b> Langage C </b>
    -- <b> CMD ou un éditeur de code (VS code .. ) </b>
</div>

## Comment faire marcher ( éxécuter ) le programme
Après avoir installé tous les outils nécessaires, pour éxécuter le programme on procède par ces étapes : 
- Cliquez sur le bouton Démarrer de Windows. Dans la zone de recherche, saisissez cmd 
- Se positionner sur le dossier où il y'a les fichiers et taper ces commandes 
  - `flex PartieLex.l`
  - `bison -d PartieSyntax.y`
  - `gcc lex.yy.c PartieSyntax.tab.c  -lfl -ly -o test`
  - `test  < MonExemple.txt` 
- Sinon au lieu de taper toutes ces commandes, on peut directement saisir  
  - `comande.bat` , l'éxécution se lance et le résultat s'affichera par la suite

## Routines définies dans la partie sémantique 
- Double déclaration
- Variables non déclarées 
- Dépassement de la taille de tableau
- Changement interdit de valeur d'une constante
- Division par 0
- Incompatibilité de type
- La taille de tableau > 0
- Nombre de signes de formatages 
- Les routines de quads ( IF,WHILE,DO WHILE)
- .......................


<table align="center">
  <tr>
    <th>
    📝 On peut rajouter les parties qui manquent dans ce projet : Optimisation de code et Génération de code objet ( selon la syntaxe de l’assembleur 8086 )
    </th>
  </tr>
</table>
