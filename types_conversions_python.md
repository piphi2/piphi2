# Types de variables et conversions en Python

## Types de valeurs

### Nombres entiers

Exemples : `7`, `128`, `0`\
Classe Python : **int**

### Nombres décimaux

Exemples : `3.29`, `5.0`\
Classe Python : **float**

### Chaînes de caractères

Exemples : `'a'`, `'A'`, `'123'`, `'ABCD'`, `"A1B2C3"`, `'Hello world !'`\
Classe Python : **str**

### Listes d'éléments (tableaux)

Exemples : `[8, 4]`, `['8', '4']`, `['A', 'B']`\
Classe Python : **list**

------------------------------------------------------------------------

## Conversion de variables

### Conversion vers `int`

  |Type source  | Valeur    |  Instruction  | Résultat|
  ------------- | --------- |----------     |----------|
  |`str`        |   `"26"`  | `int("26")`   |  `26`|  
  `str`         |   `"1.7"` | `int("1.7")`  | Erreur|
  `str`         |   `"AB"`  |  `int("AB")`  |Erreur|
  `float`       |   `2.87`  | `int(2.87)`   |`2`|

### Conversion vers `float`

  |Type source  | Valeur    |  Instruction  | Résultat|
  ------------- | --------- |----------     |----------|
   |`str`       |   `"5"`   |   `float("5")`  |`5.0`|
  |`str`        |   `"5.2"` |   `float("5.2")`|`5.2`|

### Conversion vers `str`

 |Type source  | Valeur    |  Instruction  | Résultat|
  ------------- | --------- |----------     |----------|
   |`int`        | `123`   | `str(123)`   |  `"123"`
  |`float`      | `5.2`    | `str(5.2)` |  `"5.2"`

### Conversion vers `list`

  |Type source  | Valeur    |  Instruction  | Résultat|
  ------------- | --------- |----------     |----------|
   `str`        |  `"ABC"` |  `list("ABC")` |  `['A', 'B', 'C']`
  `str`        | `"123"`  |  `list("123")`  | `['1', '2', '3']`
 |`int`        | `123`    |  `list(123)`    |  Erreur
