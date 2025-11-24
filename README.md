# Corona
Soporte a la operación de modelos analíticos (IT). 

Este repositorio es el registro vivo de una misión técnica: demostrar la capacidad de operar, mantener y diagnosticar modelos analíticos en un entorno similar al de producción.
El reto no era “construir el mejor modelo del mundo”, sino montar un flujo funcional, rastreable y robusto, incluso dentro de las limitaciones de Databricks Community Edition. ;) 

## Proyecto de operación técnica de analitica:

Este proyecto es mezcla los siguientes temas:

- Databricks

- MLflow

- MLOps básico

- RAG

- Debugging de código

## Estructura del Repositorio

├── Notebooks/

- 01_preparacion_y_eda.dbc
- 02_entrenamiento_y_tracking.dbc
- 03_registro_y_carga_modelo.dbc
-  10_rag_ingesta_y_chunking.dbc
- 11_rag_embeddings.dbc
-  12_rag_retrieval_y_llm.dbc
-  20_escenarios_soporte.dbc
│ 
│
├── Datos/
-  telco_churn.csv
│   
│
├── Documentos Azure/
- documento_azure.pdf (Utilizado para el RAG)
│   
│
└── README.md



### ¿Cómo ejecutar los notebooks?

Accede a Databricks Community Edition.

Ve a Workspace → Import.

Importa cada archivo .dbc del repositorio.

Ejecuta los notebooks en el siguiente orden:

🔹 Parte 1 – Ciclo de vida del modelo

01_preparacion_y_eda

02_entrenamiento_y_tracking

03_registro_y_carga_modelo

🔹 Parte 2 – Sistema RAG básico

10_rag_ingesta_y_chunking

11_rag_embeddings

12_rag_retrieval_y_llm

🔹 Parte 3 – Escenarios de soporte

20_escenarios_soporte


## Reflexión final

Este proyecto muestra la capacidad de:

- Operar modelos en Databricks, incluso con restricciones.

- Rastrear, registrar y cargar modelos usando MLflow.

- Montar un pipeline RAG completo (sencillo) con recuperación real.

Diagnosticar y corregir fallas típicas de operación (schema drift, endpoints, embeddings, UDFs, MLflow).

El foco siempre fue el mismo **hacer que las cosas funcionen, sin importar las limitantes.** 

### Gracias, me lo disfruté que es lo mas importante ;)
