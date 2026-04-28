# Plantilla de Propuesta: Práctica Temática Pequeña

## 1) Título de la actividad
**Diseño de Propuesta para Práctica Temática de Sistemas (Mini Proyecto)**

> Ejemplos de tema (elige uno o propone uno similar):
> - “Mini Toolkit en ARM64”
> - “Asistente de Estudio en Terminal”
> - “Reporteador de Información del Sistema”
> - “Organizador de Archivos”
> - “Juego de Aprendizaje en Línea de Comandos”

---

## 2) Descripción general
En esta actividad **no se espera un proyecto grande**. Tu objetivo principal será **diseñar y documentar** una propuesta clara para una práctica temática pequeña, realista y ejecutable en poco tiempo.

Debes seleccionar **un lenguaje principal** para tu propuesta:
- ARM64 Assembly
- C
- Python
- Bash

> **Nota importante sobre ARM64 Assembly:** se recomienda únicamente para programas **muy pequeños** (por ejemplo, utilerías simples de consola, operaciones básicas con cadenas/números o manejo mínimo de entrada/salida).

### Enfoque de la actividad
Antes de escribir mucho código, debes priorizar:
1. Justificación del problema o necesidad.
2. Alcance pequeño y bien delimitado.
3. Estructura del repositorio.
4. Plan de pruebas básico y viable.
5. Claridad en documentación para que otra persona entienda cómo se desarrollará la práctica.

---

## 3) Entregables del estudiante
Tu repositorio debe incluir, como mínimo, los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

De forma opcional, puedes incluir:
- `src/`
- `scripts/`
- `tests/`

---

## 4) Estructura recomendada del repositorio
Usa esta estructura mínima sugerida:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> `<ext>` depende del lenguaje elegido (`s`, `c`, `py`, `sh`, etc.).

---

## 5) Instrucciones de desarrollo
1. Define un tema concreto y pequeño.
2. Elige el lenguaje principal según el alcance.
3. Redacta primero la documentación solicitada en `docs/`.
4. Si incluyes código, que sea mínimo y alineado a la propuesta.
5. Evita complejidad innecesaria.

### Restricciones del proyecto
Para mantener el trabajo viable con herramientas gratuitas de IA:
- Mantén el proyecto **pequeño**.
- No uses frameworks pesados.
- No uses APIs pagadas.
- No uses bases de datos.
- No uses servicios de nube.
- No uses contenedores.
- Evita dependencias complejas.

---

## 6) Contenido esperado por archivo

### `README.md`
Debe contener:
- Nombre tentativo del proyecto.
- Lenguaje principal elegido.
- Resumen de 1 párrafo del problema a resolver.
- Alcance (qué sí incluye / qué no incluye).
- Instrucciones rápidas de ejecución (aunque sean preliminares).

### `docs/propuesta.md`
Incluye secciones mínimas:
1. **Título del proyecto**
2. **Tema y contexto**
3. **Problema específico**
4. **Objetivo general**
5. **Objetivos específicos (3 a 5)**
6. **Alcance y límites**
7. **Lenguaje seleccionado y justificación técnica**
8. **Entregable funcional mínimo (MVP)**
9. **Riesgos técnicos y mitigaciones**

### `docs/caso_de_uso.md`
Describe, como mínimo:
- Actor principal (usuario objetivo).
- Escenario de uso.
- Flujo principal paso a paso.
- Entradas esperadas.
- Salidas esperadas.
- Criterios de aceptación del caso de uso.

### `docs/estructura_repositorio.md`
Debe explicar:
- Qué carpetas/archivos tendrá el repositorio.
- Responsabilidad de cada carpeta.
- Convención de nombres de archivos.
- Cómo crecería el repositorio sin perder orden.

### `docs/plan_de_pruebas.md`
Debe incluir:
- Estrategia básica de prueba (manual o scripts simples).
- Lista de casos de prueba (mínimo 5).
- Para cada caso: entrada, pasos, resultado esperado.
- Criterios para considerar “aprobada” la práctica.

---

## 7) Criterios de evaluación (rúbrica sugerida)

| Criterio | Porcentaje | Qué se evalúa |
|---|---:|---|
| Claridad de la propuesta | 25% | Problema bien definido, objetivo claro, alcance realista |
| Calidad de documentación | 30% | Organización, redacción técnica, coherencia entre archivos |
| Diseño del repositorio | 20% | Estructura lógica, nombres claros, separación de responsabilidades |
| Viabilidad técnica | 15% | Proyecto pequeño, factible con tiempo y herramientas disponibles |
| Plan de pruebas | 10% | Casos pertinentes, verificables y alineados al objetivo |

---

## 8) Checklist de entrega (para el estudiante)
Marca cada punto antes de enviar:

- [ ] Elegí un lenguaje principal (ARM64 Assembly, C, Python o Bash).
- [ ] Mi propuesta es pequeña y realista.
- [ ] Expliqué claramente el problema y el caso de uso.
- [ ] Definí alcance y límites del proyecto.
- [ ] Documenté la estructura del repositorio.
- [ ] Incluí plan de pruebas con al menos 5 casos.
- [ ] Mi README permite entender rápidamente el proyecto.

---

## 9) Recomendaciones finales
- Piensa en una herramienta que tú mismo usarías en terminal.
- Si dudas entre lenguajes, elige el que te permita **prototipar más simple**.
- Si eliges ARM64 Assembly, reduce aún más el alcance.
- La mejor propuesta no es la más grande, sino la más clara, coherente y ejecutable.
