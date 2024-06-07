# Desafio 5 LATAM - Tienda de Joyas - Jorge Espinoza R.

### Requerimientos

#### Se crea ruta GET /joyas que devuelve todas las filas del inventario de joyas (1 Punto)
##### - Puede recibir parametros "limits", "page" y "order_by"
### Se crea ruta GET /joyas/filtros  (1 Punto)
#### - Puede recibir "precio_max", "precio_min", "categoria" y "metal"
### Se implementa un middleware llamado logger.js que registra las peticiones a sus rutas correspondientes en un archivo reporte_actividad.log  (1 Punto)
### Se implementan bloques try-catch para capturar errores (1 Punto)
### Se usan consultas parametrizadas para evitar SQL Injection (1 Punto)