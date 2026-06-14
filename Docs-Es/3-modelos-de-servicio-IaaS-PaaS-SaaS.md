# Modelos de Servicio: IaaS, PaaS y SaaS

## Introducción

Un modelo de servicio define qué responsabilidades administra el proveedor cloud y cuáles permanecen bajo control del cliente.

Dependiendo del modelo elegido, el cliente puede encargarse de gran parte de la infraestructura o simplemente utilizar una aplicación lista para usar.

Los tres modelos principales son:

- Infrastructure as a Service (IaaS)
- Platform as a Service (PaaS)
- Software as a Service (SaaS)

---

## IaaS — Infrastructure as a Service

Es la categoría más flexible de servicios en la nube. Proporciona la mayor cantidad de control sobre los recursos de TI.

El proveedor cloud administra la infraestructura física, mientras que el cliente es responsable de configurar y administrar los sistemas que ejecuta sobre ella.

### Responsabilidades del proveedor

- Hardware físico
- Redes y conectividad
- Almacenamiento
- Centro de datos

### Responsabilidades del cliente

- Sistema operativo
- Middleware
- Aplicaciones
- Datos
- Configuración de seguridad

### Características

- Máximo nivel de control
- Alta flexibilidad
- Similar a administrar infraestructura tradicional
- Escalabilidad bajo demanda

**Ejemplo en Azure:** Azure Virtual Machines

---

## PaaS — Platform as a Service

PaaS proporciona un entorno administrado para desarrollar, probar y ejecutar aplicaciones.

El proveedor administra la infraestructura y la plataforma subyacente, permitiendo que el cliente se concentre en sus aplicaciones y datos.

### Responsabilidades del proveedor

- Hardware físico
- Redes
- Almacenamiento
- Sistema operativo
- Middleware
- Herramientas de desarrollo

### Responsabilidades del cliente

- Aplicaciones
- Datos
- Configuración de acceso

### Características

- Reduce tareas administrativas
- Facilita el desarrollo de aplicaciones
- Permite implementaciones rápidas
- Escalabilidad integrada

**Ejemplo en Azure:** Azure App Service

---

## SaaS — Software as a Service

SaaS proporciona aplicaciones completas listas para utilizar a través de internet.

Es el modelo con menor carga operativa para el cliente, ya que el proveedor administra prácticamente todos los componentes del servicio.

### Responsabilidades del proveedor

- Infraestructura
- Plataforma
- Aplicación
- Actualizaciones
- Seguridad del servicio

### Responsabilidades del cliente

- Datos
- Usuarios
- Configuración de cuentas y permisos

### Características

- No requiere instalación local
- Menor administración
- Acceso desde cualquier lugar
- Actualizaciones automáticas

**Ejemplo en Azure:** Microsoft 365

---

## Tabla comparativa de responsabilidades

| Recurso | IaaS | PaaS | SaaS |
|---|---|---|---|
| Información y datos | Cliente | Cliente | Cliente |
| Dispositivos | Cliente | Cliente | Cliente |
| Cuentas e identidad | Cliente | Cliente | Cliente |
| Infraestructura de identidad | Cliente | Compartida | Compartida |
| Aplicaciones | Cliente | Cliente | Proveedor |
| Controles de red | Cliente | Compartida | Proveedor |
| Sistema operativo | Cliente | Proveedor | Proveedor |
| Servidores físicos | Proveedor | Proveedor | Proveedor |
| Almacenamiento | Proveedor | Proveedor | Proveedor |

### Resumen rápido

| Modelo | Qué administra el cliente |
|---|---|
| IaaS | Sistema operativo, aplicaciones y datos |
| PaaS | Aplicaciones y datos |
| SaaS | Datos, usuarios y configuración |

---

## Resumen

Los modelos de servicio permiten elegir el nivel de control y responsabilidad que una organización quiere asumir sobre su infraestructura cloud.

- **IaaS** es ideal cuando se necesita máxima flexibilidad y control, a cambio de mayor responsabilidad administrativa.
- **PaaS** elimina la gestión de infraestructura y permite enfocarse en el desarrollo de aplicaciones.
- **SaaS** ofrece la menor carga operativa, entregando software listo para usar sin gestionar nada subyacente.

La elección del modelo correcto depende del nivel de control requerido, la capacidad técnica del equipo y los objetivos del negocio.

---

## Referencias

- [Describe cloud service types — Microsoft Learn](https://learn.microsoft.com/es-mx/training/modules/describe-cloud-service-types/)

---

[Regresar al indice](../README.es/md)
