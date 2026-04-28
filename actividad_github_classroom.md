# Actividad: Propuesta de Práctica Temática Pequeña (Enfoque en Documentación)

## 1) Título de la práctica

**Diseño de Propuesta: Mini Proyecto de Sistemas en Terminal**

> Puedes personalizar el título final de tu propuesta. Ejemplos válidos:
> - Mini Toolkit en ARM64
> - Asistente de Estudio en Terminal
> - Reporteador de Información del Sistema
> - Organizador de Archivos
> - Juego de Aprendizaje en Línea de Comandos

---

## 2) Descripción general

En esta actividad **no se busca programar un sistema grande**, sino **diseñar y documentar** una práctica temática pequeña, realista y bien justificada para un entorno académico.

Tu tarea será construir una **propuesta completa de proyecto** que pueda desarrollarse en poco tiempo y con herramientas gratuitas.

### Objetivo principal
Que demuestres tu capacidad para:
- plantear una idea técnica clara,
- justificar su utilidad,
- estructurar un repositorio ordenado,
- y definir un plan de pruebas básico.

### Lenguaje principal (elige uno)
- ARM64 Assembly
- C
- Python
- Bash

> **Nota importante sobre ARM64 Assembly:** se recomienda **solo para programas muy pequeños** (por ejemplo: operaciones aritméticas simples, manejo básico de cadenas, o lectura/escritura mínima por consola).

### Restricciones del proyecto
Para mantener el alcance pequeño y viable:
- Evita frameworks grandes.
- Evita APIs pagadas.
- Evita bases de datos.
- Evita servicios de nube.
- Evita contenedores.
- Evita dependencias complejas.

---

## 3) Entregables del estudiante

Tu repositorio debe incluir, como mínimo:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Opcional:
- `src/`
- `scripts/`
- `tests/`

### Contenido esperado por archivo

#### `README.md`
Debe contener:
1. Nombre del proyecto.
2. Lenguaje elegido y justificación breve.
3. Problema que resuelve.
4. Alcance (qué sí hará y qué no hará).
5. Instrucciones mínimas para ejecutar (si ya hay prototipo).

#### `docs/propuesta.md`
Debe incluir:
1. Título final de la práctica.
2. Descripción breve (1–2 párrafos).
3. Objetivo general.
4. Objetivos específicos (3 a 5).
5. Entregable funcional esperado (versión mínima).
6. Estimación de complejidad (baja/media) y por qué.

#### `docs/caso_de_uso.md`
Debe incluir:
1. Contexto del usuario.
2. Actor principal.
3. Entrada esperada.
4. Proceso general.
5. Salida esperada.
6. Ejemplo concreto de uso (paso a paso).

#### `docs/estructura_repositorio.md`
Debe incluir:
1. Árbol del repositorio.
2. Propósito de cada carpeta/archivo.
3. Convenciones de nombres (archivos, scripts, pruebas).
4. Flujo de trabajo propuesto (crear, probar, documentar).

#### `docs/plan_de_pruebas.md`
Debe incluir:
1. Criterios de aceptación.
2. Casos de prueba mínimos (al menos 5).
3. Entradas de prueba.
4. Resultados esperados.
5. Cómo validar errores comunes.

---

## 4) Estructura recomendada del repositorio

Usa esta estructura mínima:

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

---

## 5) Lineamientos de alcance (muy importante)

Tu propuesta será evaluada con énfasis en que sea:
- **pequeña**, 
- **clara**,
- **bien documentada**,
- **factible de construir en poco tiempo**.

### Ejemplos de alcance correcto
- Un script Bash para organizar archivos por extensión con reporte en texto.
- Un programa en C que procese argumentos y genere un resumen básico.
- Un mini asistente en Python por terminal para estudiar comandos.
- Un programa muy pequeño en ARM64 Assembly con entrada/salida simple.

### Ejemplos de alcance incorrecto
- “Clon de red social”.
- “Sistema empresarial completo”.
- “App con frontend web + backend + base de datos + nube”.

---

## 6) Rúbrica sugerida (100 puntos)

1. **Claridad de la propuesta** (20 pts)  
   Problema, objetivo y alcance bien definidos.

2. **Justificación técnica del lenguaje** (15 pts)  
   Elección coherente con el tamaño del proyecto.

3. **Calidad del caso de uso** (20 pts)  
   Flujo lógico, entradas/salidas claras y ejemplo útil.

4. **Estructura del repositorio** (20 pts)  
   Organización limpia y mantenible.

5. **Plan de pruebas** (15 pts)  
   Casos suficientes, medibles y realistas.

6. **Calidad de redacción y formato Markdown** (10 pts)  
   Buena ortografía, claridad y orden documental.

---

## 7) Criterios de aceptación

Se considera completa la actividad si:
- Entregas todos los archivos obligatorios.
- La propuesta tiene alcance pequeño y realista.
- El caso de uso está claramente explicado.
- El plan de pruebas tiene al menos 5 casos bien definidos.
- La documentación está en Markdown claro y consistente.

---

## 8) Recomendaciones finales

- Empieza por la documentación antes de escribir código.
- Si decides programar un prototipo, manténlo mínimo.
- Prioriza funcionalidad simple y verificable.
- Evita complejidad innecesaria: menos es más en esta práctica.

---

## 9) Entrega en GitHub Classroom

Sube tu repositorio con esta estructura y contenido documental.  
El docente revisará principalmente la **calidad de la propuesta**, no la cantidad de código.
