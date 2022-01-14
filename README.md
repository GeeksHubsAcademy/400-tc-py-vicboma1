<p align="center">
    <img src="https://github.com/GeeksHubsAcademy/2020-geekshubs-media/blob/master/image/logo.png" >	
</p>

 
	Considere el siguiente problema:

	Dada un número entero que actúa como el límite máximo del tamaño de la secuencia, se desea calcular una 
    montaña de números.
    
	Cada escalón se genera a través del empareamiento de dos de ellos en cada fila excepto la primera fila.
    En este caso base, ésta siempre empezará en 1. Por otro lado, el primer elemento y el último siempre será 1.
    La suma del elemento se hace a través de parejas de dos números consecutivos.

	Montaña :     2              3                   4

	Ejemplo:

	              1              1                   1 
                1   1          1   1               1   1
                             1   2   1           1   2   1
                                               1   3   3   1
   
    Notas:
    
    Tenga en cuenta los espacios entre elementos.
    El algoritmo debe de ser óptimo.


    En la carpeta 'src/kata.py' se encuentra el fichero con la 
    definición de nuestro método vacío.
    En la carpeta 'tests/kata_test.py' se encuentra el 
    fichero con la suite de test.
    
    El modus operandi de trabajo es el siguiente:
    
    Debes 'forkear' el proyecto a tu cuenta.
    Puedes hacer PR's ilimitadas e ir validando poco a poco la solución contra nuestro respositorio con CI.
    Puedes trabajar en local y subir la solución haciendo un PR a nuestro repositorio.
    Cuando se envíe la PR final, debes indicar el tiempo de dedicación y los intentos que has hecho.
    También puedes añadir un comentario para dar cualquier tipo de feedback.
    
    Recuerde que si usted no tiene configurado un límite de extensión de fichero de gran tamaño, es necesario
    ir a 

    Visual Studio Code
    File --> Preferences--> Setting and search for Max [Max Tokenization Length] = 200000

    En caso de duda, revisa en el apartado de 'Referencias'.

    tests/test_kata.py::Test_kata::test_apply_1 PASSED                       [ 10%]
    tests/test_kata.py::Test_kata::test_apply_10 PASSED                      [ 20%]
    tests/test_kata.py::Test_kata::test_apply_2 PASSED                       [ 30%]
    tests/test_kata.py::Test_kata::test_apply_3 PASSED                       [ 40%]
    tests/test_kata.py::Test_kata::test_apply_4 PASSED                       [ 50%]
    tests/test_kata.py::Test_kata::test_apply_5 PASSED                       [ 60%]
    tests/test_kata.py::Test_kata::test_apply_6 PASSED                       [ 70%]
    tests/test_kata.py::Test_kata::test_apply_7 PASSED                       [ 80%]
    tests/test_kata.py::Test_kata::test_apply_8 PASSED                       [ 90%]
    tests/test_kata.py::Test_kata::test_apply_9 PASSED                       [100%]
    	
	Process finished with exit code 0



## Referencias

* [Tutorial - Testing Automatizado](https://github.com/GeeksHubsAcademy/2020-js-vanilla-testing-FFFF/blob/master/README.md)
