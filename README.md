# 📊 Análisis de Rendimiento de Tiendas - Proyecto Challenge Alura Store

Este proyecto tiene como objetivo analizar el rendimiento de 4 tiendas en línea del Sr. Juan, utilizando datos de ventas extraídos desde archivos `.csv`. A través del análisis, se identifican las tiendas más rentables y se emiten recomendaciones sobre cuál tienda cerrar para mejorar el negocio, el cual esta reflejado en el informe https://github.com/jenpronet/Challenge-Alura-Store/blob/045110aacce5f5c6f31599fba346e2da9e019710/Informe_Tiendas_Juan.docx (para su visualizacion haz click en View raw).

---

## 🧠 Objetivo

Determinar cuál de las 4 tiendas debe cerrar el Sr. Juan basándose en:

- Ingresos totales.
- Productos y categorías más y menos vendidos.
- Calificaciones promedio de los clientes.
- Costos de envío promedio.
- Distribución geográfica de las ventas.

---

## 📁 Datos Utilizados

Los datos provienen de 4 archivos CSV con información de ventas:

- `tienda_1.csv`
- `tienda_2.csv`
- `tienda_3.csv`
- `tienda_4.csv`

Cada archivo contiene:
- Producto, Categoría del Producto, Precio, Costo de envío, Fecha de Compra, Calificación, Método de Pago, Coordenadas (lat/lon), entre otros.

---

## 🧰 Herramientas y Librerías Usadas

- **Python 3**
- **Pandas**: Manipulación y análisis de datos.
- **Matplotlib / Seaborn**: Visualización de gráficos.
- **Folium (opcional)**: Mapas interactivos.
- **python-docx**: Generación automática del informe en formato Word.
- **Google Colab**: Ejecución de notebooks en la nube.

---

## 📈 Análisis Realizados

- **Ingresos totales por tienda**
- **Categorías más vendidas por tienda**
- **Productos más y menos vendidos**
- **Calificaciones promedio**
- **Costo de envío promedio**
- **Distribución geográfica de las ventas** (opcional extra)

---

## 📄 Conclusiones del Informe

Tras el análisis:

- La **Tienda 2** y **Tienda 3** se destacan por sus ingresos altos, buena satisfacción del cliente y fuerte presencia geográfica.
- La **Tienda 1**, en cambio, muestra los **ingresos más bajos**, **calificaciones promedio menores**, y **productos con poca rotación**, además de una **dispersión geográfica menor**, lo que la convierte en la mejor candidata para cerrar.

✅ **Recomendación:** Cerrar la **Tienda 1** y enfocar esfuerzos en mejorar y potenciar las otras tres tiendas.

---

## 📥 Cómo usar este repositorio

1. Clona el repositorio:
   ```bash
   git clone https://github.com/jenpronet/Challenge-Alura-Store.git
   cd Challenge-Alura-Store

2. Abre el notebook en Google Colab https://colab.research.google.com/ para ejecutar el análisis completo.

3. Asegúrate de tener las librerías instaladas:
   ```bash
   !pip install pandas matplotlib seaborn
