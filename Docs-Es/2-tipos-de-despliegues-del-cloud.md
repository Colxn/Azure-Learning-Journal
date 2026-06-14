# Tipos de Despliegue del Cloud

## Introducción

Un modelo de despliegue define cómo se implementan y organizan los recursos de Cloud Computing.
Determina quién tiene acceso a los recursos, quién los administra y dónde se encuentran físicamente.

Microsoft Azure ofrece tres modelos principales de despliegue:

- Nube Pública (Public Cloud)
- Nube Privada (Private Cloud)
- Nube Híbrida (Hybrid Cloud)

---

## Public Cloud

La nube pública utiliza infraestructura propiedad de un proveedor cloud como Microsoft Azure.
Los recursos son compartidos entre múltiples clientes, aunque cada organización mantiene sus datos y servicios aislados.

### Características

- No requiere inversión inicial en hardware
- Escalabilidad prácticamente ilimitada
- Implementación rápida de recursos
- Pago por uso (Pay-As-You-Go)

**Ejemplo:** una empresa crea máquinas virtuales en Azure sin comprar servidores físicos.

---

## Private Cloud

La nube privada está dedicada exclusivamente a una sola organización.
Los recursos no se comparten con otros clientes y la organización mantiene un mayor nivel de control sobre la infraestructura.

### Características

- Mayor control sobre recursos y seguridad
- Infraestructura dedicada
- Personalización avanzada
- Requiere inversión y mantenimiento

**Ejemplo:** una organización implementa un entorno virtualizado con VMware para alojar sus aplicaciones internas sin depender de proveedores externos.

---

## Hybrid Cloud

La nube híbrida combina infraestructura local (on-premises) con servicios de nube pública.
Permite mover datos y aplicaciones entre ambos entornos según las necesidades del negocio.

Microsoft Azure extiende el modelo híbrido mediante **Azure Arc**, que permite gestionar recursos locales y multicloud desde un único panel de control en Azure.

### Características

- Máxima flexibilidad
- Permite mantener sistemas críticos localmente
- Aprovecha la escalabilidad de la nube pública
- Facilita la migración gradual al cloud

**Ejemplo:** una empresa almacena información sensible localmente mientras ejecuta aplicaciones web en Azure.

---

## Comparación de Modelos de Despliegue

| | Public Cloud | Private Cloud | Hybrid Cloud |
|---|---|---|---|
| **Inversión inicial** | No requiere CAPEX | Requiere inversión en infraestructura | Combina inversión local y servicios cloud |
| **Escalabilidad** | Rápida y prácticamente ilimitada | Limitada al hardware disponible | Flexible según el entorno |
| **Recursos** | Compartidos entre clientes | Dedicados a una organización | Locales y cloud según necesidad |
| **Administración** | Menor responsabilidad para el cliente | Mayor responsabilidad administrativa | Administración compartida |
| **Modelo de costos** | Pago por consumo (OPEX) | Costos de operación propios | Costos combinados |

---

## Resumen

Los modelos de despliegue permiten elegir cómo consumir servicios cloud según las necesidades de cada organización.

- **Public Cloud** prioriza velocidad y reducción de costos.
- **Private Cloud** ofrece mayor control y personalización.
- **Hybrid Cloud** combina las ventajas de ambos modelos.

La elección dependerá de factores como seguridad, presupuesto, cumplimiento normativo y flexibilidad operativa.

---

## Referencias

- [Define cloud models — Microsoft Learn](https://learn.microsoft.com/es-mx/training/modules/describe-cloud-compute/5-define-cloud-models)

[Regresar al indice](../README.es.md)
