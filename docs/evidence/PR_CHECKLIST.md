# Checklist de Revisión de Pull Requests (PR) - Sistema GeHO

Este documento define los puntos obligatorios que el **DevOps** debe verificar antes de aprobar e integrar cualquier cambio a la rama `develop`.

## ✅ Requisitos Técnicos
- [ ] **Compilación:** ¿El código compila correctamente sin errores?
- [ ] **Conflictos:** ¿La rama está libre de conflictos con `develop`?
- [ ] **Convenciones de Nomenclatura:** ¿Se respetan las reglas de C# (PascalCase) y estándares de bases de datos?
- [ ] **Pruebas:** ¿El autor confirmó que el cambio funciona en su entorno local?

## 🌿 Estándares de Git
- [ ] **Ramas:** ¿El cambio proviene de una rama `feature/*`?
- [ ] **Commits:** ¿Todos los mensajes de commit siguen el formato `tipo: descripción`?
- [ ] **Atomicidad:** ¿El PR se enfoca en una sola tarea o corrección?

## 📝 Documentación
- [ ] **Descripción del PR:** ¿Se explica claramente qué se cambió y por qué?
- [ ] **Comentarios:** ¿El código complejo está debidamente comentado?
- [ ] **Evidencia:** Si aplica, ¿se adjuntó captura de pantalla o log de la funcionalidad?

---
*Este checklist es parte del protocolo de calidad del rol de DevOps para el proyecto Sistema GeHO.*
