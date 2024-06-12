#Enlaces <a></a>
1. Permiten redirigir a otras paginas y obtener recursos.
2. Existen 3 tipos de enlaces.
    a. Enlaces Absolutos
    b. Enlaces Relativos desde la ubicación del archivo
    c. Enlaces Relativos desde la raíz.
3. Los enlaces absolutos usan https:// o http://.
4. Los enlaces relativos usan ../ o ./ (recomendado).
5. El uso de un tipo de enlace u otro se decide según la situación.

#Listas
1. <ol> Lista ordenada (Numéricamente) 
2. <ul> Lista desordenada (Se usa un punto para separar cada uno de los elementos) 
3. <dl> Lista de definición 

#Tablas
1. Se crean con la etiqueta <table>
2. Se diseña mediante las etiquetas <tr> (Para las filas) y <td> (Para las columnas)

#Nav
1. Permite navegar entre paginas.
2. Es una etiqueta semántica.

#Emmet
1. Permite escribir el HTML de una manera mas fácil y rápida.
2. Al usar '>' define al hijo de la etiqueta que esta la izq del '>'.
2. Al usar '+' define al hermano de la etiqueta que esta la izq del '+'.
3. Al usar '*' repite n veces.
4. Al usar '{$}' numera cada repetición.
Ejemplo: 
nav>ul>(li>a{$})*3