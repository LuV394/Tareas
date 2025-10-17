# TaskTracker Diario Pro

Una aplicación web ligera para la gestión y trazabilidad de tareas diarias, con soporte para timers, categorías, plantillas rápidas, visualizaciones de productividad y exportación de datos. Construida con HTML, CSS, JavaScript, Chart.js y Dexie.js (para IndexedDB).

## Descripción

TaskTracker Diario Pro es una herramienta para rastrear tareas diarias con enfoque en productividad. Permite crear tareas, pausarlas, completarlas, y analizar el tiempo invertido mediante gráficos y métricas. Todo se almacena localmente en el navegador para privacidad y rapidez.

### Características Principales
- **Registro de Tareas**: Crea tareas con nombre, descripción, categoría, prioridad y color. Soporte para pausar/reanudar y timers en tiempo real.
- **Plantillas Rápidas**: Preconfiguraciones para tareas comunes.
- **Gestión de Categorías**: Agrega, edita y elimina categorías personalizadas desde la configuración.
- **Visualización**: Gráficos de timeline (Gantt), distribución por categoría, eficiencia y productividad semanal.
- **Exportación**: Reportes en TXT, CSV y backups completos en JSON.
- **Configuración**: Auto-guardado, notificaciones, limpieza de datos.
- **Responsivo**: Adaptable a móviles y desktops.
- **Optimizaciones de Rendimiento**: Timer con `requestAnimationFrame`, renderizado incremental del DOM, debounce en eventos.

## Instalación

1. Clona o descarga el repositorio:
git clone <url-del-repo>
2. Abre `index.html` en un navegador moderno (Chrome, Firefox, Edge).
3. No requiere servidor; funciona offline gracias a IndexedDB.

**Dependencias** (cargadas via CDN):
- Chart.js v3.9.1 (para gráficos).
- Dexie.js v3.2.2 (para IndexedDB).

## Uso

1. **Registro de Tareas**:
- Haz clic en "Nueva Tarea" para crear una.
- Usa plantillas para tareas frecuentes.
- Pausa, reanuda o completa tareas desde las tarjetas.

2. **Visualización**:
- Selecciona una fecha para ver métricas y gráficos.

3. **Configuración**:
- Gestiona categorías, auto-guardado y backups.

4. **Exportación**:
- Exporta el día actual o backups completos.

Ejemplo de flujo:
Usuario -> Registro -> Nueva Tarea -> Iniciar
Usuario -> Pausar/Completar -> Visualización -> Analizar gráficos
Usuario -> Configuración -> Gestionar categorías

## Estructura del Proyecto

- `index.html`: Archivo principal con HTML, CSS y JS integrados.
- (No hay archivos adicionales; todo es self-contained para simplicidad).

## Contribución

1. Forkea el repositorio.
2. Crea una branch: `git checkout -b feature/nueva-funcion`.
3. Commitea cambios: `git commit -m 'Añade nueva función'`.
4. Push: `git push origin feature/nueva-funcion`.
5. Abre un Pull Request.

Sugerencias bienvenidas: mejoras en UX, integración con APIs externas o soporte para PWA.

## Licencia

MIT License. Usa libremente, pero cita la fuente si es posible.

## Autor

Desarrollado por [Tu Nombre o Alias]. Contacto: [tu-email@example.com].

Última actualización: 16 de octubre de 2025.