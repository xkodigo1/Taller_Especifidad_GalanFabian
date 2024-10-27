# Taller_Especifidad_GalanFabian
README con la solución del taller. Especificando Nro Parte. Enunciado, Solucion y ScreenShoot de la ejecucion
# Parte 1: Introducción Teórica a la Especificidad
A: La especificidad en CSS determina qué tan relevante es una regla CSS específica para un elemento particular. Cuando el navegador encuentra varios estilos que pueden aplicarse a un elemento, verifica la especificidad de cada regla y aplica la más específica. Los selectores son:

   1. Selectores de ID: Valor de especificidad de 100 puntos.
   2. Selectores de clase, pseudoclases y atributos: Valor de especificidad de 10 puntos.
   3. Selectores de elementos y pseudoelementos: Valor de especificidad de 1 punto.

| Selector                            | Ejemplo                     | Especificidad Calculada |
|-------------------------------------|-----------------------------|-------------------------|
| **Selector universal**              | `*`                         | 0                       |
| **Selector de elemento**            | `p`                         | 1                       |
| **Selector de pseudoelemento**      | `p::before`                 | 1                       |
| **Selector de clase**               | `.mi-clase`                 | 10                      |
| **Selector de atributo**            | `[type="text"]`             | 10                      |
| **Selector de pseudoclase**         | `:hover`                    | 10                      |
| **Selector de ID**                  | `#mi-id`                    | 100                     |
| **Selector en línea (style)**       | `style="color: red;"`       | 1,000                   |
| **Selector `!important`**           | `color: red !important;`    | N/A*      

# Parte 2: Ejemplos Prácticos

