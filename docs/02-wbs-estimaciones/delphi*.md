# 📐 PERT + Delphi — Estimación de Esfuerzo
### Útero Artificial Ectogénico · Proyecto BioTech

> **Método:** Delphi con 3 expertos → promedio de O/M/P → fórmula PERT  
> **Unidad:** Horas / Persona  
> **O** = Optimista · **M** = Más probable · **P** = Pesimista

----

##  Fórmulas

| Magnitud | Fórmula | Descripción |
|----------|---------|-------------|
| **TE** | `(O + 4·M + P) / 6` | Tiempo Esperado ponderado |
| **σ** | `(P − O) / 6` | Desvío estándar (incertidumbre) |
| **Varianza** | `σ²` | Dispersión cuadrática |
| **σ_proyecto** | `√(Σ Varianzas)` | Incertidumbre total del proyecto |

---

##  Formulario Delphi — Estimaciones por Experto

> Valores en **Horas / Persona**

### 1.1 Gestión del Proyecto

| ID | Tarea | Experto 1 O·M·P | Experto 2 O·M·P | Experto 3 O·M·P | Notas |
|----|-------|-----------------|-----------------|-----------------|-------|
| 1.1.1 | Acta de Constitución | 4 · 8 · 16 | 6 · 10 · 16 | 6 · 10 · 18 | Doc formal ~5 pág: objetivos, alcance, sponsor, autoridad PM, exclusiones bioéticas |
| 1.1.2 | Plan de Gestión del Proyecto | 16 · 32 · 60 | 16 · 24 · 40 | 24 · 40 · 72 | Doc maestro: alcance + cronograma + costos + calidad + riesgos + comunicaciones |
| 1.1.3 | Registro y Estrategia de Stakeholders | 6 · 12 · 20 | 4 · 8 · 12 | 6 · 12 · 20 | ~6 stakeholders: BioTech, Conservación, Ética, Proveedores, equipo interno |
| 1.1.4 | Identificar Riesgos Iniciales | 8 · 20 · 40 | 4 · 8 · 12 | 8 · 16 · 28 | Riesgos técnicos + regulatorios + financieros + bioseguridad |
| 1.1.5 | Diagramar Presupuesto | 10 · 24 · 48 | 8 · 12 · 20 | 12 · 20 · 36 | Costear biomateriales + electrónica + bioimpresión + horas lab + personal |
| 1.1.6 | Gestionar Contratos con Proveedores | 16 · 40 · 80 | 20 · 32 · 60 | 20 · 40 · 72 | Múltiples proveedores (hidrogeles, sensores, bomba, oxigenador). Búsqueda + cotización + revisión |
| 1.1.7 | Reunión de Kick Off | 2 · 4 · 8 | 2 · 4 · 6 | 4 · 6 · 12 | Prep + coordinar asistentes + reunión + minuta |

### 1.2 Expediente Bioético y Normativo

| ID | Tarea | Experto 1 O·M·P | Experto 2 O·M·P | Experto 3 O·M·P | Notas |
|----|-------|-----------------|-----------------|-----------------|-------|
| 1.2.1 | Documentación para Comité de Ética | 24 · 56 · 120 | 16 · 24 · 48 | 24 · 40 · 72 | Expediente formal: protocolo experimental + consideraciones bioéticas + restricciones ectogénesis |
| 1.2.2 | Análisis de Implicancias y Restricciones | 20 · 40 · 80 | 8 · 12 · 20 | 16 · 28 · 48 | Investigación legal/bioética (normativa Arg + internacional) |
| 1.2.3 | Etapa de Revisión | 16 · 40 · 96 | 8 · 12 · 30 | 8 · 16 · 28 | Revisiones internas + ajustes + iteraciones antes de envío externo |
| 1.2.4 | Envío Documentación al Organismo de Ética | 2 · 6 · 12 | 1 · 2 · 3 | 2 · 8 · 16 | Preparar expediente + validar + enviar |
| 1.2.5 | ⬧ Aprobación CICUAL *(HITO)* | 0 · 0 · 0 | 0 · 0 · 0 | 0 · 0 · 0 | **HITO DE AVANCE** — trámite externo ~30–45 días calendario. No computable como esfuerzo |

### 1.3 Definición Técnica de Subsistemas

