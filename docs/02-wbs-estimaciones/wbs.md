# 🌳 Work Breakdown Structure (WBS)

## Diagrama WBS

```mermaid
mindmap
  root(("📁 BioNest\nSistema de Ectogénesis"))

    1. Plan de Gestión
      1.1 Formulación del Proyecto
        1.1.1 Acta de Constitución
        1.1.2 Plan de Gestión del Proyecto
        1.1.3 Registro de Stakeholders
        1.1.4 Registro de Riesgos Inicial
      1.2 Expediente bioético
        1.2.1 Documentación Comité Ética
        1.2.2 Análisis de restricciones
        1.2.3 Aprobación institucional
      1.3 Documentación técnica inicial
        1.3.1 Parámetros fisiológicos lagomorfos
        1.3.2 Matriz de escalabilidad
        1.3.3 Diseño conceptual sistema
        1.3.4 Diagramas de flujo

    2. Prototipo físico y electrónico
      2.1 Receptáculo bioimpreso
        2.1.1 Modelado CAD receptáculo
        2.1.2 Bioimpresión del receptáculo
        2.1.3 Pruebas de estanqueidad
      2.2 Subsistemas fisiológicos
        2.2.1 Módulo de bombeo
        2.2.2 Sistema de hematosis
        2.2.3 Módulo de diálisis
        2.2.4 Sistema de inyección
      2.3 Sistema electrónico
        2.3.1 Matriz de sensores
        2.3.2 Dashboard de monitoreo
        2.3.3 Sistema de registro
        2.3.4 Módulo de estimulación

    3. Integración y validación
      3.1 Integración del sistema
        3.1.1 Ensamblaje del prototipo
        3.1.2 Acople sensores-Dashboard
        3.1.3 Calibración del sistema
      3.2 Ensayos y validación
        3.2.1 Ensayos hidráulicos
        3.2.2 Ensayos térmicos
        3.2.3 Prueba integrada 24hs
        3.2.4 Informe de resultados

    4. Cierre y transferencia
      4.1 Documentación final
        4.1.1 Planos finales As-Built
        4.1.2 Fichas técnicas
        4.1.3 Log de decisiones
      4.2 Presentación
        4.2.1 Materiales institucionales
        4.2.2 Presentación al cliente
```

## Diccionario de la WBS

