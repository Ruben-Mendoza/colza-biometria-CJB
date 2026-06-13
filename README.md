# Caracterización Química del Grano de Colza y su Relación con Variables Ambientales

> **Concurso de Jóvenes Biometristas "Susana Filippini"**  
> Grupo Argentino de Biometría (GAB)  
> Categoría: Grado  
> Autor: Rubén Alfredo Mendoza — FAMAF, Universidad Nacional de Córdoba

---

## Descripción

Análisis estadístico de la composición química del grano de colza (*Brassica napus*) y su relación con variables ambientales, a partir de un ensayo comparativo en 4 localidades de Argentina con 13 variedades (cultivares) de semillas.

**Hipótesis:** La composición química del grano de colza —en particular su contenido de ácidos grasos— está determinada no solo por el genotipo, sino también por factores ambientales (temperatura, precipitación, evapotranspiración durante el período floración–maduración).

### Variables analizadas

- Contenido de ácidos grasos: linolénicos, linoleicos, oleicos, saturados totales
- Suma total de tocoferoles (α + γ + δ)
- Índice de Estabilidad Oxidativa (OSI)
- Variables climáticas: temperatura mínima, media y máxima, precipitación y evapotranspiración durante floración–maduración

### Métodos estadísticos aplicados

- Estimación puntual de medias con distribución **t de Student** (muestras pequeñas, n=8 por cultivar)
- **ANOVA** de una y dos vías (efectos de cultivar y localidad)
- Test de hipótesis para **correlación** entre ácidos grasos y temperatura
- **Imputación de datos faltantes** con K-Nearest Neighbors (KNN)
- **Clustering no supervisado** con K-Means para agrupar cultivares por perfil químico

---

## Tecnologías y herramientas

- **Lenguaje:** Python 3
- **Bibliotecas:** `numpy`, `pandas`, `scipy`, `scikit-learn` (KNN imputación, KMeans), `matplotlib`, `seaborn`

---

## Principales hallazgos

- No se encontraron diferencias significativas entre cultivares en ácidos linolénicos ni en el Índice de Estabilidad Oxidativa.
- Sí se encontraron diferencias significativas entre cultivares en ácidos oleicos, linoleicos, saturados y tocoferoles totales.
- El **ANOVA de dos factores** mostró que la **localidad tiene mayor efecto que el cultivar** sobre la composición de ácidos grasos, con poca interacción entre ambos factores.
- No se encontró evidencia de correlación entre temperatura y niveles de ácidos linolénicos en ninguna de las 4 localidades.
- K-Means identificó **3 clusters** de cultivares con perfiles químicos diferenciados.

---

## Contexto

Trabajo presentado al **Concurso de Jóvenes Biometristas "Susana Filippini"**, organizado por el Grupo Argentino de Biometría (GAB). El concurso está orientado a estudiantes de grado y posgrado que apliquen métodos estadísticos a problemas biológicos, agronómicos o biomédicos.
