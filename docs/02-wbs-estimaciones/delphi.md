# 🎲 Estimación Delphi

> **Técnica:** Delphi · **Rondas realizadas:** 2 · **Estimadores:** Bioingeniero (E1), Biotecnólogo (E2), Esp. Materiales (E3)
## Ronda 1
| ID    | Tarea                              | E1 (hs) | E2 (hs) | E3 (hs) | Promedio | Delta |
| ----- | ---------------------------------- | ------- | ------- | ------- | -------- | ----- |
| 1.1.5 | Investigación bibliográfica        | 140     | 160     | 150     | 150      | 20    |
| 1.2.3 | Aprobación institucional (gestión) | 80      | 100     | 90      | 90       | 20    |
| 2.0.1 | Investigación biomateriales        | 200     | 240     | 220     | 220      | 40    |
| 2.0.2 | Pruebas biocompatibilidad          | 140     | 160     | 150     | 150      | 20    |
| 2.1.2 | Bioimpresión v1                    | 80      | 96      | 88      | 88       | 16    |
| 2.1.4 | Rediseño v2                        | 64      | 80      | 72      | 72       | 16    |
| 2.1.5 | Bioimpresión v2                    | 80      | 96      | 88      | 88       | 16    |
| 2.2.1 | Diseño bombeo v1                   | 140     | 160     | 150     | 150      | 20    |
| 2.2.7 | Investigación hematosis            | 180     | 200     | 190     | 190      | 20    |
| 2.2.8 | Diseño oxigenador                  | 140     | 160     | 150     | 150      | 20    |
| 2.4.6 | Dashboard v1                       | 200     | 240     | 220     | 220      | 40    |
| 3.1.5 | Resolución problemas integración   | 140     | 160     | 150     | 150      | 20    |
| 4.1.4 | Documentación científica           | 140     | 160     | 150     | 150      | 20    |
| **TOTAL** | | | | | **[COMPLETAR]** | |

> **Delta:** diferencia entre la estimación máxima y mínima de la ronda. Si Delta > [umbral definido por el grupo], se discute y se realiza la ronda 2.

## Discusión entre rondas
Investigación de biomateriales (2.0.1):

E1: "Necesitamos probar al menos 5-6 hidrogeles diferentes, cada uno requiere caracterización" (200hs)
E2: "Más las pruebas de resistencia mecánica, degradación, esterilización" (240hs)
E3: "Y hay que documentar todo para el comité de ética" (220hs)

Consenso: Es trabajo de laboratorio intensivo, ir con estimación conservadora.
Dashboard (2.4.6):

E2: "Es solo una interfaz web con gráficos" (240hs)
E1: "No, tiene que manejar 4 sensores en tiempo real, alarmas, registro en BD" (200hs)
E3: "Y funcionar sin crashes durante pruebas de 48hs continuas" (220hs)


## Ronda 2

| ID                | Tarea                              | E1 (hs) | E2 (hs) | E3 (hs) | Promedio    | Delta            |
| ----------------- | ---------------------------------- | ------- | ------- | ------- | ----------- | ---------------- |
| 1.1.5             | Investigación bibliográfica        | 140     | 160     | 150     | 150         | 20               |
| 1.2.3             | Aprobación institucional (gestión) | 80      | 100     | 90      | 90          | 20               |
| 2.0.1             | Investigación biomateriales        | 200     | 240     | 220     | 220         | 40               |
| 2.0.2             | Pruebas biocompatibilidad          | 140     | 160     | 150     | 150         | 20               |
| 2.1.2             | Bioimpresión v1                    | 80      | 96      | 88      | 88          | 16               |
| 2.1.4             | Rediseño v2                        | 64      | 80      | 72      | 72          | 16               |
| 2.1.5             | Bioimpresión v2                    | 80      | 96      | 88      | 88          | 16               |
| 2.2.1             | Diseño bombeo v1                   | 140     | 160     | 150     | 150         | 20               |
| 2.2.7             | Investigación hematosis            | 180     | 200     | 190     | 190         | 20               |
| 2.2.8             | Diseño oxigenador                  | 140     | 160     | 150     | 150         | 20               |
| 2.4.6             | Dashboard v1                       | 200     | 240     | 220     | 220         | 40               |
| 3.1.5             | Resolución problemas integración   | 140     | 160     | 150     | 150         | 20               |
| 4.1.4             | Documentación científica           | 140     | 160     | 150     | 150         | 20               |
| ID                | Tarea                              | E1 (hs) | E2 (hs) | E3 (hs) | Promedio R2 | Estimación Final |
| 1.1.5             | Investigación bibliográfica        | 145     | 155     | 150     | 150         | **150 hs**       |
| 1.2.3             | Aprobación institucional           | 85      | 95      | 90      | 90          | **90 hs**        |
| 2.0.1             | Investigación biomateriales        | 210     | 230     | 220     | 220         | **220 hs**       |
| 2.0.2             | Pruebas biocompatibilidad          | 145     | 155     | 150     | 150         | **150 hs**       |
| 2.1.2             | Bioimpresión v1                    | 84      | 92      | 88      | 88          | **90 hs**        |
| 2.1.5             | Bioimpresión v2                    | 84      | 92      | 88      | 88          | **90 hs**        |
| 2.2.7             | Investigación hematosis            | 185     | 195     | 190     | 190         | **190 hs**       |
| 2.4.6             | Dashboard v1                       | 210     | 230     | 220     | 220         | **220 hs**       |
| 3.1.5             | Resolución problemas               | 145     | 155     | 150     | 150         | **150 hs**       |
| 4.1.4             | Documentación científica           | 145     | 155     | 150     | 150         | **150 hs**       |
| **TOTAL CRÍTICO** |                                    |         |         |         |             | **~1500 hs**     |

## Conversión a duración

| ID                | Tarea                              | Esfuerzo | Recursos          | Dedicación     | Duración       |
| ----------------- | ---------------------------------- | -------- | ----------------- | -------------- | -------------- |
| 1.1.5             | Invest. bibliográfica              | 150hs    | Biotecnólogo (1)  | 75%            | **25 días**    |
| 1.2.3             | Aprobación ética                   | 90hs     | Director (1)      | 30% (trámites) | **30 días** ⏰  |
| 2.0.1             | Invest. biomateriales              | 220hs    | Esp. Mat (1)      | 90%            | **30 días**    |
| 2.0.2             | Pruebas biocompat.                 | 150hs    | Esp. Mat (1)      | 90%            | **20 días**    |
| 2.1.2             | Bioimpresión v1                    | 90hs     | Esp. Mat (1)      | 80%            | **12 días**    |
| 2.2.7             | Invest. hematosis                  | 190hs    | Biotec (1)        | 90%            | **25 días**    |
| 2.4.6             | Dashboard v1                       | 220hs    | Desarrollador (1) | 90%            | **30 días**    |
| 3.1.5             | Resolución problemas               | 150hs    | Equipo (3)        | 75%            | **20 días** ⚠️ |
| 4.1.4             | Doc. científica                    | 150hs    | Biotec (1)        | 90%            | **20 días**    |

> **Fórmula:** Duración = Esfuerzo / (Recursos × Dedicación × Hs/día)

---

*Cátedra Gestión de Proyectos · FIUNER · 2026*
