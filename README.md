# colorSort
Algoritmo de la bandera holandesa en c++

1. [-Se inicializan tres variables enteras, red, white y blue, que representan la cantidad de elementos que hay de cada color en el arreglo. Al inicio, todas estas variables son iguales a cero.]

2. [-Se recorre el arreglo con un bucle for y se cuentan los elementos de cada color. Si el número actual es 0, se incrementa la variable red, si es 1, se incrementa la variable white y si es 2, se incrementa la variable blue.]

3. [-Luego de contar la cantidad de elementos de cada color, se procede a ordenar el arreglo. Se inicializa una variable entera i en cero, que será utilizada para recorrer el arreglo.]

4. [-Se utilizan tres bucles while para recorrer el arreglo y reemplazar los elementos en su posición correcta. El primer bucle while coloca los elementos rojos en las -primeras posiciones del arreglo. Para ello, se coloca el valor 0 en las primeras red posiciones del arreglo y se decrementa la variable red en cada iteración.]

5. [-El segundo bucle while coloca los elementos blancos en las posiciones siguientes. Para ello, se coloca el valor 1 en las siguientes white posiciones del arreglo y se decrementa la variable white en cada iteración.]

6. [-El tercer bucle while coloca los elementos azules en las últimas posiciones del arreglo. Para ello, se coloca el valor 2 en las últimas blue posiciones del arreglo y se decrementa la variable blue en cada iteración.]

7. [-Al final de los tres bucles while, el arreglo habrá sido ordenado según los colores de los elementos que contiene.]


# Ejemplo

![image](https://user-images.githubusercontent.com/89582094/235976129-8fd2c059-287f-4e6c-b0e3-4575e319babc.png)

