# Challenge Alura Store

## ¿Qué hace este proyecto?

Este código analiza las ventas de 4 tiendas diferentes y da una recomendación sobre en cual empezar a vender. Muestra información sobre:
- Ingresos totales por tienda
- Productos más vendidos
- Calificaciones de clientes
- Categorías de productos
- Costos de envío

## ¿Qué necesitas instalar?

Antes de ejecutar el código, instala estas librerías:

```bash
pip install pandas matplotlib numpy
```

## ¿Cómo usar el código?

1. **Descarga** el archivo con el código
2. **Abre** tu editor de Python (Jupyter, VS Code, etc.)
3. **Ejecuta** el código completo

El programa automáticamente:
- Descarga los datos de las tiendas desde internet
- Calcula todos los análisis
- Muestra gráficos con los resultados

## ¿Qué verás?

El código te mostrará:
- Gráficos de barras con ingresos por tienda
- Porcentajes de participación de cada tienda
- Productos más populares de cada tienda
- Calificaciones promedio
- Costos de envío

## Estructura de archivos

```
proyecto/
├── DATOS/                 # Repositorio de csv
│   ├── tienda_1.csv
│   ├── tienda_2.csv
│   ├── tienda_3.csv
│   └── tienda_4.csv
├── AluraStoreLatam.py     # Código principal
└── README.md              # Este archivo
```

## Posibles problemas

**Error de conexión**: Si no tienes internet, el código no funcionará porque descarga datos online.

**Librerías faltantes**: Si sale error, instala las dependencias con pip install.

**Gráficos no se ven**: Asegúrate de usar Jupyter Notebook o un entorno que muestre gráficos.

## Datos utilizados

Los datos vienen de 4 archivos CSV con información de:
- Productos vendidos
- Precios
- Calificaciones de clientes
- Categorías
- Costos de envío
