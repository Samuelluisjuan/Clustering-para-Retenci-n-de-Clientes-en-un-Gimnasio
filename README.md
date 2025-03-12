# ML Clustering No Supervisado
**Analysis of Gyms and Implementation of Machine Learning for Unsupervised Clustering.**

En este proyecto, nos propusimos analizar y agrupar usuarios de un gimnasio mediante técnicas de Machine Learning no supervisado, específicamente utilizando clustering. El objetivo principal era entender la estructura de los datos de los usuarios y sus comportamientos, para identificar patrones que permitan segmentar a los usuarios de manera más efectiva.

- Análisis de Datos y Estandarización: Inicialmente, los datos fueron estandarizados para asegurar que las características se encontraran en la misma escala y no distorsionaran el modelo de clustering. Esto incluyó la normalización de variables como la frecuencia de asistencia, duración de la membresía, y las promociones activas.

Análisis Exploratorio y Visualización: Se llevó a cabo un análisis exploratorio para entender las distribuciones de las características clave y la relación entre ellas. Las matrices de correlación mostraron cómo las características como la duración de la membresía y la frecuencia de asistencia estaban correlacionadas, lo que podría influir en las decisiones de clustering. Asimismo, la creación de histogramas permitió visualizar las distribuciones de cada variable para diferentes grupos de usuarios con y sin churn.

- Clustering de Usuarios: Con los datos estandarizados y visualizados, aplicamos diferentes algoritmos de clustering para identificar grupos de usuarios con comportamientos similares:

- K-Means: Se utilizó para crear clusters basados en características como la proximidad, las promociones activas y la duración de la membresía.
DBSCAN: Fue explorado para identificar patrones más complejos, como usuarios con patrones irregulares de asistencia o aquellos que podrían considerarse como ruido en el clustering.
Resultados y Segmentación: Los resultados del clustering proporcionaron una segmentación clara de los usuarios en diferentes grupos, cada uno con características distintivas en cuanto a su frecuencia de visita y comportamiento con respecto a promociones y ofertas. Estos grupos pueden ayudar a la gestión del gimnasio a personalizar sus estrategias de marketing y retención, mejorando la experiencia del usuario y reduciendo la tasa de churn.

**Conclusiones:**
El análisis y el clustering no solo permitieron una mejor comprensión del comportamiento del usuario, sino que también proporcionaron insights valiosos para diseñar estrategias de retención y marketing más efectivas. El uso de técnicas de aprendizaje automático como K-Means y DBSCAN demostró ser una metodología efectiva para manejar datos complejos y proporcionar segmentaciones útiles.

- Futuras Líneas de Acción: Para continuar mejorando este análisis, se podría integrar más datos para enriquecer las características de los usuarios, como la frecuencia de visitas a clases específicas o el uso de servicios adicionales. Además, el modelo de clustering podría ajustarse y mejorarse con algoritmos más avanzados de aprendizaje profundo para detectar patrones aún más complejos.

