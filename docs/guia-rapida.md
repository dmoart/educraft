# Guía Rápida — EduCraft

## Instalación en 2 pasos

### 1. Instalar OpenCode

```bash
# Windows (PowerShell)
curl -fsSL https://opencode.ai/install | bash

# Verificar instalación
opencode --version
```

### 2. Instalar EduCraft

```bash
# Clonar el repositorio y copiar la skill
git clone https://github.com/dmoart/educraft.git

# Copiar al directorio de skills de OpenCode
copy educraft\skills\educraft %USERPROFILE%\.claude\skills\educraft\
```

## Uso

Abrí OpenCode en cualquier carpeta y escribí:

### Programa educativo
```
/educraft programa para robótica con Arduino, tramo 5, 8° EBI, duración 6 meses
```

### Proyecto de aula
```
/educraft proyecto-aula para estación meteorológica con Micro:bit, 7° EBI, 3 meses
```

### Guía docente
```
/educraft guia-docente para proyecto de videojuegos con Scratch, 5° primaria
```

### Memoria técnica
```
/educraft memoria para proyecto de maceta inteligente, integrantes: 4 estudiantes
```

### Presupuesto
```
/educraft presupuesto para kit de robótica, 30 estudiantes, USD y moneda local
```

### Espacio maker
```
/educraft makerlab para secundaria, 40 estudiantes, expansión gradual
```

## Tips

- **Sé específico con el grado/nivel** — la skill ajusta contenidos y rúbricas automáticamente.
- **Mencioná la duración** — los cronogramas se generan acorde.
- **Si trabajás con presupuesto, indicá moneda** — la skill genera tablas separadas.
- **EduCraft se basa en ABP y MCN 2022** — los documentos mantienen coherencia pedagógica.

## Personalización

EduCraft es un archivo SKILL.md. Podés editarlo para:

- Agregar tus propios tipos de proyecto.
- Cambiar las dimensiones de las rúbricas.
- Ajustar los niveles educativos a tu sistema.
- Incorporar bibliografía específica de tu área.
