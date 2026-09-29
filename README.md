# Jóvenes Vida Nueva Internacional

Aplicación web (un solo archivo `index.html`) para el seguimiento de jóvenes del ministerio.

## Funciones
- **Inicio:** calendario principal de eventos, alertas de seguimiento, próximos eventos y cumpleaños del mes.
- **Eventos:** fecha, horario, repetición, lugar, responsable, predicador, cupo, costo, observaciones y asistencia por joven (Presente / Tarde / Justificado / Ausente).
- **Jóvenes:** canal de contacto (WhatsApp, llamada) y calendario mensual de seguimiento por joven con estado de color (Bien / Atención / Crítico).
- **Alertas:** un joven queda en alerta si pasan más de 3 días sin seguimiento o si el último fue crítico.
- **Casas de oración y Congregación:** reuniones, asistencia, visitantes, nuevos convertidos y peticiones.

## Uso
Abre `index.html` en el navegador o publícalo con GitHub Pages (Settings → Pages → rama `main`, carpeta raíz).

## Datos
- Publicada como Artifact en claude.ai usa una base de datos compartida entre el equipo.
- Fuera de claude.ai (por ejemplo en GitHub Pages) guarda los datos en el navegador de cada dispositivo (`localStorage`).
