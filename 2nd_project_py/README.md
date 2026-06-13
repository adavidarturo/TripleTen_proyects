
# Análisis de Usuarios ConnectaTel 📊

## Descripción del proyecto
Este proyecto consiste en un análisis exploratorio de datos (EDA) de clientes de ConnectaTel con el objetivo de identificar patrones de comportamiento, segmentar usuarios y generar recomendaciones comerciales basadas en el nivel de consumo.

## Proceso realizado

### 1. Carga y preparación de datos
- Importación de datasets de usuarios y registros de uso.
- Revisión inicial de estructura, tipos de datos y valores faltantes.
- Conversión y validación de columnas de fecha.

### 2. Limpieza de datos
- Identificación y tratamiento de valores inválidos y sentinels.
- Corrección de edades con valores erróneos.
- Análisis de valores faltantes y determinación de patrones MAR/MNAR.
- Conservación de outliers cuando representaban comportamientos reales de consumo.

### 3. Análisis exploratorio
- Evaluación de variables numéricas mediante estadísticas descriptivas.
- Visualización de distribuciones con histogramas y boxplots.
- Análisis de variables categóricas como plan, ciudad y tipo de actividad.

### 4. Ingeniería de variables y segmentación
Se crearon nuevas variables para facilitar el análisis:
- `grupo_edad`: segmentación de clientes por rango etario.
- `grupo_uso`: clasificación según cantidad de llamadas y mensajes.
- Agregación del uso por usuario:
  - Total de mensajes.
  - Total de llamadas.
  - Total de minutos consumidos.

### 5. Conclusiones de negocio
El análisis permitió identificar segmentos de usuarios según comportamiento de consumo:
- Usuarios de uso medio representan la mayor parte de la base de clientes.
- Usuarios de alto uso representan una oportunidad para planes premium y estrategias de fidelización.
- Usuarios de bajo uso pueden ser objetivo de campañas para aumentar engagement.

## Tecnologías utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Resultado
Se construyó un perfil de usuario enriquecido que permite comprender patrones de consumo y apoyar decisiones relacionadas con segmentación, diseño de planes y estrategias comerciales.
