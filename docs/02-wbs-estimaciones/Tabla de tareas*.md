# Tabla de tareas

| **ID** | **Tarea** | **Predecesoras** | **Responsable** | **Duración (días)** | **Inicio Estimado** | **Hito** |
|--------|-----------|-----------------|-----------------|:-------------------:|--------------------:|:--------:|
| | **FASE 1 — PLANIFICACIÓN PREDICTIVA** | | | | | |
| 1.1.1 | Acta de Constitución | — | Director de Proyecto | 2 | may-26 | No |
| 1.1.2 | Plan de Gestión del Proyecto | 1.1.1 | Director de Proyecto | 5 | may-26 | No |
| 1.1.3 | Registro y Estrategia de Stakeholders | 1.1.1 | Director de Proyecto | 2 | may-26 | No |
| 1.1.4 | Identificar Riesgos Iniciales | 1.1.2 | Director de Proyecto | 2 | may-26 | No |
| 1.1.5 | Diagramar Presupuesto | 1.1.2 | Director de Proyecto | 3 | jun-26 | No |
| 1.1.6 | Gestionar Contratos con Proveedores | 1.1.2 | Director de Proyecto | 5 | jun-26 | No |
| 1.1.7 | Reunión de Kick Off | 1.1.4 | Director de Proyecto | 1 | jun-26 | **Sí** |
| 1.2.1 | Documentación para Comité de Ética | 1.1.5 | Biotecnólogo | 6 | jun-26 | No |
| 1.2.2 | Análisis de Implicancias y Restricciones | 1.2.1 | Biotecnólogo | 4 | jun-26 | No |
| 1.2.3 | Etapa de Revisión | 1.2.2 | Biotecnólogo / Bioingeniero | 4 | jul-26 | No |
| 1.2.4 | Envío Documentación al Organismo de Ética | 1.2.3 | Director de Proyecto | 1 | jul-26 | No |
| 1.2.5 | ⬧ Aprobación CICUAL | 1.2.4 | — | 35 | jul-26 | **Sí** |
| 1.3.1 | Especificaciones Fisiológicas (Lagomorfos) | 1.1.5 | Biotecnólogo | 5 | jun-26 | No |
| 1.3.2 | Matriz de Escalabilidad | 1.3.1 | Biotecnólogo | 3 | jun-26 | No |
| 1.3.3 | Diseño Funcional del Sistema (Arquitectura) | 1.3.1 | Bioingeniero / Diseño Industrial | 6 | jul-26 | No |
| 1.3.4 | Diagramas de Flujo del Sistema | 1.3.3 | Bioingeniero | 4 | jul-26 | No |
| | **FASE 2 — EJECUCIÓN ADAPTATIVA (Kanban)** | | | | | |
| 2.1.1 | Compra de Materiales (Tercerizada) | 1.2.5 | Especialista Materiales | 3 | ago-26 | No |
| 2.1.2 | Modelado CAD del Habitáculo Uterino | 1.2.5 | Lic. Diseño Industrial | 8 | ago-26 | No |
| 2.1.3 | ⚠ Bioimpresión con Hidrogeles/Biomateriales | 2.1.2 | Especialista Materiales | 12 | sep-26 | No |
| 2.1.4 | Pruebas de Estanqueidad y Resistencia | 2.1.3 | Técnico de Laboratorio | 5 | oct-26 | No |
| **SG-S1** | 🏁 **Stage-Gate S1 — Receptáculo Validado** | 2.1.4 | — | 0 | oct-26 | **Sí** |
| 2.2.1 | Diseñar y Ensamblar Módulo de Bombeo | 1.2.5 | Bioingeniero | 12 | ago-26 | No |
| **SG-S2** | 🏁 **Stage-Gate S2 — Bombeo Validado** | 2.2.1 | — | 0 | sep-26 | **Sí** |
| 2.2.2 | Sistema de Hematosis Artificial | 1.2.5 | Bioingeniero / Biotecnólogo | 16 | ago-26 | No |
| **SG-S3** | 🏁 **Stage-Gate S3 — Oxigenación Validada** | 2.2.2 | — | 0 | oct-26 | **Sí** |
| 2.2.3 | Módulo de Filtrado y Diálisis | 1.2.5 | Bioingeniero / Biotecnólogo | 9 | ago-26 | No |
| **SG-S4** | 🏁 **Stage-Gate S4 — Diálisis Validada** | 2.2.3 | — | 0 | oct-26 | **Sí** |
| 2.2.4 | Sistema de Inyección de Nutrientes/Hormonas | 1.2.5 | Bioingeniero | 5 | ago-26 | No |
| 2.3.1 | Integración Matriz de Sensores (P/T/pH/Vol) | 1.2.5 | Bioingeniero | 9 | ago-26 | No |
| 2.3.2 | Interfaz de Usuario (Dashboard) | 2.3.1 | Desarrollador de Software | 11 | sep-26 | No |
| 2.3.3 | Sistema de Almacenamiento y Registro de Datos | 2.3.2 | Desarrollador de Software | 6 | oct-26 | No |
| 2.3.4 | Módulo de Estimulación | 1.2.5 | Bioingeniero | 5 | ago-26 | No |
| **SG-S5** | 🏁 **Stage-Gate S5 — Sistema Electrónico Validado** | 2.3.3 | — | 0 | nov-26 | **Sí** |
| | **FASE 3 — INTEGRACIÓN Y VALIDACIÓN FINAL** | | | | | |
| 3.1.1 | Ensamblaje del Prototipo Físico Completo | SG-S1, SG-S2, SG-S3, SG-S4, SG-S5 | Equipo Multidisciplinario | 9 | nov-26 | No |
| 3.1.2 | Acoplamiento de Sensores al Dashboard | 3.1.1 | Bioingeniero / Desarrollador | 5 | dic-26 | No |
| 3.1.3 | Calibración del Sistema Completo | 3.1.2 | Biotecnólogo / Bioingeniero | 7 | dic-26 | No |
| 3.2.1 | Ensayos Hidráulicos Integrados | 3.1.3 | Técnico de Laboratorio | 5 | ene-27 | No |
| 3.2.2 | Ensayos Térmicos Integrados | 3.1.3 | Técnico de Laboratorio | 4 | ene-27 | No |
| 3.2.3 | Simulación Circulación Continua 24hs | 3.2.2 | Técnico de Laboratorio | 6 | feb-27 | No |
| 3.2.4 | Informe Final de Resultados y Conclusiones | 3.2.3 | Biotecnólogo / Director | 5 | feb-27 | No |
| 3.2.5 | Entrega a Tercero para Control de Calidad | 3.2.4 | Director de Proyecto | 2 | feb-27 | No |
| 3.2.6 | ⬧ Obtención de Aprobación del Control de Calidad | 3.2.5 | — | 1 | mar-27 | **Sí** |
| **SG-S6** | 🏁 **Stage-Gate S6 — Integración y Validación Final** | 3.2.6 | — | 0 | mar-27 | **Sí** |
| | **FASE 4 — CIERRE Y TRANSFERENCIA** | | | | | |
| 4.1.1 | Actualizar Planos Finales As-Built | SG-S6 | Lic. Diseño Industrial | 3 | mar-27 | No |
| 4.1.2 | Elaborar Fichas Técnicas | SG-S6 | Especialista Materiales / Bioingeniero | 3 | mar-27 | No |
| 4.1.3 | Compilar Log de Decisiones | SG-S6 | Director de Proyecto | 2 | mar-27 | No |
| 4.1.4 | Redactar Manual de Usuario | SG-S6 | Biotecnólogo / Bioingeniero | 4 | mar-27 | No |
| 4.2.1 | Reunión de Cierre | 4.1.4 | Director de Proyecto | 1 | abr-27 | No |
| 4.2.2 | Presentación Final a Institución de Conservación | 4.2.1 | Director / Responsable Marketing | 3 | abr-27 | **Sí** |
| **MFIN** | 🏁 **Cierre del Proyecto** | 4.2.2 | — | 0 | abr-27 | **Sí** |

---

*Cátedra Gestión de Proyectos · FIUNER · 2026*

