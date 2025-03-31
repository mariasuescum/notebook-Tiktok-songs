# Exploratory Data Analysis (EDA) - Top Youtubers Dataset

## Descripción del Dataset
Este dataset contiene información sobre los 1000 canales de YouTube más populares. Incluye detalles como el número de suscriptores, vistas, cantidad de videos, categoría y año de creación.

## Pasos del Análisis
1. **Carga de Datos**
   - Se utilizó la codificación `ISO-8859-1` para evitar errores de lectura.
   
2. **Análisis de Valores Nulos**
   - Se encontró que la única columna con valores faltantes es `Category` (43 valores nulos, 4.3% del total).
   - Posibles soluciones:
     - Eliminar filas con valores nulos.
     - Rellenar con la moda (categoría más frecuente).

3. **Estadísticas Descriptivas**
   - Se analizaron medidas como media, mediana, mínimo, máximo y desviación estándar.

4. **Visualización de Datos**
   - Histogramas para entender la distribución de suscriptores y vistas.
   - Gráficos de dispersión para analizar la relación entre videos y vistas.
   - Gráficos de barras para visualizar la cantidad de canales por categoría.

## Próximos Pasos
- Decidir cómo manejar los valores nulos en `Category`.
- Explorar posibles valores atípicos en las métricas numéricas.
- Profundizar en correlaciones entre variables clave.

---


