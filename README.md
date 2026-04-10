# Gemini Agents & Skills Hub

Este repositorio centraliza la documentación y configuración de agentes personalizados y sus habilidades para Gemini CLI.

## Estructura del Repositorio

- `skills/`: Contiene subdirectorios para cada habilidad específica. Cada habilidad debe incluir un archivo `SKILL.md`.
- `agents/`: (Opcional) Documentación sobre la configuración de agentes específicos.

## Cómo añadir una nueva Habilidad

1. Crea un nuevo directorio en `skills/nombre-de-la-habilidad`.
2. Copia el archivo `SKILL_TEMPLATE.md` en ese directorio y renómbralo a `SKILL.md`.
3. Completa la documentación de la habilidad.
4. Registra la habilidad en Gemini CLI usando la ruta absoluta del archivo `SKILL.md`.

## Registro en Gemini CLI

Para que Gemini CLI reconozca una habilidad, debe estar configurada en tu entorno. Puedes usar el comando de configuración de Gemini CLI para apuntar a los archivos `SKILL.md` en este repositorio.
