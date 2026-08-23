# DS Airlines - Predicción de Demoras y Segmentación de Clientes

Proyecto de Ciencia de Datos que predice demoras en vuelos y segmenta clientes para optimizar asignación de beneficios.

## 📌 Descripción

Análisis completo para la empresa DS Airlines que aborda dos problemas:

1. **Predicción de Demoras** (Modelos Supervisados): Identificar vuelos con probabilidad de demora para minimizar costos operativos
2. **Segmentación de Clientes** (Modelos No Supervisados): Agrupar pasajeros afectados por demoras según perfil económico para asignar beneficios estratégicamente

## 🎯 Resultados

**Modelo de Predicción (Regresión Logística):**
- Accuracy: 69.80%
- Precision: 73.80%
- Costo operativo minimizado: 4,965 m.u.

**Segmentación (K-Means, K=2):**
- Cluster 0: Pasajeros High-Value → Acceso a Sala VIP
- Cluster 1: Pasajeros Estándar → Voucher de Comida
- Silueta: 0.60 | PCA explica 64.46% de variabilidad

## 🛠️ Tech Stack

- Python: pandas, numpy, scikit-learn, matplotlib, seaborn
- IBM SPSS Statistics & SPSS Modeler
- Jupyter Notebooks
- LaTeX (Informe técnico)

## 📁 Estructura

```
├── docs/
│   └── Informe_TPI_2026.pdf          ⭐ Informe técnico completo
├── notebooks/
│   ├── 01_EDA_Vuelos.ipynb
│   ├── 02_Prediccion_Demoras.ipynb
│   ├── 03_EDA_Clientes.ipynb
│   └── 04_Clustering_Clientes.ipynb
├── requirements.txt
└── README.md
```

## 🚀 Cómo ejecutar

### Requisitos
- Python 3.10+
- Jupyter Notebook

### Instalación

```bash
git clone https://github.com/BrunoPacienzia/ds-airlines.git
cd ds-airlines

# Crear entorno virtual
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Instalar dependencias
pip install -r requirements.txt

# Ejecutar notebooks
jupyter notebook
```

## 📊 Modelos Evaluados

**Predicción de Demoras:**
- Regresión Logística ✅ (Seleccionado)
- Árbol de Decisión
- K-Nearest Neighbors
- Análisis Discriminante Lineal

**Clustering:**
- K-Means (Seleccionado)
- Clustering Jerárquico
- Clustering Bietápico
- PCA para análisis de varianza

## 📚 Lo que aprendí

- Modelado supervisado con ajuste de puntos de corte y matrices de costos
- Algoritmos no supervisados (K-Means, clustering jerárquico, PCA)
- Evaluación de modelos con múltiples métricas
- Integración de Python y SPSS para análisis completo
- Documentación técnica en LaTeX

## 👥 Equipo

Proyecto colaborativo desarrollado para Ciencia de Datos (5° año, UTN FRRo)

---

**⭐ Lee el [informe técnico completo](./Informe.pdf) para análisis detallado**
