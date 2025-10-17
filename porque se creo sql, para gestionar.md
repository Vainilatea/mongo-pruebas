porque se creo sql, para gestionar datos de forma estructuradas, grandes cantidades de datos llevaron a adaptación a no sql

para almacenar datos que van creciendo, cambiando se creo no sql, basadas en json

NoSQL se necesito para big data



* orientado a documentos, intuitivo y sensible, json pero se ve en bson
* los docs pueden tener estructuras aninadad y jerarquizas
* sin esquema fijo
* escabilidad horizontal
* fragmentación (sharding): datos se dividen
* replica sets: cada nodo tiene replicas para evitar perdidas si uno falla
* consultas ricas: filtros, proyecciones (elegir que datos se devuelven en resultados), 
* índices: de campo único, índice compuesto, índice textual
* pipelines de agregación para procesar datos:
* &nbsp;	->$match(filtra por criterios), $group(agrupa documentos para calcular estadisticas), $sort(ordena resultados), 	$project(seleciona y trasnforma campos)
* alta disponibilidad nodo primerio y secundario
* trasnsacciones acid 

compatibilidad con lenguajes de programacion python javascript, node, php, CALMOHADILLA



