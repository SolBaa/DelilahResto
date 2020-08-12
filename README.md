# Delilah Restó 



# Set up
1. Instale un entorno de servidor local (se recomiendan XAMPP o MAMP) utilizado para MySQL
2. Inicie el servidor(Apache con entorno sugerido) y MySQL. Asegurate que el puerto sea 8889
3. Asegurate de tener un perfil con nombre de usuario y contraseña 'root' en MySQL.
4. Importa (./database/dbForIMport.sql) contiene todas las SQL queries para crear la base de datos y crea las tablas necesarias. ambién hay consultas para completar estas tablas. 



# Server init

```bash
git clone https://github.com/Solbaa/DelilahResto
cd delilah-resto
npm install
```
Iniciar servidor. 
```bash
npm start
```

# Endpoints 
Los endpoint estan detallados en (../documentation/swagger.yml) 

# Endpoints Testing
(../documentation/Delilah Resto.postman_collection.json) En postman se podran testear todos los endpoints. (Algnos requieren roles de administrador, se tendra que incluir el token correspondiente). 