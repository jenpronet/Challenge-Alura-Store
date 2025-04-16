# 📊 Informe Final de Análisis de Tiendas - Alura Store

## 1. 🧭 Introducción

El presente informe tiene como objetivo determinar **cuál de las cuatro tiendas del Sr. Juan debe ser vendida**, con base en un análisis exhaustivo de desempeño. Se consideraron múltiples variables clave para la toma de decisión:

- Ingresos totales por tienda  
- Categorías de productos más y menos vendidos  
- Calificaciones promedio de los clientes  
- Productos más y menos vendidos  
- Costo de envío promedio

Este análisis identifica fortalezas y debilidades de cada tienda, brindando una recomendación clara y objetiva.

---

## 2. 📌 Desarrollo

### 2.1. 💰 Ingresos Totales por Tienda

| Tienda  | Ingreso Total          |
|---------|------------------------|
| Tienda 1 | $1,150,880,400.00 ✅ |
| Tienda 2 | $1,116,343,500.00     |
| Tienda 3 | $1,098,019,600.00     |
| Tienda 4 | $1,038,375,700.00 ❌ |

**➡️ Conclusión**: La Tienda 1 es la más rentable. La Tienda 4 muestra el menor ingreso.

---

### 2.2. 📦 Ventas por Categoría

Todas las tiendas comparten un patrón similar:

- **Categorías más vendidas**: Muebles y Electrónicos
- **Categorías menos vendidas**: Artículos para el hogar, Libros e Instrumentos musicales

**➡️ Conclusión**: Aunque similares, la Tienda 3 lidera en cantidad total de ventas por categoría.

---

### 2.3. 🌟 Calificación Promedio por Tienda

| Tienda  | Calificación Promedio |
|---------|------------------------|
| Tienda 1 | 3.98 ❌              |
| Tienda 2 | 4.04                 |
| Tienda 3 | 4.05 ✅              |
| Tienda 4 | 4.00                 |

**➡️ Conclusión**: Tienda 3 tiene la mejor satisfacción del cliente.

---

### 2.4. 🏆 Productos Más y Menos Vendidos

#### Más vendidos:
- **Tienda 1**: Microondas, TV LED UHD 4K, Armario
- **Tienda 2**: Iniciando en programación, Batería, Microondas
- **Tienda 3**: Kit de bancas, Mesa de comedor, Cama king
- **Tienda 4**: Cama box, Cubertería, Power BI Dashboards

#### Menos vendidos:
- Repetición de productos con baja demanda como: Guitarra eléctrica, Pandereta, Ciencia de datos con Python, Celular ABXY

**➡️ Conclusión**: Tienda 1 y 2 presentan más consistencia en sus productos top. Las demás presentan más dispersión.

---

### 2.5. 🚚 Costo de Envío Promedio

| Tienda  | Costo de Envío Promedio |
|---------|-------------------------|
| Tienda 1 | $26,018.61 ❌          |
| Tienda 2 | $25,216.24             |
| Tienda 3 | $24,805.68             |
| Tienda 4 | $23,459.46 ✅          |

**➡️ Conclusión**: Tienda 4 es la más eficiente en logística. Tienda 1 la más costosa.

---

## 3. ✅ Conclusión y Recomendación

Luego de evaluar los factores clave, se concluye que:

> ### 💡 **El Sr. Juan debería vender la Tienda 4**

### 🎯 Justificación:
- **Menor ingreso**: $1,038,375,700.00
- **Calificación promedio baja**: 4.00
- **Ventas por categoría similares**, pero no destaca
- **Costo logístico bajo**, pero no compensa los puntos anteriores

### 🏪 Tiendas a conservar:
- **Tienda 1**: Mayor ingreso total y ventas consistentes
- **Tienda 2**: Buen balance entre ingreso, satisfacción y logística
- **Tienda 3**: Mejor calificación y costos de envío competitivos

---


✅ **Recomendación:** Cerrar la **Tienda 4** y enfocar esfuerzos en mejorar y potenciar las otras tres tiendas.

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
