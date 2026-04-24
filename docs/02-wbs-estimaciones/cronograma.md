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
    
    section 1.2 Marco Bioético
    1.2.1 Doc. Comité Ética           :w121, 2026-05-05, 15d
    1.2.2 Análisis de restricciones   :w122, after w121, 10d
    1.2.3 Aprobación institucional    :w123, after w122, 20d
    SG1 - Habilitación Ejecución      :milestone, sg1, after w123, 0d
    
    section 1.3 Diseño y Parámetros
    1.3.1 Parámetros lagomorfos       :w131, after w111, 15d
    1.3.2 Matriz de escalabilidad     :w132, after w131, 10d
    1.3.3 Diseño conceptual sistema   :w133, after w131, 15d
    1.3.4 Diagramas de flujo          :w134, after w133, 10d
    
    section 2.1 Receptáculo Uterino
    2.1.1 Modelado CAD receptáculo    :w211, after sg1, 15d
    2.1.2 Bioimpresión receptáculo    :w212, after w211, 20d
    2.1.3 Pruebas de estanqueidad     :w213, after w212, 10d
    SG-S1 Receptáculo Validado        :milestone, sgs1, after w213, 0d
    
    section 2.2 Circuitos Vitales
    2.2.1 Módulo de bombeo            :w221, after sg1, 20d
    SG-S2 Bombeo Validado             :milestone, sgs2, after w221, 0d
    2.2.2 Sistema de hematosis        :w222, after sg1, 25d
    SG-S3 Oxigenación Validada        :milestone, sgs3, after w222, 0d
    2.2.3 Módulo de diálisis          :w223, after sg1, 20d
    SG-S4 Diálisis Validada           :milestone, sgs4, after w223, 0d
    2.2.4 Sistema de inyección        :w224, after sg1, 15d
    
    section 2.3 Electrónica
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
    
    section 4.1 Documentación Técnica
    4.1.1 Planos finales As-Built     :w411, after w324, 15d
    4.1.2 Fichas técnicas             :w412, after w324, 10d
    4.1.3 Log de decisiones           :w413, after w324, 5d
    
    section 4.2 Cierre y Presentación
    4.2.1 Materiales institucionales  :w421, after w324, 15d
    4.2.2 Presentación al cliente     :w422, after w421, 5d
    Hito - Cierre del Proyecto        :milestone, final, after w422, 0d
