# 🌱 Mis Hábitos — Seguimiento diario y recordatorios

App web sencilla para crear tus hábitos diarios, marcarlos cada día y no olvidarte de nada.
Un solo archivo, funciona **sin conexión** y guarda todo en tu propio dispositivo.

## ✨ Qué hace

- ✅ **Vista de hoy**: tus hábitos del día con contador o casilla de check.
- 📆 **Dos apartados**: **Hábitos diarios** (se reinician cada día) y **Hábitos semanales** (se cuentan toda la semana).
- 🎯 **Metas flexibles**: "sí/no", "8 vasos de agua al día", o "3 veces por semana" (p. ej. gimnasio).
- 🔥 **Rachas**: racha actual y mejor racha (en días para los diarios, en semanas para los semanales), con mapa de calor de los últimos 30 días.
- 📈 **Progreso**: % de esta semana, de los últimos 30 días, gráfica de los últimos 14 días y un resumen de las últimas 8 semanas para los hábitos semanales.
- ⏰ **Recordatorios**: aviso del navegador a la hora que elijas + botón para añadirlo a tu **calendario del móvil** (`.ics`).
- 📅 **Días pasados**: puedes ver y "reparar" días anteriores.
- 🗑️ **Quitar hábitos**: botón de papelera en cada hábito del día y también en *Ajustes → Mis hábitos* (siempre pide confirmación).
- 🌙 Tema claro / oscuro, **exportar/importar** copia de seguridad.

## 📆 Hábitos diarios vs. semanales

| Tipo | Para qué sirve | Ejemplo | Cómo se marca |
|---|---|---|---|
| **📆 Diario** | Cosas que haces cada día (o ciertos días de la semana). La meta se reinicia cada día. | *Beber 2 L de agua (8 veces/día)* · *Leer 20 min* | Casilla o contador del día |
| **🗓️ Semanal** | Cosas que no son todos los días. La meta se reinicia cada lunes. | *Gimnasio, 3 veces por semana* | Pulsas **＋** cada vez que vas; se guarda el día y se suma toda la semana |

Los hábitos semanales llevan una **barra de progreso** (`2/3 esta semana`) y su **racha se mide en semanas** seguidas cumpliéndolo.

### ⏰ Recordatorios: tú eliges los días

Al crear o editar un hábito marcas **en qué días quieres el aviso**:

- **Diario** → el hábito solo aparece (y avisa) esos días.
- **Semanal** → el hábito se ve siempre (puedes ir cualquier día), pero **solo te avisa los días que marques**.
  Ejemplo: *Gimnasio 3 veces/semana*, aviso **L · X · V** a las 19:00. Si ya has cumplido las 3 sesiones esa semana, deja de avisarte.
  En la tarjeta verás el detalle: `📅 L·X·V`.

El botón **「📅 Añadir al calendario」** crea el evento del calendario repitiéndose exactamente esos días.

## 🚀 Cómo usarla

**En tu ordenador:** abre el archivo `index.html` con el navegador (doble clic).

**En el móvil:** súbela a GitHub Pages (igual que ya hiciste con *Finanzas personales*) y ábrela desde el navegador del móvil.
Luego usa *"Añadir a pantalla de inicio"* para tenerla como si fuera una app.

## 🔔 Sobre los recordatorios

- Los **avisos del navegador** solo aparecen mientras la página está abierta (aunque esté en segundo plano). Requieren pulsar *Probar* una vez para dar permiso.
- Para que suenen **siempre, sin tener la web abierta**, edita un hábito y pulsa **「📅 Añadir al calendario」**: se descarga un archivo `.ics` que se añade a Google Calendar / Apple Calendar con repetición automática.

## 🔒 Privacidad

Todos los datos se guardan en el **almacenamiento local del navegador** de tu dispositivo.
No se envía nada a ningún servidor.
