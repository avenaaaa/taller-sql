# Taller de SQL

Práctica de SQL con datos reales de la NBA 2015-16 y de la final de 2016.

**Página:** https://avenaaaa.github.io/taller-sql/

## Qué tiene

- **Aprender:** por tema, ejemplos resueltos donde predices el resultado antes de verlo, con el paso a paso de lo que hace el motor y la versión con el error típico.
- **Practicar:** ejercicios que se comprueban solos, con dos pistas, la solución con su paso a paso y la opción de ejecutar sin que cuente como intento.
- **Referencia:** todos los ejemplos con su resultado, buscador, lo propio de BigQuery y una tabla de errores frecuentes.
- **Pizarra libre** para probar cualquier consulta, y un módulo final con datos de banco.

Temas: lo básico (SELECT, WHERE, ORDER BY, CASE), NULL con AND y OR, JOIN, GROUP BY con WHERE y HAVING, subconsultas y CTE, funciones de ventana, duplicados y filas que se multiplican, y fechas en BigQuery.

## Cómo funciona

Es una sola página estática. La base de datos es SQLite compilado a JavaScript ([sql.js](https://github.com/sql-js/sql.js), licencia MIT en `LICENSE-sql.js.txt`) y corre entera en el navegador: nada se envía a ningún servidor. En esta versión el avance se guarda solo en el navegador donde se usa.

JOIN, GROUP BY, HAVING, NULL, CASE, subconsultas, CTE y funciones de ventana se escriben igual en BigQuery. Las funciones de fecha se muestran con su sintaxis de BigQuery.

## Datos

Récords, promedios por partido y premios de la temporada 2015-16, y los puntos de cada partido de la final de 2016, tomados de basketball-reference.com y nba.com. La única tabla inventada es `carga_puntos`, que simula una carga con filas repetidas para la lección de duplicados.
