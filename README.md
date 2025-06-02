# 🧾 Mini ETL: Automatización de Reportes de Ventas

Este proyecto forma parte del eBook **"Micro ETL: crea mini pipelines de datos con Python"**, y tiene como objetivo automatizar el análisis de ventas usando Python, Pandas y Google Colab.

## 🎯 Objetivo

Automatizar el proceso de lectura, transformación y exportación de reportes de ventas semanales en Excel, reduciendo el tiempo de análisis manual a segundos.

## 🛠 Herramientas utilizadas

- Python
- Google Colab
- Pandas
- CSV (como fuente de datos)
- Excel (como salida automatizada)

## 📄 Archivos incluidos

| Archivo | Descripción |
|--------|-------------|
| `etl_ventas_colab.ipynb` | Cuaderno con el código del ETL en Google Colab |
| `ventas.csv` | Datos de ejemplo: ventas por tienda, unidades, precio |
| `reporte_final.xlsx` | Resultado final del mini ETL: resumen por tienda |

## 🧪 ¿Qué hace este proyecto?

1. **Extrae** datos desde un archivo CSV (`ventas.csv`)
2. **Transforma** los datos: calcula total por venta y agrupa resultados por tienda
3. **Carga** el resumen en un archivo Excel listo para compartir

## 🧠 Aprendizajes clave

- Uso básico de Pandas (`read_csv`, `groupby`, `to_excel`)
- Creación de columnas nuevas con operaciones
- Limpieza y ordenamiento de datos reales
- Flujo de trabajo simple de ETL para tareas de oficina o analítica junior

## 📸 Vista previa del resultado

> Puedes incluir una imagen aquí del DataFrame final o del Excel generado, si quieres.

## 📌 Cómo ejecutarlo

1. Abre el archivo `MiniProyecto_ETL_Ventas.ipynb` en [Google Colab](https://colab.research.google.com/)
2. Sube el archivo `ventas.csv` desde tu equipo
3. Ejecuta cada celda en orden
4. Descarga el archivo `reporte_final.xlsx` al final

## 👩‍💻 Autor

María Fernanda Triana — [LinkedIn](https://www.linkedin.com/in/maria-fernanda-triana/)
Este proyecto hace parte del eBook **Micro ETL**, disponible en Hotmart.