| ID    | Nombre de la tarea                 | Entregable asociado     | Descripción                                                                             | Criterio de completitud                  |
| ----- | ---------------------------------- | ----------------------- | --------------------------------------------------------------------------------------- | ---------------------------------------- |
| 1.1.1 | Acta de Constitución               | Plan de Gestión         | Documento formal que autoriza el proyecto, define objetivos, sponsor y autoridad del PM | Firma del sponsor y aprobación formal    |
| 1.1.2 | Plan de Gestión del Proyecto       | Plan de Gestión         | Documento maestro: alcance, cronograma, costos, calidad, riesgos, comunicaciones        | Aprobación del equipo directivo          |
| 1.1.3 | Registro de Stakeholders           | Plan de Gestión         | Identificación, clasificación y estrategia de involucramiento de partes interesadas     | Matriz poder/interés completa            |
| 1.1.4 | Registro de Riesgos Inicial        | Plan de Gestión         | Identificación de riesgos técnicos, regulatorios y de bioseguridad con respuestas       | Matriz de riesgos priorizada             |
| 1.2.1 | Documentación Comité Ética         | Expediente bioético     | Expediente formal con protocolo experimental, consideraciones éticas y restricciones    | Documento completo para comité           |
| 1.2.2 | Análisis de restricciones          | Expediente bioético     | Análisis de implicancias bioéticas, normativas y limitaciones de uso del sistema        | Informe de restricciones firmado         |
| 1.2.3 | Aprobación institucional           | Expediente bioético     | Obtención de la aprobación formal del Comité de Ética institucional (SG1)               | Carta de aprobación recibida             |
| 1.3.1 | Parámetros fisiológicos lagomorfos | Matriz de escalabilidad | Definición de rangos objetivo: presión, temperatura, pH, flujos para O. cuniculus       | Tabla paramétrica validada               |
| 1.3.2 | Matriz de escalabilidad            | Matriz de escalabilidad | Tabla con rangos S/M/L especies y fórmulas de conversión paramétrica                    | Validación matemática 3 categorías       |
| 1.3.3 | Diseño conceptual sistema          | Documentación técnica   | Arquitectura modular del sistema completo con subsistemas identificados                 | Diagrama de bloques aprobado             |
| 1.3.4 | Diagramas de flujo                 | Documentación técnica   | Flujos de circulación, oxigenación, diálisis e inyección de nutrientes                  | Diagramas P&ID validados                 |
| 2.1.1 | Modelado CAD receptáculo           | Prototipo físico        | Diseño 3D del habitáculo uterino escala lagomorfa (200-400ml)                           | Modelo CAD revisado                      |
| 2.1.2 | Bioimpresión del receptáculo       | Prototipo físico        | Fabricación física con biomateriales/hidrogeles biocompatibles                          | Pieza física bioimpresa                  |
| 2.1.3 | Pruebas de estanqueidad            | Protocolo de pruebas    | Validación hidráulica a presión nominal sin deformación (Stage-Gate S1)                 | Aprobación SG-S1                         |
| 2.2.1 | Módulo de bombeo                   | Prototipo físico        | Circuito cerrado con bomba peristáltica simulando corazón artificial                    | Circulación 24hs sin pérdidas (SG-S2)    |
| 2.2.2 | Sistema de hematosis               | Prototipo físico        | Oxigenador de membrana para transferencia O₂/CO₂                                        | Transferencia en rangos objetivo (SG-S3) |
| 2.2.3 | Módulo de diálisis                 | Prototipo físico        | Sistema de filtrado para remoción de desechos metabólicos simulados                     | Remoción sobre umbral (SG-S4)            |
| 2.2.4 | Sistema de inyección               | Prototipo físico        | Bomba de infusión controlada para simulación de nutrientes/hormonas                     | Flujo regulable validado                 |
| 2.3.1 | Matriz de sensores                 | Sistema electrónico     | Sensores de presión, temperatura, pH, volumen integrados al receptáculo                 | 4 sensores funcionando simultáneamente   |
| 2.3.2 | Dashboard de monitoreo             | Sistema electrónico     | Interfaz gráfica en tiempo real para visualización de variables críticas                | UI funcional con datos en vivo           |
| 2.3.3 | Sistema de registro                | Sistema electrónico     | Base de datos para almacenamiento persistente de datos experimentales                   | Registro sin pérdidas 24hs (SG-S5)       |
| 2.3.4 | Módulo de estimulación             | Prototipo físico        | Sistema de presión mecánica y emisión acústica en el habitáculo                         | Funcionamiento verificado                |
| 3.1.1 | Ensamblaje del prototipo           | Prototipo físico        | Integración mecánica de todos los subsistemas físicos                                   | Sistema armado completo                  |
| 3.1.2 | Acople sensores-Dashboard          | Sistema electrónico     | Conexión eléctrica y calibración de sensores con interfaz software                      | Lectura coherente en Dashboard           |
| 3.1.3 | Calibración del sistema            | Protocolo de pruebas    | Ajuste fino de parámetros a rangos fisiológicos lagomorfos                              | Variables en rangos +/- 5%               |
| 3.2.1 | Ensayos hidráulicos                | Protocolo de pruebas    | Pruebas de circulación, presión y estanqueidad del sistema integrado                    | Protocolo ejecutado sin fallas           |
| 3.2.2 | Ensayos térmicos                   | Protocolo de pruebas    | Validación de control de temperatura (37-38°C lagomorfos)                               | Temperatura estable +/- 0.5°C            |
| 3.2.3 | Prueba integrada 24hs              | Protocolo de pruebas    | Operación continua de todos los subsistemas con monitoreo (SG-S6)                       | 24hs sin fallas críticas                 |
| 3.2.4 | Informe de resultados              | Protocolo de pruebas    | Documento con conclusiones, desviaciones y recomendaciones                              | Informe firmado y aprobado               |
| 4.1.1 | Planos finales As-Built            | Documentación técnica   | Planos CAD actualizados reflejando modificaciones reales del prototipo                  | Planos versionados finales               |
| 4.1.2 | Fichas técnicas                    | Documentación técnica   | Especificaciones de biomateriales, componentes electrónicos y parámetros                | Fichas completas archivadas              |
| 4.1.3 | Log de decisiones                  | Documentación técnica   | Registro de cambios de diseño, justificaciones y lecciones aprendidas                   | Log completo y trazable                  |
| 4.2.1 | Materiales institucionales         | Presentación            | Pitch deck, one-pager, video demo para modelo de licenciamiento                         | Materiales de marketing finalizados      |
| 4.2.2 | Presentación al cliente            | Presentación            | Demo en vivo del prototipo a la Institución de Conservación                             | Presentación ejecutada                   |

---

*Cátedra Gestión de Proyectos · FIUNER · 2026*
