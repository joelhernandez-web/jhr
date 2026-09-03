# CLAUDE.md

## Qué es este proyecto y quién lo usa

Es un dashboard de KPIs que se presentan mensualmente. Hoy es un sitio
estático (`index.html`, sin build ni dependencias) pensado como panel de
indicadores clave de desempeño, comenzando por el área de Finanzas, para
que el equipo lo consulte cada mes.

## Mi regla de verificación

Antes de dar por terminada una tarea: hago pull y despliego.

## Cómo vuelvo a abrir esto

- Repositorio: `joelhernandez-web/jhr` en GitHub, rama principal `main`.
- El sitio es HTML/CSS estático — el archivo principal es `index.html`, no
  hay build, empaquetador ni dependencias que instalar.
- Está desplegado en Netlify como **jhr-kpis-finanzas**
  (http://jhr-kpis-finanzas.netlify.app), con despliegue automático al
  hacer push a `main`. Las ramas `claude/...` generan un deploy preview
  aparte.
- Para trabajar en local: clona el repo y abre `index.html` directamente
  en el navegador (no necesita servidor).

## Sistema de diseño

- **Colores:**
  - Azul (primario): `#1f4b99`
  - Blanco (fondo / superficies): `#ffffff`
  - Naranja (acento / llamadas a la acción): `#f5821f`
- **Tipografía:** Arial, con fallback a sans-serif genérico
  (`Arial, Helvetica, sans-serif`).
