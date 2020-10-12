#A Java WebDriver Page Object Framework
Test Parte 1
Para la parte uno de la prueba se puede observar
El caso de prueba se encuentra en el path /com.regression-tests/src/test/java/com/framework/tests.
Precondiciones
*El archivo example file.txt debe existir en la ruta /Test-Automation-Framework/resources/

Casos Negativos
Verifique que el archivo exista cuando es cargado por el sistema.
Verifique que el archivo pueda ser leído en el caso de que solo sea permitido un tipo de formato.
Verifique que si existen dos palabras diferentes con el mismo tamaño (suponiendo que la primera encontrada tiene mayor prioridad) muestra la palabra original más larga o muestra en un array todas las palabras encontradas del mismo tamaño.
Verifique si en el caso de dos palabras de igual tamaño el sistema imprime todas las palabras encontradas del mismo tamaño.
Verifique que las palabras tengan un formato correcto asignado en el requerimiento.
Verifique que el archivo no exceda el peso máximo(en el caso de que el requerimiento lo tenga).
Verifique que el output contenga todas las palabras encontradas.
Casos Positivos
Verifique que la palabra más larga es la mostrada en el output.
Verifique que la la palabra es mostrada de forma inversa en el output.
Verifique que el output pueda ser exportado a otro formato (de acuerdo a el requerimiento).
Verifique el tiempo que le toma al sistema obtener los resultados (si el requerimiento lo dice).
Verifique que el output sea entendible por el usuario(de acuerdo a el requerimiento).

Test Parte 2
El javadoc puede ser encontrado en la carpeta resources bajo el path /Test-Automation-Framework/resources.
Para la parte dos de la prueba tenemos:

El framework consta de 3 módulos que a continuación especifico:
 En el path /com.regression-tests/src/test/java/com/framework/tests se pueden encontrar los test creados.
 En el path /com.framework/src/main/java/com/framework/core se pueden encontrar dos clases la Base Test y la BasePage las cuales se encargan de suministrar los métodos via extends tanto a los pague objects class como a los test
 En el path /com.pageobjects/src/main/java/com/pageobjects pueden encontrar los page objects para cada página creada con sus respectivos selectores y métodos llamados por los tests
Consideraciones
El test se corre con TestNG.
El API corre por debajo por lo tanto no se va a ver la creación del producto por lo tanto agregue unos prints para que se pueda verificar tanto el ID del producto como el Nombre del mismo.
Por lo tanto debería tener un output de esta forma:

Product created with the name Quality279

Product created with the id 6622

Updating the quantity on the cart

Removing the product

The Status Code is correct :200

Product deleted with the Id 6622

