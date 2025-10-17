**motivaciones mongodb**

flexibilidad

redundancia de datos, alta disponibilidad - replica sets (datos divididos por si se cae un nodo hay backup)

usa master node

modelo de datos (json,bson) fáciles de leer

escalabilidad horizontal (sharding) distribuye datos, gran volumen de datos

alto rendimiento (es rápido)

potente consulta de datos (usa pipelines y operaciones complejas)

compatible con multiples lenguajes



--------------------------------



**tipos de db**

documentales - mongodb/elasticsearch/kivana - ecommerce

clave valor - redis - loggings (true false)

columnares - hbase/cassandra/big table (logs por ejemplo de registros los últimos mil)

grafos - neo4j (redes sociales)

arrays - influx db - sensores estar escribiendo constantemente



-----------------------------------



READ: recuperar elementos de una colección

find: devuelve todos los que coincidan

findOne: devuelve el primero solo

$and, or, not, nor, all,exists, type, regex (busca patrones), 

db.>colecion>.find(<filtro>)



