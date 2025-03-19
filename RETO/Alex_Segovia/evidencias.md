## **RESOLUCIÓN EJERCICIO CROSS-SITE SCRIPTING DE LA PLATAFORMA PORTSWIGGER**

### 1. Seleccionamos el LAB **DOM XSS in document.write sink using source location.search**

![](./img/1.png)

### 2. A continuación, encontramos la descripción del LAB.

![](./img/2.png)

### 3. Ingresamos el laboratorio y vemos lo siguiente, tiene una barra de buscador:

![](./img/3.png)

### 4. Vemos que en la barra del navegador 

![](./img/4.png)

### 5. Ahora vemos el código fuente de la página (ctrl+u) para buscar y ubicar (location.search) y (windows.write) en base a lo que nos mencionaba la descripción del laboratorio.

![](./img/5.png)

### 6. Una vez determinado cómo funciona la barra de búsqueda podemos observar que se podría incluir código JavaScript por ahí para modificar la etiqueta HTML (img).

![](./img/6.png)

### 7. Este es el resultado y nos aparece el pop-up con lo puesto

![](./img/7.png)

### 8. Con esto el laboratorio queda solucionado.

![](./img/8.png)

![](./img/9.png)




