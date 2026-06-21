<div align="center">

# 🧠 Laboratorio No. 1 — Construcción de una Representación del Conocimiento

**Asignatura:** Sistemas Inteligentes  
**Universidad:** Fundación Universitaria Internacional de La Rioja  
**Fecha:** Mayo 2026

</div>

---

---

## 📋 Descripción del laboratorio

Este laboratorio corresponde a la actividad **"Construcción de una Representación del Conocimiento"**, en la cual se selecciona una actividad de la vida diaria o del dominio profesional, se construye una representación del conocimiento usando el método elegido, y se realiza una reflexión crítica sobre las **6 características fundamentales** de toda representación del conocimiento.

**Actividad elegida:** Resolver un Bug en Código  
**Método de representación:** Mapa Conceptual Estructurado (7 columnas × 8 niveles de profundidad)

---

## 🎯 Objetivos

- Construir una representación del conocimiento de una actividad real y compleja.
- Aplicar los conceptos de la Ingeniería del Conocimiento y los Sistemas Inteligentes.
- Evaluar críticamente el grado de cumplimiento de las 6 características de la representación.
- Establecer conexiones con formalismos ejecutables como CLIPS, Prolog, OWL y HTN.

---

## 🗂️ Estructura del repositorio

```
Construccion_De_Una_Representacion_Del_Conocimiento/
│
├── 📄 README.md                                          ← Este archivo
├── 📄 Laboratorio1_Representacion_Conocimiento.docx     ← Informe académico completo
└── 🌐 mapa_conceptual_debugging.html                    ← Mapa conceptual interactivo
```

---

## 📦 Archivos del proyecto

### 📄 `Laboratorio1_Representacion_Conocimiento.docx`
Informe académico completo que incluye:
- Introducción y justificación de la actividad seleccionada
- Descripción del método de representación elegido
- Representación del conocimiento con mapa conceptual (Figura 1)
- Tabla detallada de 14 pasos con conocimiento involucrado y tipo epistémico
- Taxonomía de los 10 tipos epistémicos presentes en el dominio
- Análisis completo de las 6 características con nivel de cumplimiento
- Las 10 relaciones cruzadas entre características (Tabla 5)
- Síntesis reflexiva y conclusiones
- Bibliografía académica completa

### 🌐 `mapa_conceptual_debugging.html`
Mapa conceptual interactivo desarrollado con D3.js que permite:
- Visualizar los 7 columnas × 8 niveles del mapa completo
- Zoom con scroll, desplazamiento con drag
- Click en cualquier nodo para ver descripción detallada
- Activar/desactivar las 10 relaciones cruzadas entre características
- Exportar el mapa como imagen PNG
- Leyenda integrada con código de colores, tipos de línea y niveles de cumplimiento

> **Cómo abrir:** Descarga el archivo y ábrelo con doble clic en Google Chrome o Firefox. No requiere instalación de ningún tipo.

---

## 🧩 Sobre la actividad: Resolver un Bug en Código

Se eligió esta actividad porque el **debugging** es uno de los dominios cognitivos más ricos en la ingeniería del software. A diferencia de actividades simples, involucra simultáneamente **10 tipos de conocimiento**:

| Tipo epistémico | Descripción |
|---|---|
| **Declarativo** | Hechos sobre tipos de errores y sus causas |
| **Procedimental** | Pasos para usar herramientas de depuración |
| **Heurístico** | Reglas empíricas como la Navaja de Occam |
| **Causal** | Relaciones causa-efecto entre fallo y origen |
| **Condicional** | Reglas IF-THEN según el tipo de lenguaje o error |
| **Meta-cognitivo** | Gestión del propio proceso de razonamiento |
| **Evaluativo** | Criterios de priorización de bugs |
| **Social** | Conocimiento sobre code review y trabajo en equipo |
| **Normativo** | Buenas prácticas: commits, tests, documentación |
| **Taxonómico** | Clasificación jerárquica de tipos de bugs |

---

## 📐 Estructura del mapa conceptual

El mapa conceptual fue diseñado con **7 columnas y 8 niveles de profundidad**:

```
Fila 0 → Nodo raíz: Representación del Conocimiento
Fila 1 → Las 6 Características + Relaciones Cruzadas
Fila 2 → Dimensiones de análisis de cada característica
Fila 3 → Evidencias concretas del dominio
Fila 4 → Reglas, técnicas y ejemplos aplicados
Fila 5 → Implicaciones y limitaciones detectadas
Fila 6 → Contraste con formalismos alternativos
Fila 7 → Relaciones con otras características
Fila 8 → Conclusión sintética de cada característica
```

