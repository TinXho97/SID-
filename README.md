# SID — muestra simplificada para presentación

> Material de presentación inspirado en la organización documental del README de GanadApp. **No es el repositorio fuente ni una copia funcional de SID.** La app real se muestra aparte durante la demo.

## 1. Descripción del sistema

SID es un prototipo Android que ayuda a revisar señales observables en mensajes, enlaces y códigos QR que la persona comparte voluntariamente.

## 2. Objetivo

Ayudar a la persona a revisar el contenido antes de actuar y a elegir qué verificar por un canal oficial conocido. SID ofrece orientación; no confirma quién envió el mensaje ni certifica que sea legítimo.

## 3. Usuario previsto

Una persona que recibió un mensaje o enlace que le genera dudas y quiere revisar señales desde Android.

## 4. Alcance del prototipo

- Compartir o pegar texto y revisarlo antes del análisis.
- Revisar señales y una explicación en la pantalla de resultado.
- Leer un QR local sin abrir el destino automáticamente.
- Revisar ciertos metadatos de archivos sin abrir su contenido.

## 5. Exclusiones y límites

- SID no autentica remitentes ni decide por la persona.
- No se presenta como protección general contra fraudes.
- El firewall DNS es una variante de laboratorio con dos dominios ficticios; no forma parte de la demo principal.
- La comprensión y utilidad de las recomendaciones requieren evaluación con personas.

## 6. Evolución

Completar regresión Android, accesibilidad y evaluación de comprensión; mantener separados los experimentos de consulta de dominio y firewall hasta completar sus pruebas.

## 7. Arquitectura resumida

La interfaz Android recibe y confirma la entrada. Un núcleo Kotlin separado extrae señales y genera orientación. El repositorio original conserva también una implementación Python de referencia. Este paquete de muestra no incluye esas implementaciones.

## 8. Organización de la muestra

| Archivo | Para qué sirve |
|---|---|
| `00_REFERENCIAS/` | Alcance del prototipo y límites de la evidencia. |
| `01_PLAN_MAESTRO/` | Visión, objetivo, alcance y continuidad. |
| `02_CASOS_DE_USO/` | Un recorrido observable de la app. |
| `03_ARQUITECTURA/` | Esquema conceptual sin código fuente. |
| `04_MODELO_DATOS/` | Qué datos se usan y límites de privacidad, en resumen. |
| `06_INTERFAZ_USUARIO/` | Pantallas y recorrido principal. |
| `07_IMPLEMENTACION/` | Estado de pruebas y limitaciones verificadas. |
| `docs/` | Ficha PP3, recorrido del repositorio y guion de demo. |

## 9. Gestión y privacidad

Este repositorio público es una **copia documental de muestra**. No contiene código fuente, APK, corpus de investigación ni historial del SID original. El repositorio fuente SID permanece privado y no se modificó.
