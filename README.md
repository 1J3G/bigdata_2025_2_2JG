## 1️⃣ Descripción General

Este proyecto tiene como propósito **diseñar y analizar una base de datos analítica** a partir del *Grocery Sales Dataset* disponible en Kaggle.  
El objetivo principal es **comprender los factores que influyen en las ventas** de una empresa de distribución, identificando los productos, categorías, ubicaciones, clientes y empleados que generan mayores ingresos.

---

## 2️⃣ Planteamiento del Problema

La empresa **Distribuciones J3Gs** desea conocer qué productos, categorías y ubicaciones generan mayores ventas y cómo influyen los clientes y empleados en los resultados.  
Actualmente dispone de una gran cantidad de datos transaccionales, pero no ha realizado un estudio que permita **detectar patrones de comportamiento, tendencias de compra ni métricas de desempeño**.  


---

## 3️⃣ Dataset Utilizado

**Fuente:** [Grocery Sales Dataset – Kaggle](https://www.kaggle.com/datasets/andrexibiza/grocery-sales-dataset)  

Este conjunto de datos contiene información sobre:
- Transacciones de ventas (`Sales`)
- Productos y categorías (`Products`, `Categories`)
- Clientes y empleados (`Customers`, `Employees`)
- Ubicación geográfica (`Cities`, `Countries`)

---

## 4️⃣ Variables más Relevantes

| Tipo | Variables clave | Utilidad |
|------|------------------|-----------|
| **Ventas** | `TotalPrice`, `SaleDate` | Permiten medir el nivel y frecuencia de ventas. |
| **Productos y Categorías** | `ProductName`, `CategoryID`, `Price` | Identifican los artículos más rentables. |
| **Clientes** | `CustomerID`, `CityID` | Facilitan el análisis de comportamiento por región. |
| **Empleados** | `SalesPersonID`, `HireDate` | Permiten evaluar el desempeño individual. |
| **Ubicación** | `CityName`, `CountryName` | Analizan las zonas con mayor volumen de ventas. |

---

## 5️⃣ Modelo Entidad–Relación (ER)

El modelo ER refleja la estructura de la base de datos relacional construida para el análisis.  
Las entidades principales son **Sales**, **Products**, **Customers**, **Employees**, **Cities** y **Countries**.  
Cada venta se relaciona con un producto, cliente, empleado y ciudad, permitiendo consultas integradas y análisis multidimensional.

📎 *Archivo adjunto:* `modelo_ER.png`

---

## 6️⃣ Desarrollo y Metodología

El proyecto se desarrolló en **Python**, empleando librerías como:

- **SQLite3 / MySQL** → Para la gestión de la base de datos.  
- **Pandas** → Para manipulación y análisis de datos.   

Además, se implementaron scripts para:
1. **Conexión y exploración de tablas.**
2. **Consulta de registros mediante bucles SQL.**
3. **Visualización de estructuras y relaciones.**
4. **Extracción de insights y exportación a CSV.**

---

## 7️⃣ Resultados Esperados

- Identificar los **productos y categorías más vendidos**.  
- Detectar **patrones de compra por ciudad o país**.  
- Evaluar **el rendimiento de los empleados en ventas**.  
- Obtener indicadores útiles para la **toma de decisiones estratégicas**.

---

## 8️⃣ Conclusión
  
En definitiva, demuestra cómo una base de datos correctamente estructurada puede ser la base para el **análisis inteligente de la información**.
