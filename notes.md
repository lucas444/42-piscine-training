# Notes C


## Conversion

int -> long -> float -> double -> long doublea


## caractère

caractères d'une notation spéciale

| Notation En C | CODE ASCII | ABREVIATION USUELLE | Signfication            |
| ------------- | ---------- | ------------------- | ----------------------- |
| \a            | 07         | BEL                 | Cloche ou bip           |
| \b            | 08         | BS                  | Retour arriere          |
| \f            | 0C         | FF                  | saut de page            |
| \n            | 0A         | LF                  | Saut de ligne           |
| \r            | 0D         | CR                  | Retout chariot          |
| \t            | 09         | HT                  | Tablulation hotizontale |
| \v            | 0B         | VT                  | Tablulation verticale   |
| \\            |            |                     |                         |
| \'            |            |                     |                         |
| \"            |            |                     |                         |
| \?            |            |                     |                         |

## Operateur 


## Opérateurs arithmétiques en C

| Opérateur | Nom              | Description                                | Exemple (a=10, b=3) | Résultat |
| --------- | ---------------- | ------------------------------------------ | ------------------- | -------- |
| `+`       | Addition         | Additionne deux valeurs                    | `a + b`             | `13`     |
| `-`       | Soustraction     | Soustrait la deuxième valeur à la première | `a - b`             | `7`      |
| `*`       | Multiplication   | Multiplie deux valeurs                     | `a * b`             | `30`     |
| `/`       | Division entière | Divise la première valeur par la seconde   | `a / b`             | `3`      |
| `%`       | Modulo (reste)   | Donne le reste de la division entière      | `a % b`             | `1`      |
| `++`      | Incrémentation   | Ajoute 1 à la variable                     | `a++` ou `++a`      | `11`     |
| `--`      | Décrémentation   | Soustrait 1 à la variable                  | `a--` ou `--a`      | `9`      |

### Opérateurs Conditionnelle

```C
if ( a > b)
	max =a;
else
	max = b;
```
```C
/* Si a>b alors a sinon b **/

max = a > b ? a : b 
```

### Opérateurs logiques (`booléens`) en C

| Opérateur | Nom               | Description                           |                 |                                            |
| --------- | ----------------- | ------------------------------------- | --------------- | ------------------------------------------ |
| `&&`      | ET logique (AND)  | Vrai si les deux opérandes sont vrais |                 |                                            |
| `         |                   | `                                     | OU logique (OR) | Vrai si au moins un des opérandes est vrai |
| `!`       | NON logique (NOT) | Inverse la valeur logique             |                 |                                            |

### opérateurs bit à bit

| Opérateur | Nom                 | Description                                              |     |
| --------- | ------------------- | -------------------------------------------------------- | --- |
| &         | ET bit à bit (AND)  | Chaque bit en sortie est 1 si les deux bits sont 1       |     |
| `         | `                   | OU bit à bit (OR)                                        |     |
| ^         | OU exclusif (XOR)   | Chaque bit en sortie est 1 si un seul bit est 1          |     |
| ~         | NON bit à bit (NOT) | Inverse tous les bits (complément à un)                  |     |
| <<        | Décalage à gauche   | Décale les bits vers la gauche (multiplie par 2^n)       |     |
| >>        | Décalage à droite   | Décale les bits vers la droite (divise par 2^n, arrondi) |     |


## Opérateurs de comparaison en C

| Opérateur | Nom                 | Description                                            | Exemple (a=10, b=3) | Résultat |
| --------- | ------------------- | ------------------------------------------------------ | ------------------- | -------- |
| `==`      | Égal à              | Renvoie vrai si les deux valeurs sont égales           | `a == b`            | `false`  |
| `!=`      | Différent de        | Renvoie vrai si les deux valeurs sont différentes      | `a != b`            | `true`   |
| `>`       | Supérieur à         | Vrai si la première valeur est strictement plus grande | `a > b`             | `true`   |
| `<`       | Inférieur à         | Vrai si la première valeur est strictement plus petite | `a < b`             | `false`  |
| `>=`      | Supérieur ou égal à | Vrai si la première valeur est supérieure ou égale     | `a >= b`            | `true`   |
| `<=`      | Inférieur ou égal à | Vrai si la première valeur est inférieure ou égale     | `a <= b`            | `false`  |

