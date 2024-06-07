# Desafio 5 LATAM - Tienda de Joyas - Jorge Espinoza R.

### Requerimientos

#### 1. Se crea ruta GET /joyas que devuelve todas las filas del inventario de joyas (1 Punto)
##### - Puede recibir parametros "limits", "page" y "order_by"
### 2. Se crea ruta GET /joyas/filtros  (1 Punto)
#### - Puede recibir "precio_max", "precio_min", "categoria" y "metal"
### 3. Se implementa un middleware llamado logger.js que registra las peticiones a sus rutas correspondientes en un archivo reporte_actividad.log  (1 Punto)
### 4. Se implementan bloques try-catch para capturar errores (1 Punto)
### 5. Se usan consultas parametrizadas para evitar SQL Injection (1 Punto)

### Rutas Requeridas
1. HATEOS en ruta http://localhost:3000/joyas?limits=3&page=2&order_by=stock_ASC
   ![alt text](https://github.com/jierzen/joyas/blob/main/consulta%201.png)

2. Filtrando por multiples parametros http://localhost:3000/joyas/filtros?precio_min=25000&precio_max=30000&categoria
=aros&metal=plata
![alt text](https://github.com/jierzen/joyas/blob/main/consulta%202.png)
