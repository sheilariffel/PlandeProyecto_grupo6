# 📅 Cronograma del Proyecto

## Diagrama de Gantt

```mermaid
gantt
    title Cronograma BioNest - Sistema de Ectogénesis Artificial
    dateFormat  YYYY-MM-DD
    excludes    weekends

    section 1.1 Inicio y Gestión
    1.1.1 Acta de Constitución        :w111, 2026-05-05, 5d
    1.1.2 Plan de Gestión             :w112, after w111, 10d
    1.1.3 Registro Stakeholders       :w113, after w111, 5d
    1.1.4 Registro de Riesgos Inicial :w114, after w112, 7d
    1.1.5 Investigación bibliográfica :w115, after w111, 15d
    1.1.6 Contratos con proveedores   :w116, after w112, 10d
    1.1.7 Reunión de Kick-Off         :milestone, w117, after w114, 0d

    section 1.2 Marco Bioético y Normativo
    1.2.1 Doc. Comité Ética           :w121, 2026-05-05, 15d
    1.2.2 Análisis de restricciones   :w122, after w121, 10d
    1.2.3 Revisión interna            :w123, after w122, 5d
    1.2.4 Aprobación CICUAL           :w124, after w123, 20d
    1.2.5 Aprobación IRAM/IEC         :w125, after w123, 20d
    SG1 - Habilitación Ejecución      :milestone, sg1, after w124 w125, 0d

    section 1.3 Diseño y Parámetros
    1.3.1 Parámetros lagomorfos       :w131, after w115, 15d
    1.3.2 Matriz de escalabilidad     :w132, after w131, 10d
    1.3.3 Diseño funcional sistema    :w133, after w131, 15d
    1.3.4 Diagramas de flujo          :w134, after w133, 10d

    section 2.1 Receptáculo Uterino
    2.1.1 Compra materiales           :w211c, after sg1, 5d
    2.1.2 Modelado CAD receptáculo    :w211, after sg1, 15d
    2.1.3 Bioimpresión receptáculo    :w212, after w211, 20d
    2.1.4 Pruebas de estanqueidad     :w213, after w212, 10d
    SG-S1 Receptáculo Validado        :milestone, sgs1, after w213, 0d

    section 2.2 Circuitos Vitales
    2.2.1 Módulo de bombeo            :w221, after sg1, 20d
    SG-S2 Bombeo Validado             :milestone, sgs2, after w221, 0d
    2.2.2 Sistema de hematosis        :w222, after sg1, 25d
    SG-S3 Oxigenación Validada        :milestone, sgs3, after w222, 0d
    2.2.3 Módulo de diálisis          :w223, after sg1, 20d
    SG-S4 Diálisis Validada           :milestone, sgs4, after w223, 0d
    2.2.4 Sistema de inyección        :w224, after sg1, 15d

    section 2.3 Electrónica y Control
    2.3.1 Matriz de sensores          :w231, after sg1, 15d
    2.3.2 Dashboard de monitoreo      :w232, after w231, 20d
    2.3.3 Sistema de registro         :w233, after w232, 15d
    SG-S5 Sistema Electrónico         :milestone, sgs5, after w233, 0d
    2.3.4 Módulo de estimulación      :w234, after sg1, 15d

    section 3.1 Integración
    3.1.1 Ensamblaje del prototipo    :w311, after sgs1 sgs2 sgs3 sgs4 sgs5, 15d
    3.1.2 Acople sensores-Dashboard   :w312, after w311, 10d
    3.1.3 Calibración del sistema     :w313, after w312, 15d

    section 3.2 Pruebas y Validación
    3.2.1 Ensayos hidráulicos         :w321, after w313, 8d
    3.2.2 Ensayos térmicos            :w322, after w321, 8d
    3.2.3 Prueba integrada 24hs       :w323, after w322, 5d
    SG-S6 Integración Final           :milestone, sgs6, after w323, 0d
    3.2.4 Informe de resultados       :w324, after sgs6, 10d

    section 3.3 Control de Calidad Final
    3.3.1 Entrega a tercero — validación y normativa :w331, after sgs6, 15d

    section 4.1 Documentación Técnica
    4.1.1 Planos finales As-Built     :w411, after w324, 15d
    4.1.2 Fichas técnicas             :w412, after w324, 10d
    4.1.3 Log de decisiones           :w413, after w324, 5d
    4.1.4 Manual de usuario           :w414, after w324, 10d

    section 4.2 Cierre y Transferencia
    4.2.1 Reunión de cierre           :w421, after w331 w411 w412 w413 w414, 3d
    4.2.2 Presentación al cliente     :w422, after w421, 5d
    Hito - Cierre del Proyecto        :milestone, final, after w422, 0d
```

