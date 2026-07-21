# 🇪🇸 Análisis de la evolución de la población española (2000-2025)

Proyecto de análisis de datos desarrollado con **Microsoft Fabric** y **Power BI** utilizando datos oficiales del **Instituto Nacional de Estadística (INE)**.

El objetivo del proyecto es analizar la evolución de la población española entre los años **2000 y 2025**, identificando las principales tendencias demográficas y las diferencias territoriales mediante un dashboard interactivo.

---

## 📌 Objetivos

- Analizar la evolución de la población española entre 2000 y 2025.
- Identificar las provincias y comunidades autónomas con mayor crecimiento y mayor pérdida de población.
- Estudiar la evolución de la población masculina y femenina.
- Presentar los resultados mediante un dashboard interactivo que facilite la interpretación de los datos.

---

## 📊 Dataset

**Fuente oficial:**

- Instituto Nacional de Estadística (INE)

Datos utilizados:

- Población por municipios.
- Distribución por sexo.
- Evolución anual (2000-2025).

---

## 🛠 Tecnologías utilizadas

- Microsoft Fabric
- Dataflow Gen2
- Lakehouse
- Power Query
- SQL
- DAX
- Power BI

---

## ⚙️ Proceso ETL

El proyecto sigue una arquitectura basada en Microsoft Fabric:

1. Ingesta de los archivos originales del INE.
2. Limpieza y transformación de datos mediante Dataflow Gen2.
3. Estandarización de municipios y provincias.
4. Modelado en esquema estrella.
5. Creación de medidas DAX.
6. Desarrollo del dashboard en Power BI.

---

## 📈 Dashboard

El informe está compuesto por tres páginas:

### 1️⃣ Visión general

- Evolución de la población española.
- Evolución de hombres y mujeres.
- Indicadores principales.

### 2️⃣ Análisis territorial

- Crecimiento por comunidades autónomas.
- Provincias con mayor crecimiento y mayor descenso.
- Municipios con mayor incremento y pérdida de población.

### 3️⃣ Insights y conclusiones

Resumen de los principales hallazgos del análisis y limitaciones del conjunto de datos.

---

## 📌 Principales conclusiones

- La población española experimentó un crecimiento sostenido entre 2000 y 2025.
- El crecimiento no fue homogéneo entre territorios.
- Las provincias próximas a grandes áreas metropolitanas registraron los mayores incrementos poblacionales.
- Algunas provincias del interior continúan mostrando tendencias de despoblación.
- La evolución de la población masculina y femenina fue muy similar durante el periodo analizado.
- El conjunto de datos permite analizar la evolución demográfica, pero no estudiar directamente los movimientos migratorios.

---

## 📂 Estructura del proyecto

```
📁 Data
📁 ETL
📁 Power BI
📄 README.md
```

---

## 🚀 Posibles mejoras

- Incorporar datos oficiales de migraciones del INE.
- Analizar la evolución por grupos de edad.
- Incluir indicadores de natalidad y mortalidad.
- Añadir análisis predictivos mediante modelos de forecasting.

---

## 👤 Autor

**Rosa Sierra**

Data Analyst | Power BI | SQL | Python | Microsoft Fabric

GitHub: https://github.com/RosaSierr0609
