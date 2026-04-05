# Análisis de Datos - ConnectaTel

## 📋 Descripción del Proyecto
Análisis exploratorio y de segmentación de clientes de una empresa de telecomunicaciones en Latinoamérica (ConnectaTel).  
Se trabajó con tres datasets: planes, usuarios y uso real de llamadas y mensajes.

### 🎯 Objetivos
- Explorar y limpiar los datos
- Construir un perfil estadístico de los clientes
- Detectar comportamientos atípicos (outliers)
- Crear segmentos de clientes por edad y nivel de uso
- Generar insights accionables para estrategias de retención y mejora de planes

## 📊 Datasets Utilizados
- `plans.csv` → Información de los planes (Basico y Premium)
- `users_latam.csv` → Datos demográficos y de registro de clientes
- `usage.csv` → Uso real de llamadas y mensajes

## 🛠️ Etapas del Análisis
1. Carga y exploración inicial
2. Identificación y corrección de problemas de calidad de datos
3. Limpieza de sentinels y fechas imposibles
4. Agregación de uso por usuario
5. Visualización de distribuciones y detección de outliers
6. Segmentación de clientes (por uso y por edad)
7. Insights ejecutivos y recomendaciones de negocio

## 🚀 Cómo ejecutar el notebook
1. Abrir el archivo `S7 Version-Estudiante-Project-ConnectaTel.ipynb` en **Google Colab** o **Jupyter Notebook**
2. Asegurarse de que los archivos CSV estén en la carpeta `/datasets/`
3. Ejecutar las celdas en orden

## 📈 Hallazgos Principales
- La mayoría de clientes son adultos con alto nivel de uso.
- Los usuarios del plan **Premium** muestran mayor consumo de mensajes y minutos.
- Se identificaron usuarios "heavy users" (outliers) que representan alto valor para la empresa.
- Oportunidad clara de crear un plan orientado a jóvenes.

## 💡 Recomendaciones de Negocio
- Desarrollar un **plan Joven** más accesible y enfocado en mensajería.
- Implementar estrategias de up-selling para clientes de uso medio.
- Diseñar campañas de retención para clientes de alto uso.
- Mejorar la captura de datos de ciudad para análisis geográficos futuros.

---

**Proyecto realizado como parte del Sprint 7 - Análisis de Datos**

Autor: JAVIER RAMOS RIVERA
Fecha: Abril 2026
