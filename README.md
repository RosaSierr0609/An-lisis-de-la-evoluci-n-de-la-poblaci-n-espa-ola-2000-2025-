# 🇪🇸 Análisis de la evolución de la población española (2000-2025)

Proyecto de análisis de datos desarrollado con **Microsoft Fabric** y **Power BI** utilizando datos oficiales del **Instituto Nacional de Estadística (INE)**.

El objetivo del proyecto es analizar la evolución de la población española entre los años **2000 y 2025**, identificando las principales tendencias demográficas y su distribución territorial mediante un proceso completo de ingesta, transformación, modelado y visualización de datos.

---

# 📊 Dashboard

> *(Añadir aquí una captura del dashboard o un GIF del informe)*

---

# 🎯 Objetivos

- Analizar la evolución de la población española entre 2000 y 2025.
- Identificar las provincias y comunidades autónomas con mayor crecimiento y mayor pérdida de población.
- Analizar la distribución territorial de la población.
- Estudiar la evolución de la población masculina y femenina.
- Desarrollar un flujo de datos completo utilizando Microsoft Fabric.

---

# 📂 Fuente de datos

**Instituto Nacional de Estadística (INE)**

Datos oficiales de población municipal correspondientes al periodo **2000-2025**.

Los datos incluyen:

- Comunidades Autónomas
- Provincias
- Municipios
- Año
- Población total
- Población masculina
- Población femenina

---

# 🏗️ Arquitectura del proyecto

El proyecto sigue una arquitectura tipo **Medallion** implementada en Microsoft Fabric.

```text
                 INE
           Archivos Excel
                  │
                  ▼
          Dataflow Gen2
                  │
                  ▼
         Lakehouse RAW
                  │
                  ▼
       Lakehouse Bronze
        Limpieza y calidad
                  │
                  ▼
        Lakehouse Silver
      Modelo analítico limpio
                  │
                  ▼
          Modelo Estrella
                  │
                  ▼
             Power BI
```

---

# ⚙️ Proceso ETL

Durante el desarrollo del proyecto se realizaron las siguientes fases:

- Ingesta automática de los archivos del INE mediante Dataflow Gen2.
- Estandarización de provincias y municipios.
- Limpieza y transformación de datos.
- Creación del modelo dimensional.
- Desarrollo de medidas DAX.
- Construcción del dashboard interactivo.

---

# ⭐ Modelo de datos

El dashboard utiliza un modelo en estrella compuesto por:

### Tabla de hechos

- Fact_Poblacion

### Tablas dimensión

- Dim_Calendario
- Dim_Provincia
- Dim_Municipio

Este modelo facilita el análisis temporal y territorial manteniendo un rendimiento óptimo en Power BI.

---

# 📈 Dashboard

El informe está compuesto por tres páginas.

## 1️⃣ Visión general

- Evolución de la población española.
- Evolución de hombres y mujeres.
- Indicadores principales.
- Incremento porcentual de la población.

---

## 2️⃣ Análisis territorial

- Crecimiento por comunidades autónomas.
- Provincias con mayor crecimiento.
- Provincias con mayor descenso.
- Municipios con mayor incremento de población.
- Municipios con mayor pérdida de población.

---

## 3️⃣ Insights y conclusiones

Resumen de los principales hallazgos del análisis y de las limitaciones del conjunto de datos.

---

# 📌 Principales hallazgos

- La población española experimentó un crecimiento sostenido entre 2000 y 2025.
- El crecimiento poblacional no fue homogéneo entre territorios.
- Las provincias próximas a grandes áreas metropolitanas concentraron los mayores incrementos de población.
- Algunas provincias del interior continuaron perdiendo habitantes durante el periodo analizado.
- La evolución de la población masculina y femenina fue muy similar.
- El padrón permite analizar la evolución de la población residente, aunque no los flujos migratorios que explican dichos cambios.

---

# 🛠 Tecnologías utilizadas

- Microsoft Fabric
- Dataflow Gen2
- Lakehouse
- Power Query
- SQL
- DAX
- Power BI

---

# 📁 Estructura del repositorio

```
📂 Data
📂 ETL
📂 Dashboard
📂 Docs
📄 README.md
```

---

# 🚀 Posibles mejoras

- Incorporar datos oficiales de migraciones del INE.
- Añadir indicadores de natalidad y mortalidad.
- Incorporar análisis por grupos de edad.
- Implementar modelos predictivos de evolución demográfica.

---

# 👩‍💻 Autor

**Rosa Sierra**

**Data Analyst | Power BI | SQL | Python | Microsoft Fabric**

GitHub:
https://github.com/RosaSierr0609

LinkedIn:
*(Añadir enlace)*