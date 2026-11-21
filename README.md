# Borna · web

Página pública de Borna (la app está en otro repositorio, instaladores-app). HTML y CSS sin compilar.

- `index.html`: portada
- `soporte/`, `privacidad/`, `condiciones/`, `aviso-legal/`: páginas de texto (la de soporte y la de privacidad son las que pide la App Store)
- `estilo.css`: estilos comunes

**Publicar:** en Vercel, *Add New → Project*, importa este repositorio y pulsa *Deploy* (sin configurar nada).
Luego, en *Settings → Domains*, añade el dominio de Borna.

Antes de publicar, completa el NIF en `privacidad/`, `condiciones/` y `aviso-legal/` (busca `<!--NIF-->`).
