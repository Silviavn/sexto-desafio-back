### Mongo db (Comandos de apoyo para gestionar mejor nuestra base de datos)

show dbs: muestra las bases de datos existentes

use <db name>: Crea una nueva base de datos (en caso de no existir) y se posiciona sobre ella

db: Muestra en que base de datos estamos posicionados

show collections: Muestra todas las colecciones disponibles  en la base de datos posicionada

db.createColleccion(name): Crea una nueva coleccion en la base de datos posicionada

db.dropDatabase():Elimina la base de datos actual

db.collection.drop: Elimina la base de datos posicionada

## Primeros comandos CRUD

db.collection insertOne(doc): Agrega un nuevo documento a la coleccion seleccionada

db.collection.insertMany(docs):Agrega multiples documentos a la coleccion seleccionada(dado un arreglo de documentos)

db.collection.findOne(opt):Busca un elemento que cumpla con los criterios de busqueda (opt), devuelve el primer documento que cumpla con dicho criterio.

db.collection.find(opt): Devuelve todos los documentos que cumplan con dicho criterio

db.collection.find(opt).pretty(): Añadido para hacer mas presentables los resultados de un find().




## CRUD

C: create (Crear un dato e insertarlo en la base de datos)
R: Read (Leer un dato, mostrarlo al cliente)
U: Update: ( Actualizar un dato, cambiar su informaciòn)
D: Delete (Borrar un dato)

