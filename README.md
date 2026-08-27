# TRACEX — Sistema de Gestión Logística
TRACEX es un sistema informático diseñado para gestionar de forma integral las operaciones de envío y distribución de paquetes de una empresa de logística.

El proyecto fue desarrollado como trabajo práctico final de la asignatura Principios de Diseño de Sistemas de la Universidad Nacional de La Matanza (UNLaM).

Descripción

El sistema permite gestionar el ciclo completo de un envío, desde su registro y pago hasta la entrega o devolución al remitente.

Entre sus principales funcionalidades se encuentran:

Registro de clientes, empleados y sus roles.
Registro de envíos y características de los paquetes.
Selección del tipo de servicio y zona de destino.
Cálculo automático del importe del envío.
Registro y confirmación del pago.
Generación de códigos únicos de seguimiento.
Generación de etiquetas de envío.
Seguimiento del paquete durante las distintas etapas logísticas.
Registro de eventos mediante el escaneo del código de seguimiento.
Actualización del estado visible para el cliente.
Registro de entregas e intentos fallidos.
Gestión de reintentos y retiro en sucursal.
Inicio del proceso de devolución al remitente.
Generación de informes diarios sobre el estado de los envíos.
Diseño del sistema

El sistema fue modelado utilizando UML, principalmente mediante:

Diagrama de clases de diseño.
Diagramas de secuencia correspondientes a los principales casos de uso.

Durante el diseño se aplicaron distintos patrones GRASP para distribuir las responsabilidades entre las clases y lograr:

Alta cohesión.
Bajo acoplamiento.
Mejor mantenibilidad.
Separación adecuada de responsabilidades.
Mayor facilidad para extender el sistema.

Entre los aspectos analizados se encuentra la distribución de responsabilidades entre controladores, gestores, entidades y servicios.

Arquitectura y componentes

El diseño contempla diferentes componentes para separar las responsabilidades del sistema, entre ellos:

Controllers: recepción y coordinación de las solicitudes provenientes de los actores.
Gestores: coordinación de la lógica correspondiente a los distintos procesos del sistema.
Entidades: representación de los objetos principales del dominio.
Repositorios: persistencia y recuperación de información.
Servicios: encapsulamiento de operaciones específicas como cálculo de importes, generación de códigos, facturas, etiquetas y notificaciones.
Tecnologías y conceptos

Lenguaje / herramientas

UML
PlantUML
Programación Orientada a Objetos

Conceptos aplicados

Patrones GRASP
Responsabilidades y colaboración entre objetos
Alta cohesión y bajo acoplamiento
Diseño orientado a objetos
Diagramas de clases
Diagramas de secuencia
Análisis de casos de uso
Documentación

El repositorio contiene la documentación y los diagramas desarrollados durante el proyecto.

Diagramas
Diagrama de clases de diseño
Diagramas de secuencia
Justificación de las decisiones de diseño
Aplicación de patrones GRASP
Contexto académico

Asignatura: Principios de Diseño de Sistemas
Universidad: Universidad Nacional de La Matanza
Proyecto: Trabajo Práctico Final
Sistema: TRACEX — Gestión de envíos y distribución
