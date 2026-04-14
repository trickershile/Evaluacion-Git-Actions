# Evaluación Git y GitHub Actions
**Primer encargo:** Simulación de desarrollo colaborativo. Implementación de flujo de trabajo con GitFlow, revisión mediante Pull Requests y automatización básica con GitHub Actions.

---

## Justificación del Flujo de Trabajo
He decidido utilizar **GitFlow** porque el encargo requiere explícitamente el uso de ramas de desarrollo continuo (`develop`), ramas de nuevas características (`feature/*`) y ramas de corrección de errores críticos (`hotfix/*`). GitFlow estructura perfectamente esta separación, manteniendo la rama `main` limpia y estable, mientras la integración del trabajo diario ocurre en la rama `develop`.

## Convenciones del Proyecto
* **Nomenclatura de Ramas (Naming):** * Nuevas características: `feature/nombre-de-la-caracteristica` (ej. `feature/pagina-inicio`).
  * Correcciones en producción: `hotfix/nombre-del-error` (ej. `hotfix/error-critico`).
* **Mensajes de Commit:** Se utilizarán mensajes en minúscula, descriptivos y en modo imperativo (ej. "agrega botón de inicio", "corrige error de navegación").
* **Estrategia de Merge y Revisión:** Todo el código nuevo se integrará a través de **Pull Requests (PR)**. Dado que este trabajo se está realizando de manera individual, se simulará el entorno colaborativo: crearé los PRs desde las ramas correspondientes y realizaré una autorevisión del código antes de ejecutar el merge hacia `develop` o `main`.
