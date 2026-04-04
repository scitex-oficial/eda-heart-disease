# EDA · Heart Disease UCI
### Análisis Exploratorio de Datos con Python y Seaborn
**by SciTeX · Manuel Merino** · #PensarConDatos

---

## Descripción

Serie de visualizaciones sobre el dataset **Heart Disease UCI** 
(Cleveland, n=303) explorando las variables clínicas que 
discriminan entre pacientes con y sin enfermedad cardíaca.

Cada gráfico fue publicado como contenido educativo en LinkedIn 
bajo la cuenta de [SciTeX](https://www.linkedin.com/company/scitexoficial).

---

## Dataset

**Fuente:** [UCI Machine Learning Repository — Heart Disease](https://archive.ics.uci.edu/dataset/45/heart+disease)

**Variables principales:**

| Variable | Descripción |
|---|---|
| `age` | Edad en años |
| `sex` | Sexo (1=hombre, 0=mujer) |
| `cp` | Tipo de dolor en el pecho |
| `trestbps` | Presión arterial en reposo (mmHg) |
| `chol` | Colesterol sérico (mg/dl) |
| `thalach` | Frecuencia cardíaca máxima (lpm) |
| `oldpeak` | Depresión del segmento ST |
| `exang` | Angina inducida por esfuerzo |
| `target` | Diagnóstico (1=con enfermedad, 0=sin enfermedad) |

---

## Gráficos

### 01 · Frecuencia Cardíaca Máxima por Diagnóstico
Histograma con curva de densidad comparando la distribución 
de `thalach` entre pacientes con y sin enfermedad cardíaca.

![thalach histplot](outputs/thalach_histplot_componente.svg)

---

## Instalación
```bash
pip install pandas numpy matplotlib seaborn ucimlrepo
```

---

## Uso

Abre el notebook en la carpeta `notebooks/` y ejecuta 
las celdas en orden. El dataset se descarga automáticamente 
desde el UCI repository.

---

## Autor

**Manuel Merino** — Especialista en Business Analytics  
[LinkedIn personal](https://www.linkedin.com/in/tu-perfil) · 
[SciTeX](https://www.linkedin.com/company/scitexoficial)

---

## Licencia

MIT License — libre para usar y adaptar con atribución.
