# 🏷️ Análisis Comercial de Tiendas — Proyecto Sr. Juan

Este proyecto tiene como propósito identificar cuál de las tiendas analizadas representa la menor oportunidad comercial para que el **Sr. Juan** venda sus productos.  
El trabajo fue desarrollado en **Google Colab** y los resultados se presentan en forma de gráficos y conclusiones basadas en datos reales simulados.

---

## 🎯 Objetivo del análisis

El objetivo principal fue **comparar el desempeño de cuatro tiendas** en distintos aspectos clave del negocio:

- 💰 Ingresos totales  
- 🛒 Categorías de productos más y menos vendidas  
- ⭐ Calificaciones promedio de los clientes  
- 📦 Productos más y menos vendidos  
- 🚚 Costo de envío promedio (considerando que el cliente asume este costo)

El análisis busca recomendar **la tienda menos conveniente** para vender los productos del Sr. Juan, teniendo en cuenta tanto rentabilidad como satisfacción del cliente.

---

## 📊 Datos analizados

Los datos provienen de registros de ventas de cada tienda, procesados con **pandas**.  
Cada tienda fue representada por un `DataFrame`, y se calcularon métricas clave mediante funciones de agrupamiento (`groupby`), `map`, `concat` y cálculos de promedio (`mean`, `count`).

---


### 🔍 Hallazgos destacados:

- **Tienda 1** presentó los **mayores ingresos**, pero también el **costo de envío más alto**  
- **Tienda 2 y Tienda 3** destacaron por tener **mejores calificaciones** de clientes  
- **Tienda 4** tuvo el **costo de envío más bajo**, pero los **ingresos más reducidos**

---

## 💬 Conclusión y recomendación

Tras evaluar los factores analizados, se concluye que:

> 🔹 La **Tienda 4** es la **menos conveniente** para el Sr. Juan, debido a su bajo nivel de ingresos totales, lo que refleja menor movimiento comercial.  


---

## ⚙️ Herramientas utilizadas

- 🐍 Python 3  
- 🧮 pandas  
- 📈 matplotlib  
- 💻 Google Colab  
- ☁️ Git / GitHub  



## 📘 Enlace al notebook



---