```

## Tabla de tareas

| **ID**   | **Tarea**                                             | **Predecesoras** | **Responsable**      | **Duración (días)** | **Inicio Estimado** | **Hito** |
| -------- | ----------------------------------------------------- | ---------------- | -------------------- | ------------------- | ------------------- | -------- |
|          | **FASE 1: INVESTIGACIÓN Y PLANIFICACIÓN (3.5 meses)** |                  |                      |                     |                     |          |
| 1.1.5    | Investigación bibliográfica                           | 1.1.1            | Biotecnólogo         | 20                  | may-26              | No       |
| 1.2.1    | Doc. Comité Ética                                     | 1.1.5            | Biotecnólogo         | 15                  | jun-26              | No       |
| 1.2.3    | Aprobación institucional                              | 1.2.2            | Director             | 30                  | jul-26              | No       |
| 1.3.1    | Investigación parámetros                              | 1.1.5            | Biotecnólogo         | 25                  | jun-26              | No       |
| 1.3.3    | Diseño conceptual                                     | 1.3.2            | Bioingeniero         | 20                  | jul-26              | No       |
| M1       | 🏁 SG1 - Habilitación                                 | 1.2.3, 1.3.4     | —                    | 0                   | ago-26              | Sí       |
|          | **FASE 2A: MATERIALES (2 meses)**                     |                  |                      |                     |                     |          |
| 2.0.1    | Investigación biomateriales                           | M1               | Esp. Materiales      | 30                  | sep-26              | No       |
| 2.0.2    | Pruebas biocompatibilidad                             | 2.0.1            | Esp. Materiales      | 20                  | oct-26              | No       |
|          | **FASE 2B: RECEPTÁCULO (3.5 meses - 2 iteraciones)**  |                  |                      |                     |                     |          |
| 2.1.2    | Bioimpresión prototipo v1                             | 2.1.1            | Esp. Materiales      | 12                  | nov-26              | No       |
| 2.1.3    | Pruebas estanqueidad v1                               | 2.1.2            | Técnico              | 8                   | nov-26              | No       |
| 2.1.4    | Rediseño v2                                           | 2.1.3            | Diseñador Industrial | 10                  | dic-26              | No       |
| 2.1.5    | Bioimpresión prototipo v2                             | 2.1.4            | Esp. Materiales      | 12                  | dic-26              | No       |
| 2.1.6    | Pruebas estanqueidad v2                               | 2.1.5            | Técnico              | 8                   | ene-27              | No       |
| MS1      | 🏁 SG-S1 Receptáculo                                  | 2.1.7            | —                    | 0                   | ene-27              | Sí       |
|          | **FASE 2C: CIRCUITOS (5 meses)**                      |                  |                      |                     |                     |          |
| 2.2.1-5  | Módulo bombeo (2 iteraciones)                         | M1               | Bioingeniero         | 72                  | sep-dic 26          | No       |
| MS2      | 🏁 SG-S2 Bombeo                                       | 2.2.6            | —                    | 0                   | dic-26              | Sí       |
| 2.2.7    | Investigación hematosis                               | MS2              | Biotecnólogo         | 25                  | ene-27              | No       |
| 2.2.8-10 | Diseño y fab. oxigenador                              | 2.2.7            | Bioingeniero         | 35                  | ene-feb 27          | No       |
| 2.2.11   | Calibración parámetros                                | 2.2.10           | Biotecnólogo         | 10                  | feb-27              | No       |
| MS3      | 🏁 SG-S3 Oxigenación                                  | 2.2.11           | —                    | 0                   | mar-27              | Sí       |
|          | **FASE 2D: ELECTRÓNICA (4 meses)**                    |                  |                      |                     |                     |          |
| 2.4.1    | Investigación sensores                                | M1               | Bioingeniero         | 15                  | sep-26              | No       |
| 2.4.6-8  | Dashboard v1 y v2                                     | 2.4.1            | Desarrollador        | 50                  | oct-dic 26          | No       |
| 2.4.10   | Validación electrónica                                | 2.4.9            | Bioingeniero         | 8                   | ene-27              | No       |
| MS5      | 🏁 SG-S5 Electrónica                                  | 2.4.10           | —                    | 0                   | ene-27              | Sí       |
|          | **FASE 3: INTEGRACIÓN (4 meses)**                     |                  |                      |                     |                     |          |
| 3.1.2    | Ensamblaje prototipo                                  | MS1, MS5         | Equipo completo      | 15                  | feb-27              | No       |
| 3.1.4    | Calibración sistema completo                          | 3.1.3            | Biotecnólogo         | 15                  | mar-27              | No       |
| 3.1.5    | Resolución problemas                                  | 3.1.4            | Equipo completo      | 20                  | mar-27              | No       |
| 3.2.3    | Prueba integrada 24hs v1                              | 3.2.1, 3.2.2     | Técnico              | 2                   | abr-27              | No       |
| 3.2.4    | Ajustes post-prueba                                   | 3.2.3            | Equipo               | 10                  | abr-27              | No       |
| 3.2.5    | Prueba integrada 48hs v2                              | 3.2.4            | Técnico              | 3                   | may-27              | No       |
| MS6      | 🏁 SG-S6 Integración                                  | 3.2.6            | —                    | 0                   | may-27              | Sí       |
|          | **FASE 4: CIERRE (2.5 meses)**                        |                  |                      |                     |                     |          |
| 4.1.4    | Documentación científica                              | 3.2.7            | Biotecnólogo         | 20                  | jun-27              | No       |
| 4.2.2    | Video demostración                                    | 4.2.1            | Marketing            | 10                  | jul-27              | No       |
| 4.2.3    | Presentación cliente                                  | 4.2.2            | Director             | 2                   | ago-27              | No       |
| MFIN     | 🏁 Cierre Proyecto                                    | 4.2.3            | —                    | 0                   | ago-27              | Sí       |


---

*Cátedra Gestión de Proyectos · FIUNER · 2026*
