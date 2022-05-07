# Nginx

### 1. Instalar Nginx en windows y ejecutar el archivo nginx.exe como administrador

<img src="https://i.gyazo.com/1c87ee90da83253b539347cdb68e4cc8.png">

### 2. Comprobamos que Nginx se haya iniciado bien

<img src="https://i.gyazo.com/1b18d9b39d95835372a7d4780ffc1be0.png">

### 3. Habilitamos la consola de administración IIS de Windows que nos servirá para configurar la web posteriormente:

<img src="https://i.gyazo.com/d35eaa1766e38d4cd4c37a274dac5e70.png">

### 4. Cambiamos la ruta física del Default Web Site a la que deseemos

<img src="https://i.gyazo.com/7d040646f80e916ee0ce18b95a6028c2.png">

<img src="https://i.gyazo.com/efdb9abe364b4e63d8ead8aef76ff694.png">

### 5. Accedemos a la carpeta "conf" de nginx, en la que modificaremos el archivo "nginx.conf" para cambiar el root a la ruta física que hemos añadido previamente

<img src="https://i.gyazo.com/2110c2cf1b38cb10f297c95ec56aa173.png">

<img src="https://i.gyazo.com/b1ee606ab39699a07c703057c5d62d81.png">

### 6. Y por último introducimos el .html dentro de la carpeta que hayamos creado previamente. Ahora al acceder al "localhost" se debería de ver el .html introducido.

<img src="https://i.gyazo.com/58e4d86af648fb30876e0e799216b57d.png">

<img src="https://i.gyazo.com/3d1158aa66f6628987cf98805fa98158.png">
