# 📊 Reporte de Ventas TechZone 2025 – Power BI

Dashboard interactivo en **Power BI** que analiza las ventas de 2025 de TechZone, una tienda de componentes y periféricos de computadora. Permite ver de un vistazo cuánto se vendió, qué productos y ciudades lideran, y qué canal funciona mejor.

![Dashboard TechZone](dashboard.png)

## 🎯 Objetivo

Convertir los datos de ventas en un reporte visual que ayude a responder:

- ¿Cuánto se vendió en 2025 y cómo evolucionaron los ingresos mes a mes?
- ¿Cuál es el producto estrella?
- ¿Qué ciudades generan más ingresos?
- ¿Se vende más por canal online o en tienda física?
- ¿Qué pesa más: componentes o periféricos?

## 🛠️ Herramientas

- **Power BI Desktop**
- **Excel** (fuente de datos)

## 🗃️ Datos

El archivo `ventas_perifericos_2025.xlsx` contiene **1,311 registros** de ventas con estas columnas:

| Columna | Descripción |
|---|---|
| `Fecha` | Fecha de la venta |
| `ID_venta` | Identificador de la venta |
| `Producto` | Nombre del producto |
| `Categoría` | Componentes o Periféricos |
| `Subcategoría` | Mouse, SSD, RAM, etc. |
| `Precio_unitario` | Precio por unidad |
| `Cantidad` | Unidades vendidas |
| `Ingreso_total` | Precio × cantidad |
| `Cliente_ID` | Identificador del cliente |
| `Ciudad` | Ciudad de la venta |
| `Canal_venta` | Online o Tienda física |

## 📈 Contenido del dashboard

- **Tarjetas (KPI):** producto estrella y total de ventas 2025 (17 millones).
- **Ingresos por mes:** evolución mensual de las ventas.
- **Cantidad de productos vendidos:** gráfico de anillo por producto.
- **Ingreso total por ciudad:** ranking de ciudades.
- **Ventas por canal:** online vs. tienda física.
- **Ingreso total por producto:** productos que más facturan.
- **Ventas por categoría:** componentes vs. periféricos.
- **Segmentador de mes:** filtra todo el dashboard por mes.

## 🔎 Hallazgos principales

- Las ventas totales de 2025 llegaron a **17 millones**.
- Los ingresos tienen tendencia al alza, con su punto más alto en **diciembre**.
- **Lima** es la ciudad que más ingresos genera, seguida de Arequipa y Trujillo.
- El canal **online** concentra el **53.24%** de las ventas y la tienda física el 46.76%.
- Los **componentes** representan el **55.15%** de los ingresos y los periféricos el 44.85%.
- La **GPU NVIDIA RTX 4070** es el producto que más ingresos genera.

## 📂 Archivos

```
├── TechZone.pbix                     # Dashboard de Power BI
├── ventas_perifericos_2025.xlsx      # Datos de ventas
├── dashboard.png                     # Captura del dashboard
└── README.md
```

## ▶️ Cómo abrirlo

1. Descarga el repositorio.
2. Abre `TechZone.pbix` con **Power BI Desktop** (gratuito).
3. Si te pide actualizar la fuente de datos, apunta a `ventas_perifericos_2025.xlsx`.

## 👤 Autor

Frank – [GitHub](https://github.com/frankboz)
