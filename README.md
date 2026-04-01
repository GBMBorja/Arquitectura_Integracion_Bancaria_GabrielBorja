# Arquitectura_Integracion_Bancaria_GabrielBorja
Test Aquitectura de Integracion

# Repositorio de Modernización Bancaria - Arquitectura de Integración

Este repositorio contiene los entregables del ejercicio práctico de arquitectura de integración para la modernización de sistemas bancarios.

## Contenido
1. [Propuesta_Arquitectura_Modernizacion.md](Propuesta_Arquitectura_Modernizacion.md): Documento detallado con el diseño y justificaciones técnicas.
2. Diagramas C4 (Contexto, Contenedores y Componentes con Mermaid).

## Instrucciones de Visualización
El documento principal está en formato Markdown. Se recomienda visualizarlo con un visor que soporte **Mermaid.js** para renderizar los diagramas.

## Resumen de la Solución
- **Estrategia Multicore:** Capa de abstracción BIAN para coexistencia de Core Tradicional y Digital.
- **Seguridad:** OAuth2/OIDC + mTLS + Tokenización para cumplimiento de LOPDP.
- **Resiliencia:** Despliegue Multi-Región con mallas de servicios (Istio) y disyuntores (Circuit Breakers).
- **Plan de Migración:** Patrón Strangler Fig para transición de bajo riesgo.
