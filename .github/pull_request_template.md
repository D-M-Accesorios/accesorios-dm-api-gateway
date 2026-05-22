## [HU-ENV-INICIALES_XX] Título de la Historia de Usuario

---

### Descripción

<!-- Describe brevemente qué hace este PR y por qué es necesario. -->

---

### HU relacionada

- **ID:** HU-ENV-INICIALES_XX
- **Repositorio del backlog:** [accesorios-dm/docs/HUs/](../accesorios-dm/docs/HUs/)

---

### ADRs aplicados

- [ ] ADR-008 — Versionamiento de APIs (`/api/v1/`)
- [ ] ADR-009 — Formato estándar de errores

---

### Tipo de cambio

- [ ] `feat` — Nueva funcionalidad
- [ ] `fix` — Corrección de bug
- [ ] `refactor` — Refactorización
- [ ] `chore` — Configuración / dependencias
- [ ] `docs` — Documentación
- [ ] `test` — Tests
- [ ] `ci` — Pipeline CI/CD

---

### Criterios de aceptación completados

- [ ] ...
- [ ] ...

---

### Checklist técnico — API Gateway

- [ ] El código no contiene secretos, credenciales ni valores hardcodeados.
- [ ] Las rutas siguen el prefijo `/api/v1/{service}/` (ADR-008).
- [ ] Los errores proxiados respetan el formato estándar definido en ADR-009.
- [ ] El rate limiting está configurado si se expone un nuevo endpoint público.
- [ ] Las cabeceras CORS no fueron modificadas sin aprobación del lead.
- [ ] Los targets de proxy apuntan a variables de entorno, no a IPs hardcodeadas.
- [ ] El archivo `.env.example` fue actualizado si se agregaron nuevas variables.
- [ ] El servicio levanta correctamente con `docker-compose up`.

---

### Checklist de Definición de Done

- [ ] Los criterios de aceptación de la HU están cumplidos.
- [ ] El CI pasa (validate-branch-flow + build si aplica).
- [ ] El reviewer aprobó el PR.
- [ ] La rama `HU-*` será eliminada tras el merge.

---

### Notas al reviewer

<!-- Contexto adicional, decisiones tomadas, áreas de atención especial. -->
