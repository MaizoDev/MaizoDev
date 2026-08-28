# Leonardo Maizo Alemán

Desarrollador Android (Kotlin) y web. Último año de Ingeniería en Informática en IACC, Chile.

Trabajo en producción: mantengo el sitio y la analítica de un centro de imagenología médica, y construyo aplicaciones con Kotlin, React y Supabase. Busco mi primer puesto formal de desarrollo, en remoto para LATAM.

📍 Chile · UTC−4 &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/leonardoaleman/) &nbsp;·&nbsp; leonardoaleman536@gmail.com

---

## Proyectos

### 🆘 [Emergencia Sísmica · Venezuela](https://github.com/Aleman7Dev/emergencia-venezuela) &nbsp;→&nbsp; [emergenciavenezuela.digital](https://emergenciavenezuela.digital/)

Aplicación web comunitaria para coordinar reportes ciudadanos durante una emergencia sísmica: mapa interactivo con reportes geolocalizados, búsqueda de personas desaparecidas y localizadas en hospitales, estado de vialidad, centros de acopio y directorio de emergencia.

Las decisiones que definieron el proyecto:

- **Los datos de identidad se guardan solo como hash** y nunca se publican. El cruce entre listas de hospital y de desaparecidos se hace sobre ese hash.
- **Los enlaces externos se validan por dominio y esquema** al guardar y al mostrar, para que un reporte no pueda inyectar `javascript:` ni trucos de `usuario@host`.
- **Un reporte se retira cuando varias personas distintas lo confirman**, para reducir información falsa que desvíe recursos de rescate.
- **PWA instalable con service worker**: la interfaz abre sin conexión, pero los reportes siempre se piden frescos a la red. En una emergencia, un dato viejo es peor que ningún dato.
- **Modo bajo consumo**: el mapa abre sin descargar las calles y se activan a demanda.

`JavaScript` · `Leaflet` · `Supabase` · `PWA + Service Worker` · `Web Push` · `Vercel` · MIT

### 🍫 [Delicias Chocolate](https://github.com/Aleman7Dev/delicias-chocolate-web)

Tienda administrable con vitrina pública en React y panel de administración en Laravel, preparada para despliegue en hosting compartido con DirectAdmin. Catálogo y colecciones administrables, login de administrador, checkout por WhatsApp y personalizadores de producto.

`React 19` · `TypeScript` · `Vite` · `Zustand` · `Framer Motion` · `Laravel 11` · `MySQL`

---

## Stack

**Móvil** · Kotlin · Java · Android Studio · Gradle
**Web** · JavaScript · TypeScript · React · HTML5 · CSS3 · WordPress / Elementor
**Backend y datos** · Laravel · Supabase (PostgreSQL) · MySQL · APIs REST · Python
**Analítica** · Google Tag Manager · Google Analytics
**Herramientas** · Git · GitHub · Vercel · Scrum

---

## Formación

**Ingeniería en Informática** — Instituto Profesional IACC, Chile · cursando último año

**1.300 horas de diplomados certificados por IACC:**

| Diplomado | Horas | Año |
|---|---|---|
| Programación en Java | 300 h | 2026 |
| Programación Avanzada | 300 h | 2024 |
| Desarrollo Web | 300 h | 2023 |
| Fundamentos de Programación y Bases de Datos | 400 h | 2023 |

Certificación Profesional en Git y GitHub.

---

## Antes de programar

Siete años en atención a clientes, ventas y supervisión de equipos. Me dejó dos cosas que uso todos los días: sé explicarle algo técnico a alguien que no lo es, y sé hacerme cargo de un resultado que otra persona está esperando.
