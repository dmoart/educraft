
> **EduCraft** es una skill para [OpenCode](https://opencode.ai) que acelera la creación de proyectos educativos STEAM con inteligencia artificial. Basada en ABP (Aprendizaje Basado en Proyectos) y alineada al Marco Curricular Nacional (MCN 2022), te permite generar programas, guías docentes, memorias técnicas, presupuestos y diseños de espacios maker en segundos.

---

## ¿Por qué EduCraft?

Cada vez que arrancás un proyecto educativo nuevo —un taller de robótica, una estación de cuidado de plantas con Micro:bit, un curso de diseño 3D— terminás escribiendo la misma estructura: justificación, objetivos, metodología, evaluación, rúbricas, presupuesto, cronograma. EduCraft automatiza esa base para que te concentres en lo que importa: la calidad pedagógica y la creatividad de tus propuestas.

Usado por docentes de educación básica integrada, formación profesional y espacios maker en Uruguay.

---

## Cómo funciona

EduCraft se instala como una skill de OpenCode (el asistente de codificación con IA de código abierto). Una vez instalada, simplemente escribís el tipo de documento que necesitás y la IA lo genera completo con la estructura, el tono y los criterios de tu metodología.

```
/educraft programa         →  Programa educativo completo (tramo, grados, duración)
/educraft proyecto-aula    →  Proyecto ABP con actividades, rúbrica y conexiones interdisciplinarias
/educraft guia-docente     →  Guía docente paso a paso para el aula
/educraft memoria          →  Memoria técnica / carpeta de proyecto para estudiantes
/educraft presupuesto      →  Presupuesto detallado de materiales (nacional e internacional)
/educraft makerlab         →  Diseño e implementación de espacios de fabricación digital
```

Cada documento incluye:
- **Objetivos generales y específicos**
- **Metodología activa** (ABP, aprendizaje colaborativo, descubrimiento)
- **Asignaturas transversales** con conexiones interdisciplinarias
- **Evaluación formativa y sumativa** con rúbricas por dimensión
- **Planificación temporal** y recursos necesarios

---

## Estructura del repositorio

```
educraft/
├── skills/
│   └── educraft/
│       └── SKILL.md          # La skill instalable en OpenCode
├── ejemplos/
│   ├── programa-robotica.md   # Programa: Robótica & Videojuegos (8° EBI)
│   ├── proyecto-maceta.md     # Proyecto ABP: Estación de cuidado de plantas
│   ├── presupuesto-maker.md   # Presupuesto: materiales para makerlab
│   └── guia-makerlab.md       # Guía: diseño de espacio maker educativo
├── docs/
│   └── guia-rapida.md         # Instalación y uso en 5 minutos
├── referencias/
│   └── fuentes.md             # Documentos de referencia y metodología
├── LICENSE
└── README.md
```

---

## Instalación

### 1. Instalar OpenCode

Seguí la [guía oficial de instalación](https://opencode.ai/docs) para tu sistema operativo.

### 2. Instalar EduCraft

```bash
# Opción A — Clonar el repositorio
git clone https://github.com/TU_USUARIO/educraft.git
copy educraft\skills\educraft %USERPROFILE%\.claude\skills\educraft\

# Opción B — Manual
# Copiá skills/educraft/SKILL.md a %USERPROFILE%\.claude\skills\educraft\SKILL.md
```

### 3. Usar

Abrí OpenCode en cualquier proyecto y escribí:

```
/educraft programa para robótica con Micro:bit, tramo 5, 8° EBI, duración 6 meses
```

EduCraft carga automáticamente la skill y genera el documento completo.

---

## Ejemplo rápido

```
TÍTULO:    Programa Educativo de Robótica & Videojuegos
TRAMO:     5° / 8° EBI
DURACIÓN:  8 meses
METODOLOGÍA: ABP + Aprendizaje Activo

ETAPA 1 (4 meses): Videojuegos con Scratch/MakeCode Arcade
ETAPA 2 (4 meses): Robótica con LEGO Spike + Micro:bit

EVALUACIÓN: Formativa (fin de módulo) + Sumativa (proyecto final con rúbrica)
```

El documento completo generado incluye: introducción, justificación, objetivos, metodología detallada, evaluación con rúbrica, estructura por etapas, cronograma, entregables, recursos y bibliografía.

---

## Para quién es

- **Docentes de robótica, programación y tecnología** — generá programas y guías en minutos.
- **Coordinadores de espacios maker** — planificá la implementación de laboratorios de fabricación digital.
- **Formadores docentes** — creá materiales de capacitación con estructura pedagógica sólida.
- **Instituciones educativas** — estandarizá la presentación de proyectos bajo el MCN 2022.
- **Estudiantes de formación docente** — aprendé a estructurar proyectos educativos profesionales.

---

## Niveles educativos cubiertos

| Nivel | Hardware sugerido | Software sugerido |
|---|---|---|
| Primaria (Nivel 1-2) | LEGO WeDo 2.0 | ScratchJr, Open Roberta |
| Primaria (Nivel 3-4) | LEGO WeDo 2.0 | Scratch, Open Roberta |
| Primaria (Nivel 5-6) | Drones, Micro:bit, LEGO Spike | Open Roberta, Scratch |
| 7°-8° EBI (Tramo 5) | Micro:bit, Arduino, LEGO Spike | MakeCode, Arduino IDE |
| 9°+ / EMS | Arduino, Raspberry Pi, impresión 3D | Python, Onshape |

---

## Metodología pedagógica

- **Aprendizaje Basado en Proyectos (ABP)**
- **Aprendizaje Activo y Colaborativo**
- **Aprendizaje por Descubrimiento**
- **STEAM** — Ciencia, Tecnología, Ingeniería, Arte, Matemáticas
- **Pensamiento Computacional**
- **Evaluación Formativa + Sumativa** con rúbricas por grado

---

## Tecnología

EduCraft es una skill para [OpenCode](https://opencode.ai), el asistente de codificación con IA de código abierto que soporta más de 75 proveedores de LLM (Anthropic, OpenAI, Google, Mistral, Ollama, etc.).

Estructura | `SKILL.md` con frontmatter YAML
Licencia | MIT
Hecho con | OpenCode, Markdown, pedagogía STEAM

---

## Contribuir

¿Usás EduCraft? ¿Te gustaría agregar un tipo de documento nuevo o mejorar la metodología? Abrí un issue o mandá un PR.

---

## Licencia

MIT — usalo, modificalo, compartilo. Si te sirve, mencioná la fuente.

---

<p align="center">Hecho con ❤️ para la educación pública y la innovación pedagógica.</p>