**Columnas:**
1. ① Cobertura — `ALTO`
2. ② Comprensión por Humanos — `ALTO`
3. ③ Consistencia — `ALTO`
4. ④ Adecuación / Expresividad — `MEDIO`
5. ⑤ Eficiencia Inferencial — `BAJO`
6. ⑥ Modificación y Adquisición — `ALTO`
7. Relaciones Cruzadas entre las 6 Características

---

## 📊 Las 6 Características — Resumen

| # | Característica | Nivel | Justificación |
|---|---|---|---|
| 1 | **Cobertura** | ✅ ALTO | 8 categorías, 14 pasos, 10 tipos epistémicos |
| 2 | **Comprensión por Humanos** | ✅ ALTO | Lenguaje natural del dominio, validable por desarrolladores senior |
| 3 | **Consistencia** | ✅ ALTO | Orden lógico, ciclos de retroalimentación semánticamente correctos |
| 4 | **Adecuación / Expresividad** | 🟡 MEDIO | Cubre procedimental, heurístico y causal (~75%); no cubre probabilístico ni analógico |
| 5 | **Eficiencia Inferencial** | 🔴 BAJO | No ejecutable directamente; requiere migración a CLIPS/Prolog/OWL/HTN |
| 6 | **Modificación y Adquisición** | ✅ ALTO | Modular, extensible, ciclo de adquisición 5-10x más rápido que formalismos ejecutables |

---

## 🔗 Las 10 Relaciones Cruzadas entre Características

| Desde | Hacia | Relación |
|---|---|---|
| ① Cobertura | ④ Adecuación | Tensión |
| ① Cobertura | ⑤ Eficiencia | Fundamento |
| ② Comprensión | ③ Consistencia | Favorece |
| ② Comprensión | ⑥ Modificación | Facilita |
| ③ Consistencia | ⑤ Eficiencia | Habilita |
| ④ Adecuación | ⑤ Eficiencia | **Determina** (más crítica) |
| ④ Adecuación | ① Cobertura | Amplía |
| ⑥ Modificación | ① Cobertura | Mantiene |
| ⑥ Modificación | ③ Consistencia | Preserva |
| ⑤ Eficiencia | ③ Consistencia | Detecta |

---

## 🚀 Formalismos ejecutables alternativos

Para transformar el mapa conceptual en un sistema ejecutable:

| Formalismo | Herramientas | Tipo de conocimiento |
|---|---|---|
| Reglas de producción | CLIPS · Drools | Condicional · Procedimental |
| Lógica de 1er orden | Prolog · Datalog | Causal · Taxonómico |
| Ontología formal | OWL · RDF · Protégé | Taxonómico · Declarativo |
| Planificador HTN | SHOP2 · JSHOP2 | Procedimental completo |
| Red Bayesiana | Netica · GeNIe | Probabilístico |
| Case-Based Reasoning | jCOLIBRI · FreeCBR | Analógico |

---

## 📚 Bibliografía principal

- Russell, S., & Norvig, P. (2021). *Artificial Intelligence: A Modern Approach* (4th ed.). Pearson.
- Sowa, J. F. (2000). *Knowledge Representation: Logical, Philosophical, and Computational Foundations*. Brooks/Cole.
- Brachman, R. J., & Levesque, H. J. (2004). *Knowledge Representation and Reasoning*. Morgan Kaufmann.
- Giarratano, J., & Riley, G. (2005). *Expert Systems: Principles and Programming* (4th ed.). Thomson.
- Gruber, T. R. (1993). A translation approach to portable ontology specifications. *Knowledge Acquisition*, 5(2), 199–220.
- Material académico de la asignatura Sistemas Inteligentes — UNIR, enero 2026.

---

## 👨‍💻 Autor

**Alejandro De Mendoza Tovar**  
Ingeniero Informático / Especialista IA / Máster Arquitectura Software / 
Fundación Universitaria Internacional de La Rioja  
GitHub: [@AlejoTechEngineer](https://github.com/AlejoTechEngineer)

---

*Laboratorio No. 1 — Sistemas Inteligentes — Mayo 2026*
