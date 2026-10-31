RetailPro — Análisis de ventas con SQL
Descripción del proyecto
RetailPro es un proyecto de análisis de datos orientado al área comercial. Su objetivo es trabajar con información de ventas para conocer el comportamiento comercial, identificar los productos con mayor facturación y obtener información útil para la toma de decisiones.
A través de consultas SQL, se busca transformar los datos almacenados en la base de datos en información que permita analizar el desempeño de las ventas.
Herramientas utilizadas
•	SQL Server: creación y administración de la base de datos.
•	SQL: consultas, filtros, agrupaciones, funciones de agregación y combinaciones de tablas.
•	GitHub: almacenamiento y organización de los archivos del proyecto.
Estructura del proyecto
El proyecto está organizado en los siguientes módulos:
Módulo 2 — Base de datos
Creación de la base de datos Ventas_Tech_DB y preparación de las tablas necesarias para trabajar con la información comercial.
Repositorio: https://github.com/ailinflorb-svg/ventas_tech_db.sql
Módulo 3 — Consultas SQL
Desarrollo de consultas para trabajar con los datos de ventas, clientes y productos, utilizando combinaciones de tablas y cálculos de facturación.
Repositorio: https://github.com/ailinflorb-svg/modulo-3-ventas_tech_db.sql
Módulo 4 — Consultas de negocio
Elaboración de consultas orientadas al análisis comercial, incluyendo resúmenes mensuales, ranking de productos y comportamiento de los clientes.
Repositorio: https://github.com/ailinflorb-svg/archivo-m4_consultas_negocio.sql
Módulo 5 — Consultas con JOINs
Desarrollo de consultas utilizando diferentes tipos de JOIN para relacionar información de las tablas de ventas, clientes y productos.
Repositorio: https://github.com/ailinflorb-svg/m5_consultas_joins.sql
Modelo de datos
La base de datos trabaja con las siguientes tablas:
Tabla	Descripción
ventas	Operaciones comerciales: fecha, cliente, producto, cantidad y precio unitario.
clientes	Información de los clientes: nombre, email, ciudad y fecha de registro.
productos	Información de los productos: nombre, precio, stock y categoría.
categorias	Categorías a las que pertenecen los productos.
Relaciones:
•	ventas.id_cliente → clientes.id_cliente
•	ventas.id_producto → productos.id_producto
•	productos.id_categoria → categorias.id_categoria
Cómo ejecutar el proyecto
1.	Instalar y abrir SQL Server Management Studio (SSMS).
2.	Descargar los archivos SQL desde los repositorios correspondientes.
3.	Ejecutar primero el script de creación de la base de datos del Módulo 1.
4.	Seleccionar la base de datos Ventas_Tech_DB.
5.	Ejecutar los scripts de los módulos siguientes, según corresponda.
6.	Revisar los resultados de las consultas para analizar la información comercial.
Nota: el script del Módulo 1 crea la base con CREATE DATABASE. Si ya existe, eliminala antes de volver a ejecutarlo.
Objetivo final
Utilizar SQL para analizar las ventas de RetailPro, reconocer tendencias, identificar los productos más relevantes y generar información que ayude al equipo comercial a tomar decisiones basadas en datos.
________________________________________
Proyecto académico — RetailPro

