# Notes C

## caractère

caractères d'une notation spéciale

|Notation En C | CODE ASCII| ABREVIATION USUELLE|Signfication|
|--------------|-----------|--------------------|------------|
|\a|07|BEL|Cloche ou bip|
|\b|08|BS|Retour arriere|
|\f|0C|FF|saut de page|
|\n|0A|LF|Saut de ligne|
|\r|0D|CR|Retout chariot|
|\t|09|HT|Tablulation hotizontale|
|\v|0B|VT|Tablulation verticale|
|\\||||
|\'||||
|\"||||
|\?||||

## Operateur 


### Opérateurs logiques (`booléens`) en C

| Opérateur | Nom                  | Description                                   |
|-----------|----------------------|-----------------------------------------------|
| `&&`      | ET logique (AND)     | Vrai si les deux opérandes sont vrais         |
| `||`      | OU logique (OR)      | Vrai si au moins un des opérandes est vrai    |
| `!`       | NON logique (NOT)    | Inverse la valeur logique                     |

### opérateurs bit à bit

| Opérateur 	| Nom 			| Description						 |
|---------------|-----------------------|--------------------------------------------------------|
|&		|ET bit à bit (AND)	|Chaque bit en sortie est 1 si les deux bits sont 1	 |
|`		|`			|OU bit à bit (OR)					 |
|^		|OU exclusif (XOR)	|Chaque bit en sortie est 1 si un seul bit est 1	 |	
|~		|NON bit à bit (NOT)	|Inverse tous les bits (complément à un)		 |
|<<		|Décalage à gauche	|Décale les bits vers la gauche (multiplie par 2^n)	 |
|>>		|Décalage à droite	|Décale les bits vers la droite (divise par 2^n, arrondi)|
