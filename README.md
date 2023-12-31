# SnakeGraphPerfectMatchingsCalculator
Calculates the number of perfect matchings of any snake graph by using the corresponding Christoffel word; which is found via the following algorithm. Let S be your snake graph, which is composed by tiles G_1,G_2,...,G_n ; if n = 1, then it means that there is a single tile; i.e. there are just 3 perfect matchings. If n > 1, then the i^th letter in the Christoffel word is determined by the position of tile G_{i+1} with respect to tile G_i. In other words, if tile G_{i+1} is attached to tile G_i via the east edge, then the i^th letter is "e" (for east); conversely, if tile G_{i+1} is attached to tile G_i via the north edge, then the i^th letter is "n" (for north).


<img width="695" alt="Screenshot 2023-07-23 at 16 50 27" src="https://github.com/BonucciAndrea/SnakeGraphPerfectMatchingsCalculator/assets/89645554/b87fe3d4-276f-4bde-a6f5-83b636934eb6">


For example, the Christoffel words of the above two snake graphs are "enne" and "eeenneee".