| ID | Tarea | Experto 1 O·M·P | Experto 2 O·M·P | Experto 3 O·M·P | Notas |
|----|-------|-----------------|-----------------|-----------------|-------|
| 1.3.1 | Especificaciones Fisiológicas (Lagomorfos) | 24 · 48 · 96 | 12 · 24 · 36 | 20 · 36 · 56 | Investigar fisiología O. cuniculus: presión, temperatura, pH, flujos sanguíneos |
| 1.3.2 | Matriz de Escalabilidad | 12 · 24 · 48 | 10 · 14 · 20 | 12 · 20 · 36 | Tabla S/M/L especies + fórmulas de conversión paramétrica |
| 1.3.3 | Diseño Funcional del Sistema (Arquitectura) | 24 · 56 · 120 | 16 · 24 · 40 | 24 · 40 · 72 | Arquitectura modular completa: diagrama de bloques + subsistemas + interfaces |
| 1.3.4 | Diagramas de Flujo del Sistema | 12 · 28 · 56 | 8 · 14 · 24 | 16 · 28 · 48 | Diagramas P&ID: circulación, oxigenación, diálisis, inyección de nutrientes |

### 2.1 Receptáculo Uterino

| ID | Tarea | Experto 1 O·M·P | Experto 2 O·M·P | Experto 3 O·M·P | Notas |
|----|-------|-----------------|-----------------|-----------------|-------|
| 2.1.1 | Compra de Materiales (Tercerizada) | 8 · 20 · 48 | — | 8 · 16 · 32 | Solo esfuerzo admin (cotizar, validar specs, coordinar entrega) |
| 2.1.2 | Modelado CAD del Habitáculo Uterino | 32 · 72 · 140 | 24 · 32 · 48 | 40 · 64 · 100 | Diseño 3D receptáculo escala lagomorfa (200–400 ml) |
| 2.1.3 | ⚠ Bioimpresión con Hidrogeles/Biomateriales | 40 · 95 · 140 | 40 · 80 · 120 | 60 · 100 · 160 | **ALTO RIESGO**: preparar biomateriales + calibrar + imprimir + probar + iterar |
| 2.1.4 | Pruebas de Estanqueidad y Resistencia | 16 · 40 · 88 | 14 · 24 · 50 | 20 · 36 · 60 | Banco ensayo + medir a presión nominal + corregir fugas + repetir (Stage-Gate S1) |

### 2.2 Circuitos de Soporte Vital

| ID | Tarea | Experto 1 O·M·P | Experto 2 O·M·P | Experto 3 O·M·P | Notas |
|----|-------|-----------------|-----------------|-----------------|-------|
| 2.2.1 | Diseñar y Ensamblar Módulo de Bombeo | 40 · 88 · 180 | 48 · 64 · 96 | 60 · 100 · 160 | Bomba peristáltica: diseño circuito cerrado + ensamblaje + pruebas circulación 24hs (SG-S2) |
| 2.2.2 | ⚠ Sistema de Hematosis Artificial | 64 · 140 · 300 | 60 · 90 · 124 | 80 · 130 · 200 | **TAREA MÁS COMPLEJA**: oxigenadores de membrana + integrar O₂/CO₂ + ensayos (SG-S3) |
| 2.2.3 | Módulo de Filtrado y Diálisis | 32 · 72 · 150 | 44 · 56 · 84 | 40 · 72 · 120 | Remoción desechos metabólicos + integrar componentes + ajustar umbral (SG-S4) |
| 2.2.4 | Sistema de Inyección de Nutrientes/Hormonas | 16 · 40 · 84 | 12 · 20 · 36 | 30 · 50 · 80 | Bomba infusión controlada: nutrientes/hormonas. Validar flujo regulable |

### 2.3 Electrónica y Control

| ID | Tarea | Experto 1 O·M·P | Experto 2 O·M·P | Experto 3 O·M·P | Notas |
|----|-------|-----------------|-----------------|-----------------|-------|
| 2.3.1 | Integración Matriz de Sensores (P/T/pH/Vol) | 32 · 72 · 144 | 30 · 50 · 86 | 40 · 64 · 100 | 4 sensores (P/T/pH/Vol) funcionando simultáneamente + selección + montaje + verificación |
| 2.3.2 | Interfaz de Usuario (Dashboard) | 40 · 96 · 180 | 32 · 62 · 66 | 60 · 100 · 160 | UI tiempo real: 4 variables + alarmas + gráficos históricos. Sin crashes en prueba 24hs |
| 2.3.3 | Sistema de Almacenamiento y Registro de Datos | 24 · 56 · 120 | 22 · 34 · 50 | 24 · 40 · 64 | BD persistente. Registro sin pérdidas 24hs (SG-S5) |
| 2.3.4 | Módulo de Estimulación | 20 · 48 · 100 | 20 · 28 · 40 | 20 · 36 · 60 | Presión mecánica + emisión acústica en habitáculo |

