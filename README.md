# Proyecto de Análisis de Inventarios y Ventas con Power BI

## Descripción del Proyecto
Este proyecto está orientado a la optimización de inventarios para una empresa. Utilizando **Power BI**, se analizaron datos históricos de ventas, compras e inventarios para tomar decisiones informadas sobre la *gestión de inventarios y las *compras de productos.

### Objetivos del Proyecto:
- **Proyección de inventarios**: Calcular el **inventario recomendado** en base a las ventas pasadas y el tiempo de entrega.
- **Análisis de compras**: Estudio de las compras realizadas por proveedor y por ciudad.
- **Análisis de ventas**: Visualización de ventas mensuales y proyección de ventas por producto.
- **Excedente de inventarios**: Identificación de productos con exceso de stock, lo cual puede generar **costos adicionales**.
- **Análisis geográfico**: Mapa de ventas y compras por ciudad.

---

## Proceso de Desarrollo

### 1. **Identificación y Comprensión de los Datos**:
El primer paso del proyecto consistió en **analizar los datos disponibles**. Se comenzó con la identificación de las **tablas** proporcionadas y las **columnas** que contenían. Para cada columna, se revisó su **descripción** para comprender su función y propósito en el conjunto de datos. Posteriormente, se clasificaron las **variables** en **métricas** y **atributos** para poder diferenciarlas y asignarlas a las **tablas de hechos** o **dimensiones** correspondientes.

### 2. **Estructuración de Tablas de Hechos y Dimensiones**:
Con los datos comprendidos y clasificados, el siguiente paso fue **estructurar las tablas de hechos y dimensiones**. Se identificaron las **métricas clave** y los **atributos** que serían necesarios para responder a los requerimientos del proyecto. Con base en esta identificación, se **creó la propuesta de tablas** que incluirían tanto las **dimensiones** (por ejemplo, productos, proveedores, fechas, etc.) como las **tablas de hechos** (ventas, compras, facturas e inventarios).

### 3. **Limpieza de Datos con Power Query**:
Antes de empezar a cargar y estructurar los datos en **Power BI**, se realizó una **limpieza exhaustiva** de los datos usando **Power Query**. Durante esta fase:
- Se **identificaron valores nulos** o erróneos y se corrigieron.
- Se **eliminaron columnas irrelevantes** que no aportaban valor al análisis, optimizando así el modelo de datos.
- Se **ajustaron tipos de datos** donde era necesario, para asegurar que cada columna tuviera el formato adecuado y evitar problemas al trabajar con las visualizaciones.
- Se llevó a cabo una **limpieza general** de los datos para asegurar que la **calidad de los datos** fuera la adecuada antes de ser cargados en Power BI.

### 4. **Carga de Datos y Modelado en Power BI**:
Una vez limpiados los datos, se procedió a **cargar las tablas de hechos y dimensiones** en **Power BI**. En la **Vista de Modelo**, se crearon las **relaciones** entre las tablas, teniendo especial cuidado con la **cardinalidad** de las relaciones para evitar errores y asegurar que el modelo fuera coherente. Esta fase fue crucial para garantizar que los datos fueran conectados correctamente y que la visualización final fuera precisa.

### 5. **Creación de Medidas con DAX**:
Con las tablas y relaciones ya creadas, se identificaron las **medidas** necesarias para responder a los requerimientos del proyecto. Utilizando **DAX (Data Analysis Expressions)**, se desarrollaron las medidas que permitirían calcular **KPI** claves, tales como:
- Inventario recomendado
- Excedente de inventario
- Ventas por mes
- Diferencia entre inventarios iniciales y finales
- Entre otras medidas clave.

Cada medida fue cuidadosamente diseñada para asegurar que los resultados fueran correctos y que las visualizaciones pudieran presentar los datos de manera clara.

### 6. **Creación de Visualizaciones y Dashboards**:
Con las medidas en su lugar, se comenzó a **diseñar las visualizaciones** necesarias para el análisis. Esto incluyó:
- **Gráficos de barras** para los **top productos en inventario**.
- **Gráficos de líneas** para las **ventas mensuales**.
- **Mapas geográficos** para el análisis **por ciudad**.
- **Gráficos de columnas apiladas** para **compras mensuales**.

Los **dashboards** fueron estructurados de manera que los **usuarios finales** pudieran interpretar fácilmente los resultados y tomar decisiones basadas en los **KPI** calculados.

### 7. **Refinamiento y Ajustes Finales**:
A lo largo del proceso de creación de los dashboards, se realizaron **ajustes finos** tanto en las visualizaciones como en las fórmulas de DAX para asegurar que los resultados fueran precisos y las visualizaciones estuvieran optimizadas. Esto incluyó cambios en el diseño de las gráficas, ajustes de colores y estilos, y pruebas de interactividad para asegurar que los dashboards fueran fáciles de usar.

---

## Conclusiones y Mejora Continua

Este proyecto ha sido una combinación de habilidades en **Power BI**, **DAX**, y **Power Query**, centrado en la optimización de la gestión de inventarios y ventas. A través de un análisis detallado de los datos y la creación de visualizaciones interactivas, se proporcionó a la empresa herramientas clave para **optimizar las compras**, **prever ventas** y **gestionar inventarios** de manera eficiente.

---
