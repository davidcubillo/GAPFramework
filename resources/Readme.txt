Test Parte 1
Para la parte uno de la prueba se puede observar
El caso de prueba se encuentra en el path /com.regression-tests/src/test/java/com/framework/tests.
Precondiciones
*El archivo example file.txt debe existir en la ruta /Test-Automation-Framework/resources/
El archivo está presente en esa ruta por lo tanto no debería tener problemas para correr el caso

Casos Negativos
Verifique que el archivo exista cuando es cargado por el sistema
Verifique que el archivo pueda ser leído en el caso de que solo sea permitido un tipo de formato
Verifique que si existen dos palabras diferentes con el mismo tamaño (suponiendo que la primera encontrada tiene mayor prioridad) muestra la palabra original más larga o muestra en un array todas las palabras encontradas del mismo tamaño
Verifique si en el caso de dos palabras de igual tamaño el sistema imprime todas las palabras encontradas del mismo tamaño
Verifique que las palabras tengan un formato correcto asignado en el requerimiento
Verifique que el archivo no exceda el peso máximo(en el caso de que el requerimiento lo tenga)
Verifique que el output contenga todas las palabras encontradas

Casos Positivos
Verifique que la palabra más larga es la mostrada en el output
Verifique que la la palabra es mostrada de forma inversa en el output
Verifique que el output pueda ser exportado a otro formato si el requerimiento lo dice
Verifique el tiempo que le toma al sistema obtener los resultados (si el requerimiento lo dice)
Verifique que el output sea entendible por el usuario

Test Parte 2
Para la parte dos de la prueba tenemos:
El javadoc puede ser encontrado en la carpeta resources bajo el path /Test-Automation-Framework/resources.
El framework consta de 3 módulos que a continuación especifico:
 En el path /com.regression-tests/src/test/java/com/framework/tests se pueden encontrar los test creados.
 En el path /com.framework/src/main/java/com/framework/core se pueden encontrar dos clases la Base Test y la BasePage las cuales se encargan de suministrar los métodos via extends tanto a los pague objects class como a los test
