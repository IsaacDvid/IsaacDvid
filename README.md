   
 # Historia técnica ED-002  

### datebase

* la base de datos y utilizemos es **mySQL** crea una base de datos con el nombre tienda online, después crea una tabla con los campos únicos a rellenar con los siguientes campos: ID (llave primaria), Nombre, descripción, imagen y existencia. 
* Creando la tabla con los siguientes campos:   

|ID|Name|Description|Image|Stock|Price|
|-|:-:|-:|-:|-|-|
| | ||
| | | |
| | | |

**Installation**
```bash
$ npm install
```

**Running the app** 

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```
### Metodos: 
 
* POST: [Crear un nuevo producto](http://localhost:3000/products)
* GET: [Mostrar los productos](http://localhost:3000/products)
* DELETE: [Eliminar un producto](http://localhost:3000/products)
* PATCH: [Actualizar un producto](http://localhost:3000/products)

> **NOTA:** Estos metodos solamente se deben utilizar con Postman, para manejar las peticiones post, delete y patch.

