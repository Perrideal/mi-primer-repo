# Skills de Claude localizadas

Estas cinco skills coinciden con los nombres o las descripciones de la imagen. Los enlaces llevan a sus fuentes originales; este repositorio las cataloga y deja los comandos listos para instalarlas en un proyecto de Claude Code.

Para instalar una skill, ejecuta su comando desde la carpeta del proyecto. El CLI `npx skills` requiere Node.js 22.20 o posterior.

## 1. Agent Browser — Vercel Labs

Automatización del navegador: abrir páginas, navegar, hacer clic, extraer información y probar interfaces.

- [Marketplace](https://skills.sh/vercel-labs/agent-browser/agent-browser)
- [Repositorio original](https://github.com/vercel-labs/agent-browser)
- Instalar: `npx skills add https://github.com/vercel-labs/agent-browser --skill agent-browser -a claude-code`
- También requiere el CLI de navegador: `npm install -g agent-browser`; la primera vez, `agent-browser install` descarga Chrome for Testing.

## 2. MCP Builder — Anthropic

Guía para diseñar y construir servidores MCP que conectan Claude con servicios externos. La fuente oficial incluye implementación y evaluación con TypeScript o Python; no es un conector sin código.

- [Marketplace](https://skills.sh/anthropics/skills/mcp-builder)
- [Repositorio original](https://github.com/anthropics/skills/tree/main/skills/mcp-builder)
- Instalar: `npx skills add https://github.com/anthropics/skills --skill mcp-builder -a claude-code`

## 3. UI/UX Pro Max — NextLevelBuilder

Asistencia de diseño de interfaces con más de 50 estilos visuales activos y combinaciones de tipografías, además de pautas UX.

- [Marketplace](https://skills.sh/nextlevelbuilder/ui-ux-pro-max-skill/ui-ux-pro-max)
- [Repositorio original](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)
- Instalar: `npx skills add https://github.com/nextlevelbuilder/ui-ux-pro-max-skill --skill ui-ux-pro-max -a claude-code`

## 4. Web Design Guidelines — Vercel Labs

Revisa interfaces web con más de 100 reglas de accesibilidad, rendimiento y UX.

- [Marketplace](https://skills.sh/vercel-labs/agent-skills/web-design-guidelines)
- [Repositorio original](https://github.com/vercel-labs/agent-skills/tree/main/skills/web-design-guidelines)
- Instalar: `npx skills add https://github.com/vercel-labs/agent-skills --skill web-design-guidelines -a claude-code`

**Nota sobre “Berserk” en la imagen:** no encontré una skill de diseño de Berserk que coincida con esa descripción. La coincidencia por las más de 100 reglas es la skill de Vercel enlazada arriba; el repositorio de [Berserk Skills](https://github.com/berserkdb/berserk-skills) trata sobre logs, trazas y métricas.

## 5. Find Skills — Vercel

Busca skills del ecosistema según lo que quieres construir y ayuda a instalarlas.

- [Marketplace](https://skills.sh/vercel-labs/skills/find-skills)
- [Repositorio original](https://github.com/vercel-labs/skills)
- Instalar: `npx skills add https://github.com/vercel-labs/skills --skill find-skills -a claude-code`

---

Las skills y sus dependencias se mantienen en los repositorios originales; este README conserva los enlaces y comandos de instalación.
