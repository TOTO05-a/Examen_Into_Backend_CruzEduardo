![Imagen, tabla libros](./Capturas/tienda%20libros.png)
Analice la tabla inicial que contiene información de libros, autores, clientes, pedidos y transacciones. y le fui aplicando el proceso de normalización hasta la Tercera Forma Normal (3FN).

![Imagen, tabla (1NF) ](./Capturas/Captura%20desde%202026-04-22%2012-04-28.png)

Aca lo que hice fue que separe los nombres de los apellidos, dejandola mejor para que sea mas facil de entender

![Imagen, tabla (2NF) libros](./Capturas/Segunda%20forma%20relacional(2FN)tabla%20libros.png)

Aquí aplicamos la 2FN. Los datos como el título y el autor dependen únicamente del ISBN. Sacamos la editorial y categoría a sus propias tablas para cumplir con la 3FN, dejando solo las llaves foráneas (FK).

![Imagen, tabla (2NF) clientes](./Capturas/(2NF)tabla%20clientes.png)

El cliente existe independientemente de si compra o no.

![Imagen, tabla (3NF) libros](./Capturas/(3NF)%20tabla%20libros.png)

![Imagen, tabla (3NF) Ventas](./Capturas/(3NF)tabla%20ventas.png)

 Esta tabla une todas las anteriores. Representa el evento de la compra. El monto se queda aquí porque es el valor específico de esa transacción en ese momento.

![Imagen, tabla (3NF) editoriales](./Capturas/(3NF)tabla%20editores.png)

Las editoriales son entidades independientes. Si una editorial cambia de nombre, solo lo editás aquí

![Imagen, tabla (3NF) categoriasos](./Capturas/(3NF)tabla%20categorias.png)

En la tabla original, el texto, Infantil o Romance se repetiría en cada libro y al crear una tabla maestra, ahorrare espacio y evito errores 

![Imagen](./Capturas/Captura%20desde%202026-04-22%2012-57-26.png)
