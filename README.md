# Bunker 4 · Landing page estática

Landing page para GitHub Pages enfocada en **Bunker 4** y en la wiki de
**infraestructura clásica y avanzada**.

## Quick path

1. Abrí `index.html` localmente para revisar el diseño.
2. Publicá el repositorio con GitHub Pages desde la rama principal.
3. Verificá que el sitio cargue estilos desde `assets/css/styles.css`.

## Qué presenta el sitio

| Área | Enfoque |
|------|---------|
| Hero | Presenta Bunker 4 como espacio práctico de aprendizaje infra/DevOps |
| CTA principal | Lleva a la wiki: <https://github.com/perfeccion-ar/infraestructura-clasica-y-avanzada/wiki> |
| CTA secundaria | Lleva a la organización: <https://github.com/perfeccion-ar> |
| Temas | Linux, VPS, LXD, Docker, Kubernetes, CI/CD, Terraform, observabilidad, networking, backups, DNS y bases de datos |
| Estética | Cuaderno técnico oscuro con textura generada por CSS, sin imágenes remotas |

## Estructura

- `index.html` — landing principal lista para GitHub Pages.
- `assets/css/styles.css` — tema visual completo y responsive.
- `README.md` — guía rápida del repositorio.

## Checklist

- [x] Corregida la inconsistencia `perfeccion-ar` / `perfeccion-arse`
- [x] Sitio mantenido en archivos estáticos puros
- [x] CTA principal apuntando a la wiki correcta
- [x] Sin dependencias de build ni imágenes remotas inestables

## Publicación

Si el repositorio ya está configurado como GitHub Pages, alcanza con hacer push a
`main`. Si no, activalo desde **Settings → Pages** usando **Deploy from a branch**
y la carpeta raíz (`/`).
