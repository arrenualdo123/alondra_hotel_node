///lista de comandfos a usar en aws en ec2 pueden omitir algunos de estos a su parecer.

Actualizar el sistema: sudo dnf update -y
Instalar Node.js y NPM: sudo dnf install -y nodejs
Instalar PM2 (Gestor de procesos): sudo npm install -g pm2
Crear y mover al directorio del proyecto: cd ~/hotel-alondra

Instalar dependencias de Node.js: npm install
Construir la aplicación (Build): npm run build
Iniciar la aplicación con PM2 en el puerto 3000: pm2 start npm --name "HotelNextApp" -- run start -- -p 3000
Guardar el estado de PM2: pm2 save
Verificar el estado de PM2: pm2 status

Instalar Nginx: sudo dnf install -y nginx
Habilitar el inicio automático de Nginx: sudo systemctl enable nginx
Iniciar Nginx: sudo systemctl start nginx

Editar el archivo de configuración de Nginx: sudo nano /etc/nginx/nginx.conf
Verificar la sintaxis de Nginx: sudo nginx -t
Reiniciar Nginx para aplicar los cambios: sudo systemctl restart nginx



