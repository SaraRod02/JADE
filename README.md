# JADE - Hands On

Repositorio de prácticas realizadas con **JADE (Java Agent DEvelopment Framework)**, un framework para desarrollar aplicaciones basadas en agentes inteligentes utilizando Java.

## Requisitos

- Java JDK instalado.
- JADE 4.6.0.
- Git para el control de versiones.

## Estructura del repositorio

```text
JADE/
├── README.md
├── hands-on-3/
│   └── HelloWorldAgent.java
├── hands-on-4/
│   ├── CyclicAgent.java
│   ├── GenericAgent.java
│   └── OneShotAgent.java
└── hands-on-5/
    ├── AgenteEmisor.java
    ├── AgenteReceptor.java
    └── BlockReceptor.java
```

## Hands On 3: Hello World Agent

En esta práctica se creó y ejecutó un agente básico con JADE para comprender su estructura y ciclo de vida.

**Archivo:** `HelloWorldAgent.java`

**Objetivo:** Familiarizarse con la creación y ejecución de agentes en JADE.

## Hands On 4: Agent Behaviours

En esta práctica se trabajó con diferentes tipos de comportamientos que permiten definir las acciones de un agente.

**Archivos:**
- `CyclicAgent.java`: ejecuta repetidamente su comportamiento.
- `GenericAgent.java`: realiza acciones hasta cumplir una condición de finalización.
- `OneShotAgent.java`: ejecuta una acción una sola vez.

**Objetivo:** Comprender el uso de los comportamientos en los agentes JADE.

## Hands On 5: Agent Messaging

En esta práctica se implementó la comunicación entre agentes mediante mensajes ACL (*Agent Communication Language*).

**Archivos:**
- `AgenteEmisor.java`: crea y envía un mensaje al agente receptor.
- `AgenteReceptor.java`: recibe y muestra el mensaje enviado.
- `BlockReceptor.java`: espera la llegada de un mensaje utilizando el método `block()` cuando no hay mensajes disponibles.

**Objetivo:** Comprender el envío y la recepción de mensajes entre agentes, así como el uso de comportamientos para gestionar la comunicación.

**Resultado:** Se comprobó la comunicación entre el emisor y ambos receptores. El mensaje de prueba fue:

`I just calculated the Simple Linear Regression`

## Tecnologías utilizadas

- Java
- JADE 4.6.0
- Git y GitHub

## Autoría

Prácticas desarrolladas como parte de las actividades académicas de programación con agentes JADE.

