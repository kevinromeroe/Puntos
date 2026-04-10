# Havoline Moto Club — Dashboard Distribuidores

Dashboard web para visualizar el ingreso de códigos por distribuidor semana a semana durante 2026.

## Cómo funciona

- Lee automáticamente el CSV publicado de Google Sheets cada vez que se carga la página
- No requiere backend ni base de datos
- Se actualiza solo cuando el Apps Script agrega nuevas semanas al Sheet

## Archivos

- `index.html` — el dashboard completo (renombrar desde `dashboard.html`)

## Cómo publicar en GitHub Pages

1. Crea un repositorio en GitHub (puede ser privado o público)
2. Sube el archivo `dashboard.html` y renómbralo a `index.html`
3. Ve a **Settings → Pages**
4. En **Source** selecciona `Deploy from a branch`
5. Selecciona la rama `main` y la carpeta `/ (root)`
6. Clic en **Save**
7. En unos segundos tu dashboard estará en: `https://TU_USUARIO.github.io/TU_REPO`

## Actualización automática

Cada vez que el trigger de Apps Script corra (cada lunes) y actualice Google Sheets,
el dashboard reflejará los nuevos datos automáticamente sin tocar nada en GitHub.

## Paleta de colores distribuidores

| Distribuidor | Color    |
|--------------|----------|
| COMTEXACO    | #E31837  |
| COSTAOIL     | #FF6B35  |
| OILRED       | #F5A623  |
| SAI          | #7ED321  |
| SWISSLUB     | #4A90D9  |
| DLO          | #B8B8B8  |
