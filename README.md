# Mitigación de sesgo con Exponentiated Gradient Reduction

Proyecto final de **Regulación y Ética en IA** (UPB, 2026). Implementa la técnica *Exponentiated Gradient Reduction*
(Agarwal et al., 2018, ICML) con [Fairlearn](https://fairlearn.org) sobre el dataset **Adult Census Income**, y analiza
la discriminación por **sexo, raza, interseccionalidad (sexo × raza) y edad**, junto con su encuadre en el **EU AI Act**.

## Contenido

| Archivo | Descripción |
|---|---|
| `Proyecto_Final_Exponentiated_Gradient.ipynb` | Notebook completo: decisiones de diseño, EDA, baseline, mitigación, robustez, análisis multi-eje y conclusiones |
| `Informe_Proyecto_Final_Exponentiated_Gradient.docx` | Informe escrito (marco teórico, metodología, resultados, análisis ético-regulatorio) |
| `Presentacion_Exponentiated_Gradient.pptx` | Presentación final (20 min) con notas del orador |
| `figuras/` | Gráficas generadas por el notebook |
| `*.csv` | Tablas de resultados exportadas por el notebook |

## Ejecutar

```bash
pip install -r requirements.txt
jupyter notebook Proyecto_Final_Exponentiated_Gradient.ipynb
```

Requiere conexión a internet (descarga Adult desde OpenML). La ejecución completa tarda ~20 minutos.

## Autor

Luis Seoanes — Ciencia de Datos, Universidad Pontificia Bolivariana.
