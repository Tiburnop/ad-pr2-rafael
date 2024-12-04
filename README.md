1. Accede al repositorio de GitHub y clónalo en tu máquina local con el siguiente comando en la terminal:
git clone https://github.com/Tiburnop/ad-pr2-rafael.git

2. cd ad-pr2-rafael

3. Abre la carpeta del proyecto en Visual Studio Code con este comando:
  code .
4. Dentro de Visual Studio Code, abre una terminal y navega al directorio del backend:
  cd backend

5. Ejecuta los siguientes comandos para configurar el backend:
  Instala las dependencias de PHP usando Composer(en caso de no tenerlas):
  composer install -n --prefer-dist
  Crea el archivo de configuración .env:
  cp .env.ci .env
  Genera una nueva clave para la aplicación de Laravel:
  php artisan key:generate
  Inicia el servidor de desarrollo en Laravel:
  php artisan serve
6. Ahora que el servidor del backend está funcionando, es momento de configurar el frontend. Navega a la carpeta del frontend:
  cd ../frontend
7. Abre el archivo index.html en tu navegador para comenzar a interactuar con la aplicación:
  xdg-open index.html
