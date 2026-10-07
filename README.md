# 2.1.2 Coeficiente de Correlación de Spearman (ρ)

**Asignatura:** Análisis y visualización de datos (GAD-2401)  
**Carrera:** Ingeniería Informática  
**Institución:** Tecnológico de Estudios Superiores de Chalco  

---

## Descripción

Sitio web educativo (HTML) + práctica en Jupyter Notebook sobre el **Coeficiente de correlación de rangos de Spearman**.

Ideal para publicar en **GitHub Pages**.

## Estructura

```
tema-2.1.2-spearman-html/
├── index.html
├── 01-introduccion.html
├── 02-formula-y-calculo.html
├── 03-interpretacion.html
├── 04-propiedades.html
├── 05-ejemplos.html
├── css/estilos.css
├── ejercicios/
│   └── ejercicios-manuales.html
├── practica/
│   └── practica_spearman.ipynb
├── requirements.txt
└── README.md
```

## Cómo ver las páginas HTML

- **Local:** abre `index.html` en el navegador.
- **GitHub Pages:** Settings → Pages → rama `main`, carpeta `/ (root)`.

## Práctica en Jupyter

1. Descarga `practica/practica_spearman.ipynb`.
2. Ábrelo en Google Colab, VS Code o Jupyter local.

```bash
pip install -r requirements.txt
jupyter notebook practica/practica_spearman.ipynb
```

## Flujo recomendado

1. Leer teoría HTML (páginas 1 → 5).
2. Resolver ejercicios manuales en el cuaderno.
3. Verificar con el notebook.
4. Completar ejercicios adicionales del notebook.

## Relación con 2.1.1 (Pearson)

| Aspecto | Pearson | Spearman |
|---------|---------|----------|
| Relación | Lineal | Monótona |
| Datos | Valores | Rangos |
| Outliers | Sensible | Robusto |
| Normalidad | Deseable | No requiere |

---

**Material generado para GAD-2401 · Uso educativo · 2026**