### 3.1 Integración Mecánica y Electrónica

| ID | Tarea | Experto 1 O·M·P | Experto 2 O·M·P | Experto 3 O·M·P | Notas |
|----|-------|-----------------|-----------------|-----------------|-------|
| 3.1.1 | Ensamblaje del Prototipo Físico Completo | 40 · 88 · 180 | 40 · 56 · 80 | 30 · 50 · 80 | Integración TODOS los subsistemas. Depende de que todos estén listos |
| 3.1.2 | Acoplamiento de Sensores al Dashboard | 20 · 48 · 96 | 12 · 24 · 48 | 16 · 28 · 48 | Conexión eléctrica + calibración + lectura coherente de 4 variables |
| 3.1.3 | Calibración del Sistema Completo | 32 · 72 · 150 | 20 · 32 · 56 | 20 · 36 · 60 | Ajuste fino ±5% a rangos fisiológicos lagomorfos. Iterativo hasta estabilizar |

### 3.2 Protocolo de Pruebas de Sistema

| ID | Tarea | Experto 1 O·M·P | Experto 2 O·M·P | Experto 3 O·M·P | Notas |
|----|-------|-----------------|-----------------|-----------------|-------|
| 3.2.1 | Ensayos Hidráulicos Integrados | 16 · 40 · 88 | 20 · 36 · 50 | 12 · 20 · 36 | Circulación + presión + estanqueidad del sistema integrado completo |
| 3.2.2 | Ensayos Térmicos Integrados | 16 · 40 · 88 | 12 · 24 · 48 | 12 · 20 · 36 | Validar temperatura 37–38°C (lagomorfos). Estabilidad ±0.5°C |
| 3.2.3 | Simulación Circulación Continua 24hs | 24 · 50 · 100 | 24 · 36 · 46 | 24 · 38 · 60 | Operación continua todos subsistemas + monitoreo + resolución incidentes (SG-S6) |
| 3.2.4 | Informe Final de Resultados y Conclusiones | 20 · 48 · 96 | 16 · 24 · 40 | 16 · 28 · 48 | Conclusiones + desviaciones + recomendaciones. Documento formal con análisis |
| 3.2.5 | Entrega a Tercero para Control de Calidad | 4 · 8 · 16 | 4 · 8 · 12 | 4 · 8 · 16 | Solo esfuerzo admin: preparar envío + coordinar + recibir resultado |
| 3.2.6 | ⬧ Obtención de Aprobación del Control de Calidad *(HITO)* | 0 · 0 · 0 | 0 · 0 · 0 | 0 · 0 · 0 | **HITO DE AVANCE** — validación externa ~7–14 días calendario. No computable como esfuerzo |

### 4.1 Documentación Técnica "As-Built"

| ID | Tarea | Experto 1 O·M·P | Experto 2 O·M·P | Experto 3 O·M·P | Notas |
|----|-------|-----------------|-----------------|-----------------|-------|
| 4.1.1 | Actualizar Planos Finales As-Built | 12 · 24 · 48 | 8 · 16 · 24 | 16 · 28 · 48 | Planos CAD actualizados reflejando modificaciones reales del prototipo |
| 4.1.2 | Elaborar Fichas Técnicas | 12 · 28 · 56 | 10 · 16 · 20 | 12 · 20 · 36 | Specs biomateriales + componentes electrónicos + parámetros operativos |
| 4.1.3 | Compilar Log de Decisiones | 8 · 16 · 32 | 6 · 10 · 18 | 8 · 12 · 20 | Compilar registro de cambios + justificaciones + lecciones aprendidas |
| 4.1.4 | Redactar Manual de Usuario | 20 · 40 · 84 | 18 · 26 · 40 | 20 · 36 · 56 | Operación: puesta en marcha, monitoreo, mantenimiento, troubleshooting |

### 4.2 Marketing y Licenciamiento

| ID | Tarea | Experto 1 O·M·P | Experto 2 O·M·P | Experto 3 O·M·P | Notas |
|----|-------|-----------------|-----------------|-----------------|-------|
| 4.2.1 | Reunión de Cierre | 2 · 4 · 8 | 2 · 4 · 6 | 4 · 8 · 12 | Prep + reunión con sponsor/equipo + acta de cierre + lecciones aprendidas |
| 4.2.2 | Presentación Final a Institución de Conservación | 12 · 18 · 24 | 12 · 18 · 24 | 16 · 20 · 24 | Demo en vivo del prototipo + pitch deck + one-pager |

---
*Cátedra Gestión de Proyectos · FIUNER · 2026*
