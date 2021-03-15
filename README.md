# Apuntes_UF2_2

## Hediondez del código
Como hediondez de código, entendemos que el código esta mal escrito, no por tener bugs, sino por estar escrito o con demasiadas líneas cosas que se podrían solucionar en 2 líneas o código muy corto y muy específico que impide la modularidad del programa. 

**Ejemplos**:
 + Ejemplo1: Métodos demasiado largos que luego resultan imposibles de cambiar.
 + Ejemplo2: Ifs que no tienen sentido o que se contradicen con otros ifs.
 + Ejemplo3: Muchos Ifs que se pueden solucionar con un CASE.
 + Ejemplo4: Código no documentado.
 + Ejemplo5: Nombre de variables sin sentido.

## Análisis de código
Tenemos diferentes métodos para analizar el codigo, podemos analizar-lo de forma dinámica o de forma estática

### Análisis de código dinámico
És un tipo de análisis de código más lento, ya que se realiza mientras se ejecuta el código, por lo que después de escribir algunas líneas de código tendremos que ir mirando de no haber hecho ningun fallo.

### Análisis de código estático
El análisis de código estático, és mucho más rápido que el dinámico ya que no se tiene que ejecutar el código, sino que se mira como esta escrito el código del programa para llegar a detectar errores. 

Tenemos diferentes herramientas para el análisis estático. Un caso sería el linter, que nos dice donde hay código redundante, código con errores, etc., para que nosotros como programadores podamos solucionar-los.
Hay diferentes programas, por ejemplo:
 + **Lint**: C
 + **Sonar**: Java
 + **JSLint, ESLint**: Javascript
Hay que decir que la mayoría de estos programas tienen plan de pago, pero siempre tenemos opciones free hechas por la comunidad.

## Refactorización
La refactorización, es reestructurar el código de forma más sencilla o de forma más compacta para que la siguiente persona que lo lea le sea más fácil entender que hace el programa. Hay que hacer la refactorización solo cambiando el código interno, sin alterar la salida que da.
Las técnicas que más se suelen usar son:
 + **Renombrar las variables**, para darles un nombre más fácil o más entendibles
 + Pasar **código duplicado a funciones**, para no tener código repetido todo el rato en el programa
 + **Eliminar código inalcanzable**, para no usar código que nunca se va a ejecutar y ocupar espacio de forma tonta
 + **Eliminar código redundante**, código que solo nos ocupa memoria y no influye en la salida del programa.
