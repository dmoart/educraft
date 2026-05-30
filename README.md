<p align="center">
  <img src="assets/banner.svg" alt="EduCraft Banner">
</p>

<p align="center">
  <strong>EduCraft</strong> es una skill para <a href="https://opencode.ai">OpenCode</a> que acelera la creación de proyectos educativos STEAM con inteligencia artificial.
  Basada en <strong>ABP</strong> (Aprendizaje Basado en Proyectos) y alineada al <strong>Marco Curricular Nacional (MCN 2022)</strong>,
  genera programas, guías docentes, memorias técnicas, presupuestos y diseños de espacios maker en segundos.
</p>

---

## ¿Por qué EduCraft?

Cada vez que arrancás un proyecto educativo nuevo —un taller de robótica, una estación de cuidado de plantas con Micro:bit, un curso de diseño 3D— terminás escribiendo la misma estructura: justificación, objetivos, metodología, evaluación, rúbricas, presupuesto, cronograma. EduCraft automatiza esa base para que te concentres en lo que importa: la **calidad pedagógica** y la **creatividad** de tus propuestas.

Usado por docentes de educación básica integrada, formación profesional y espacios maker en Uruguay.

---

## Cómo funciona

EduCraft se instala como una skill de OpenCode. Una vez instalada, escribís el tipo de documento que necesitás y la IA lo genera completo con tu metodología.

```
/educraft programa         →  Programa educativo completo (tramo, grados, duración)
/educraft proyecto-aula    →  Proyecto ABP con actividades, rúbrica y conexiones interdisciplinarias
/educraft guia-docente     →  Guía docente paso a paso para el aula
/educraft memoria          →  Memoria técnica / carpeta de proyecto para estudiantes
/educraft presupuesto      →  Presupuesto detallado de materiales (nacional e internacional)
/educraft makerlab         →  Diseño e implementación de espacios de fabricación digital
```

Cada documento incluye objetivos, metodología activa, asignaturas transversales, evaluación con rúbrica, planificación temporal y recursos.

---

## Estructura del repositorio

```
educraft/
├── assets/
│   └── banner.svg                # Banner del proyecto
├── skills/
│   └── educraft/
│       └── SKILL.md              # La skill instalable en OpenCode
├── ejemplos/
│   ├── programa-robotica.md      # Programa: Robótica & Videojuegos (8° EBI)
│   ├── proyecto-maceta.md        # Proyecto ABP: Estación de cuidado de plantas
│   └── guia-makerlab.md          # Guía: diseño de espacio maker educativo
├── docs/
│   └── guia-rapida.md            # Instalación y uso en 5 minutos
├── referencias/
│   └── fuentes.md                # Documentos de referencia y metodología
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
git clone https://github.com/dmoart/educraft.git
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

| | |
|---|---|
| Estructura | `SKILL.md` con frontmatter YAML |
| Licencia | MIT |
| Hecho con | OpenCode, Markdown, pedagogía STEAM |

---

## Acerca del autor

**Daniel Morisio** es docente de innovación educativa en Uruguay, especializado en robótica, programación, diseño 3D y espacios maker. Creador de programas educativos bajo el Marco Curricular Nacional (MCN 2022) y formador de docentes en tecnología educativa.

Su enfoque combina **Aprendizaje Basado en Proyectos**, **pensamiento computacional** y **cultura maker** para transformar la experiencia de aprendizaje en el aula.

- GitHub: [@dmoart](https://github.com/dmoart)

---

## Contribuir

¿Usás EduCraft? ¿Te gustaría agregar un tipo de documento nuevo o mejorar la metodología? Abrí un issue o mandá un PR.

---

## Licencia

MIT — usalo, modificalo, compartilo. Si te sirve, mencioná la fuente.

---

<p align="center">Hecho con ❤️ para la educación pública y la innovación pedagógica.</p>
