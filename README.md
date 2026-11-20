**Título:** **Explorando drivers de comportamiento en NovaRetail+**

**¿Qué características del comportamiento de los clientes están más relacionadas con el ingreso anual que generan?** En este proyecto realicé un análisis correlacional del dataset de NovaRetail+ para explorar posibles relaciones entre las variables y traducir los hallazgos en recomendaciones de negocio.

- **Problema:** Analizar distintas variables de comportamiento sin confundir una asociación estadística con una relación causal, y distinguir las correlaciones potencialmente útiles de aquellas que podrían resultar engañosas.
- **Qué hice:** Usé Python en Jupyter Notebook para preparar y explorar los datos. Apliqué varias técnicas de correlación y utilicé gráficos de dispersión y mapas de calor para visualizar las relaciones. También documenté los supuestos y las limitaciones del análisis.
- **Resultado o aprendizaje:**
    
    **1. Compras al mes e ingreso anual**
    
    La relación entre ambas variables es muy fuerte (correlación de Pearson: **0.967**): quienes compran con mayor frecuencia suelen generar más ingresos anuales. Sin embargo, la correlación no permite determinar cuál variable impulsa a la otra.
    
    **Implicación de negocio:** usar la frecuencia de compra como una señal para identificar clientes de alto valor y ofrecerles acciones de fidelización.
    
    **2. Visitas al mes y gasto en publicidad dirigida**
    
    La relación es moderada (correlación de Pearson: **0.5789**). Un mayor gasto en publicidad dirigida se asocia con más visitas, pero otros factores también podrían influir; no se puede afirmar que la publicidad las cause.
    
    **Implicación de negocio:** complementar la publicidad dirigida con otros medios de contacto e identificar qué públicos responden mejor.
    
    **3. Tipo de dispositivo y región**
    
    La asociación entre ambas variables es muy débil (V de Cramer: **0.012378**). La distribución de dispositivos es similar entre regiones.
    
    **Implicación de negocio:** no hay evidencia clara para diseñar estrategias distintas por región; conviene priorizar una estrategia general.
    
- **¿Qué demuestra este proyecto?**
    
    Este trabajo muestra mi capacidad para integrar técnicas de análisis correlacional, comunicar patrones con visualizaciones y evaluar críticamente las limitaciones de los datos antes de proponer acciones. Las correlaciones encontradas pueden orientar investigaciones posteriores, pero no prueban por sí solas que una variable cause cambios en los ingresos.
    

**🛠️ Skills:** 

- **Jupyter Notebook**
- **Python**: `pandas`, `numpy`, `seaborn`, `matplotlib`