## Tabla de tareas

| **ID** | **Tarea** | **Predecesoras** | **Responsable** | **Duración (días)** | **Inicio Estimado** | **Hito** |
|--------|-----------|-----------------|-----------------|:-------------------:|--------------------:|:--------:|
| | **FASE 1 — PLANIFICACIÓN PREDICTIVA** | | | | | |
| 1.1.1 | Acta de Constitución | — | Director de Proyecto | 5 | may-26 | No |
| 1.1.2 | Plan de Gestión del Proyecto | 1.1.1 | Director de Proyecto | 10 | may-26 | No |
| 1.1.3 | Registro de Stakeholders | 1.1.1 | Director de Proyecto | 5 | may-26 | No |
| 1.1.4 | Registro de Riesgos Inicial | 1.1.2 | Director de Proyecto | 7 | jun-26 | No |
| 1.1.5 | Investigación bibliográfica | 1.1.1 | Biotecnólogo | 15 | may-26 | No |
| 1.1.6 | Contratos con proveedores | 1.1.2 | Director de Proyecto | 10 | jun-26 | No |
| 1.1.7 | Reunión de Kick-Off | 1.1.4 | Director de Proyecto | 0 | jun-26 | **Sí** |
| 1.2.1 | Doc. Comité de Ética | 1.1.5 | Biotecnólogo | 15 | jun-26 | No |
| 1.2.2 | Análisis de restricciones | 1.2.1 | Biotecnólogo | 10 | jun-26 | No |
| 1.2.3 | Revisión interna | 1.2.2 | Director / Biotecnólogo | 5 | jul-26 | No |
| 1.2.4 | Aprobación CICUAL | 1.2.3 | Director de Proyecto | 20 | jul-26 | No |
| 1.2.5 | Aprobación IRAM/IEC | 1.2.3 | Bioingeniero | 20 | jul-26 | No |
| **SG1** | 🏁 **Stage-Gate 1 — Habilitación de Ejecución** | 1.2.4, 1.2.5 | — | 0 | ago-26 | **Sí** |
| 1.3.1 | Parámetros fisiológicos lagomorfos | 1.1.5 | Biotecnólogo | 15 | jun-26 | No |
| 1.3.2 | Matriz de escalabilidad | 1.3.1 | Biotecnólogo | 10 | jun-26 | No |
| 1.3.3 | Diseño funcional del sistema | 1.3.1 | Bioingeniero / Diseño Industrial | 15 | jul-26 | No |
| 1.3.4 | Diagramas de flujo | 1.3.3 | Bioingeniero | 10 | jul-26 | No |
| | **FASE 2 — EJECUCIÓN ADAPTATIVA (Kanban)** | | | | | |
| 2.1.1 | Compra de materiales a proveedores | SG1 | Esp. Materiales | 5 | ago-26 | No |
| 2.1.2 | Modelado CAD receptáculo | SG1 | Lic. Diseño Industrial | 15 | ago-26 | No |
| 2.1.3 | Bioimpresión receptáculo | 2.1.2 | Esp. Materiales | 20 | sep-26 | No |
| 2.1.4 | Pruebas de estanqueidad | 2.1.3 | Técnico de Laboratorio | 10 | oct-26 | No |
| **SG-S1** | 🏁 **Stage-Gate S1 — Receptáculo Validado** | 2.1.4 | — | 0 | oct-26 | **Sí** |
| 2.2.1 | Módulo de bombeo | SG1 | Bioingeniero | 20 | ago-26 | No |
| **SG-S2** | 🏁 **Stage-Gate S2 — Bombeo Validado** | 2.2.1 | — | 0 | sep-26 | **Sí** |
| 2.2.2 | Sistema de hematosis | SG1 | Bioingeniero / Biotecnólogo | 25 | ago-26 | No |
| **SG-S3** | 🏁 **Stage-Gate S3 — Oxigenación Validada** | 2.2.2 | — | 0 | sep-26 | **Sí** |
| 2.2.3 | Módulo de diálisis | SG1 | Bioingeniero / Biotecnólogo | 20 | ago-26 | No |
| **SG-S4** | 🏁 **Stage-Gate S4 — Diálisis Validada** | 2.2.3 | — | 0 | sep-26 | **Sí** |
| 2.2.4 | Sistema de inyección | SG1 | Bioingeniero | 15 | ago-26 | No |
| 2.3.1 | Matriz de sensores | SG1 | Bioingeniero | 15 | ago-26 | No |
| 2.3.2 | Dashboard de monitoreo | 2.3.1 | Desarrollador de Software | 20 | sep-26 | No |
| 2.3.3 | Sistema de registro de datos | 2.3.2 | Desarrollador de Software | 15 | oct-26 | No |
| 2.3.4 | Módulo de estimulación | SG1 | Bioingeniero | 15 | ago-26 | No |
| **SG-S5** | 🏁 **Stage-Gate S5 — Sistema Electrónico Validado** | 2.3.3 | — | 0 | nov-26 | **Sí** |
| | **FASE 3 — INTEGRACIÓN Y VALIDACIÓN FINAL** | | | | | |
| 3.1.1 | Ensamblaje del prototipo completo | SG-S1, SG-S2, SG-S3, SG-S4, SG-S5 | Equipo completo | 15 | nov-26 | No |
| 3.1.2 | Acople sensores–Dashboard | 3.1.1 | Bioingeniero / Desarrollador | 10 | dic-26 | No |
| 3.1.3 | Calibración del sistema | 3.1.2 | Biotecnólogo / Bioingeniero | 15 | dic-26 | No |
| 3.2.1 | Ensayos hidráulicos integrados | 3.1.3 | Técnico de Laboratorio | 8 | ene-27 | No |
| 3.2.2 | Ensayos térmicos integrados | 3.2.1 | Técnico de Laboratorio | 8 | ene-27 | No |
| 3.2.3 | Prueba integrada 24hs | 3.2.2 | Técnico de Laboratorio | 5 | feb-27 | No |
| **SG-S6** | 🏁 **Stage-Gate S6 — Integración Final** | 3.2.3 | — | 0 | feb-27 | **Sí** |
| 3.2.4 | Informe final de resultados | SG-S6 | Biotecnólogo / Director | 10 | feb-27 | No |
| 3.3.1 | Entrega a tercero — validación y normativa | SG-S6 | Director de Proyecto | 15 | mar-27 | No |
| | **FASE 4 — CIERRE Y TRANSFERENCIA** | | | | | |
| 4.1.1 | Planos finales As-Built | 3.2.4 | Lic. Diseño Industrial | 15 | mar-27 | No |
| 4.1.2 | Fichas técnicas | 3.2.4 | Esp. Materiales / Bioingeniero | 10 | mar-27 | No |
| 4.1.3 | Log de decisiones | 3.2.4 | Director de Proyecto | 5 | mar-27 | No |
| 4.1.4 | Manual de usuario | 3.2.4 | Biotecnólogo / Bioingeniero | 10 | mar-27 | No |
| 4.2.1 | Reunión de cierre | 3.3.1, 4.1.1, 4.1.2, 4.1.3, 4.1.4 | Director de Proyecto | 3 | abr-27 | No |
| 4.2.2 | Presentación al cliente | 4.2.1 | Director / Resp. Marketing | 5 | abr-27 | No |
| **MFIN** | 🏁 **Cierre del Proyecto** | 4.2.2 | — | 0 | abr-27 | **Sí** |

---

*Cátedra Gestión de Proyectos · FIUNER · 2026*
