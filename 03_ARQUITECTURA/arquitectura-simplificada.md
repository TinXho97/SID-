# Arquitectura simplificada

```text
Otra app / entrada voluntaria
            ↓
   Confirmación en Android
            ↓
  Núcleo de análisis local
            ↓
 Señales y orientación explicada
```

La app Android usa Kotlin y Jetpack Compose. El núcleo Kotlin está separado de la interfaz; existe también una implementación Python de referencia para comparar comportamientos. Este esquema es conceptual: no incluye interfaces internas, código ni detalles sensibles del motor.
