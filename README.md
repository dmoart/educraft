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
│   ├── programa-microbit-completo.md  # [MEGA] Programa Micro:bit completo con todo
│   ├── proyecto-auto-solar.md     # [NUEVO] Proyecto ABP: auto solar para 7° EBI
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

**Daniel Morisio** es docente de innovación educativa en Uruguay, especializado en el diseño de experiencias de aprendizaje que integran tecnología, creatividad, ciencia y cultura maker. Su trabajo se centra en transformar ideas en proyectos educativos reales, vinculando robótica, programación, diseño 3D, inteligencia artificial, pensamiento computacional y tecnologías espaciales.

Desarrolla propuestas alineadas al Marco Curricular Nacional (MCN 2022), con un enfoque basado en Aprendizaje Basado en Proyectos, resolución de problemas, experimentación y construcción de soluciones funcionales. A través de sus proyectos, promueve que los estudiantes investiguen, diseñen, construyan, prueben y mejoren sus propias creaciones, fortaleciendo habilidades vinculadas a la creatividad, el trabajo colaborativo, la comunicación, la autonomía y la innovación.

Desde su perfil como referente en educación tecnológica y aeroespacial, ha sido convocado por el Centro de Investigación y Divulgación Aeroespacial —CIDAE— por su trabajo en propuestas educativas vinculadas a ciencias del espacio, cohetería experimental, sondas meteorológicas, CubeSat y tecnologías aplicadas al aprendizaje. Además, es miembro de ACEMU, la Asociación Uruguaya de Cohetería Experimental.

Entre sus logros más destacados se encuentra el lanzamiento, desde el centro de Montevideo, de una sonda meteorológica desarrollada por estudiantes de secundaria, considerada la primera experiencia de este tipo en Sudamérica dentro del contexto educativo. El proyecto constituyó un hito por su complejidad técnica, logística y operativa, integrando cálculos de trayectoria, diseño, construcción, lanzamiento, seguimiento, recuperación y validación de funcionamiento real.

Su perfil combina innovación educativa, conocimiento técnico y capacidad de gestión de proyectos, con una mirada orientada a generar experiencias significativas donde la tecnología no sea solo una herramienta, sino un medio para aprender, crear, resolver problemas y producir impacto educativo.

- GitHub: [@dmoart](https://github.com/dmoart)

---

## Contribuir

¿Usás EduCraft? ¿Te gustaría agregar un tipo de documento nuevo o mejorar la metodología? Abrí un issue o mandá un PR.

---

## Licencia

MIT — usalo, modificalo, compartilo. Si te sirve, mencioná la fuente.

---

<p align="center">Hecho con ❤️ para la educación pública y la innovación pedagógica.</p>
