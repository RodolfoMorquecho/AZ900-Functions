# AZ900-Functions
Es una fracción de codigo que permite ejecutar acciones, cumplir con peticiones para traer cosas de internet, etc. Se denominan como serverless.

Lo primero que debemo hacer, es dirigirnos al portal de [Azure](https://portal.azure.com/#home)

## Paso 1
En en la vista de Home nos posicionamos en el menú y seleccionamos "Aplicación de funciones".

![1](https://user-images.githubusercontent.com/99112892/174917980-b41bdebe-75ff-4f76-87ce-fc0f7802116b.png)

## Paso 2
Creamos una Function.

![2](https://user-images.githubusercontent.com/99112892/174918048-a60da737-e73d-4a45-8b24-2516e87695f7.png)

## Paso 3
### Pestaña:Datos básicos
- Nos aseguramos de que la suscripción es de tipo 'student'.
- Creamos un nuevo grupo de recursos, el cual sería un folder donde vamos a guardar nuestra aplicación web dentro de la nube, lo nombramos como: lab04-dr.
- Para este ejemplo, nombramos a la aplicación de funciones como "hello-dr".
- Publicar mediante código.
- La "pila del entorno en tiempo de ejecución" es con el lenguaje/codigo con el que esta realizada nuestra aplicacion de funciones, en este caso uaremos: Node.js.
- La versión con la que trabajadar de Node.js es "16 LTS".
- En la Región para esta ocasion utilizamos Central US.
- El sistema operativo que usaremos sera Windows.
- Y el plan que utilizaremos sera "Consumo (Sin servidor)".
El plan elegido dicta cómo se escala la aplicación, qué características están habilitadas
y cómo se establece el precio.
- Nos vamos a la pestaña etiquetas.

![3](https://user-images.githubusercontent.com/99112892/174918166-3989e3f7-baee-4683-a6a4-d466cade6c93.png)

### Pestaña:Tags(Etiquetas)
Las etiquetas nos sirven para cuando hay muchas personas trabajando dentro de una organización, es importante saber quien esta subiendo que cambios.

![4](https://user-images.githubusercontent.com/99112892/174918226-fd93f463-a750-430e-b74a-dac8df79704d.png)

### Pestaña:Review+Create(Revisar y Crear)
- Analiza todo lo requerido anteriormente para proceder a aprovisionarlo. 
- Pulsamo en 'crear'.

![5](https://user-images.githubusercontent.com/99112892/174918288-5feb6ade-815f-4621-90b2-9dc5caa21c38.png)


- Esperaremos unos segundos hasta que se complete la implementación.
- Cuando este lista, presionamos en "ir al recurso".

![6](https://user-images.githubusercontent.com/99112892/174918372-8a1af420-8194-4e91-901e-9f385ddbd437.png)

## Paso 4
Nos ubicara automaticamente en la sección "introducción" donde obtendremos toda la informaciíón de nuestra function creada.
- Para ver que nuestra Function esta corriendo entramos al link que nos aparece posicionado a lado de "URL".

![7](https://user-images.githubusercontent.com/99112892/174918443-901e69ee-3b26-4960-b172-dd32c8744015.png)

- Verificamos que esta funcionando y corriendo a la prefección nuestra aplicación.

![8](https://user-images.githubusercontent.com/99112892/174918524-71871fb7-c515-4ddd-874e-d780da2af75a.png)

## Paso 5
- Regresamos a la interfaz previa donde esta la información esencial y en el menú lateral izquierdo presionaremos "Funciones".

![9](https://user-images.githubusercontent.com/99112892/174918559-018ed177-0a10-4185-b52c-2208daf0870a.png)

- Agregaremos una function.

![10](https://user-images.githubusercontent.com/99112892/174918599-e50706cd-fcfc-4fce-9915-ca47f25759d3.png)

- Buscaremos una function "HTTP" y le daremos en Crear , es una función a la que le pasaremos argumentos y esta se ejecutara.

![11](https://user-images.githubusercontent.com/99112892/174918639-0f4172aa-a0e3-4102-92f1-172bfebc8c7d.png)

## Paso 6
- Ya creada nuestra función HTTP, tendremos está interfaz, donde iremos a la opción "Código y prueba".

![12](https://user-images.githubusercontent.com/99112892/174918742-fc1b6900-63a4-46e9-8322-395512aee267.png)

Nos aparacera el codigo de la function.
- Primero obtendremos la URL y la copiamos.

![13](https://user-images.githubusercontent.com/99112892/174918801-de13b33c-fe89-433e-8c30-335b316df26c.png)

- Lo pegamos en una pestaña nueva y nos aparecera el siguiente mensaje.

![14](https://user-images.githubusercontent.com/99112892/174918902-cbc0140f-5f85-47eb-8ee6-cdce3063f4df.png)

## Paso 7
Tenemos nuestra funtion implementada y corriendo pero necesitamos ver que se ejeccute ante una petición.
- Como se pide en el mensaje, necesitamos agregar un nombre en la URL para obtener una respuesta personalizada, por lo que nos dirigimos a esa sección y procedemos a agregar: "&&name=Rodolfo".

![15](https://user-images.githubusercontent.com/99112892/174919006-01bd1047-a410-4cc6-a684-6adb7537f673.png)

- Obtendremos nuestra respuesta personalizada. 

![16](https://user-images.githubusercontent.com/99112892/174919038-8b6130d7-4a9d-41a4-9df8-e82658ab857f.png)





