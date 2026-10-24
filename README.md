# Ahorra energía en casa — EA1

Sitio web académico desarrollado en HTML5 y Bootstrap 5.3 para analizar el consumo de energía de un hogar
y proponer acciones de ahorro. El proyecto es parte del curso de Ingeniería Web I de la IU Digital de Antioquia.

## Estructura del sitio

El sitio está compuesto por cinco páginas enlazadas mediante un menú de navegación común:

- `index.html` — Introducción al consumo eléctrico, el efecto de El Niño y el precio de bolsa.
- `equipos.html` — Inventario de equipos con el cálculo del consumo semanal y las etiquetas de potencia.
- `mi-factura.html` — Historial de consumo, comparación entre la proyección y la factura, y recomendaciones.
- `encuesta.html` — Formulario de hábitos de consumo enviado por el método GET.
- `registro.html` — Formulario para registrar los datos técnicos de un equipo.

## Fórmulas de cálculo

- Consumo semanal (kWh): `(W × horas/día entre semana × 5 + W × horas/día fin de semana × 2) / 1000`
- Costo semanal (COP): `kWh semanal × tarifa (COP/kWh)`
- Proyección mensual (kWh): `kWh semanal × 30 / 7`

## Tecnologías

- HTML5 con etiquetas semánticas (`header`, `nav`, `main`, `section`, `footer`).
- Bootstrap 5.3 mediante CDN, con componentes como `card`, `alert` y `badge`.
- Hoja de estilos propia en `css/estilos.css` con una paleta verde (tema de energía),
  encabezado con degradado, tarjetas con sombra y realce de tablas y formularios.
- Formularios HTML con validación nativa (`required`, `min`, `max`, `maxlength`).

## Publicación

El sitio se publica en GitHub Pages desde un repositorio público llamado `ahorra-energia`.
Las cinco páginas se validan en el [servicio de validación del W3C](https://validator.w3.org/nu/).
