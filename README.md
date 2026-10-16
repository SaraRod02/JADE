# Prácticas de JADE

Repositorio para desarrollar los Hands On 3, 4 y 5 de la asignatura, utilizando JADE (Java Agent DEvelopment Framework) y el lenguaje de programación Java.

## Hands On 3: HelloWorldAgent

### Objetivo
Configurar y ejecutar la plataforma JADE, compilar el agente `HelloWorldAgent` y comprobar su funcionamiento.

### Herramientas utilizadas
- Java JDK.
- JADE 4.6.0.
- Terminal de macOS.

### Código fuente
El archivo `HelloWorldAgent.java` contiene el código fuente del agente de ejemplo.

### Compilación

Se debe sustituir la ruta de ejemplo por la ubicación real del archivo `jade.jar` en el equipo.

```bash
JADE_LIB="/ruta/a/jade/lib/jade.jar"

javac -cp "$JADE_LIB" -d hands-on-3 \
  hands-on-3/HelloWorldAgent.java
```

### Ejecución

```bash
java -cp "$JADE_LIB:hands-on-3" jade.Boot -gui \
  -agents "hello:examples.hello.HelloWorldAgent"
```

### Resultado esperado
Se inicia la plataforma JADE con su interfaz gráfica y se ejecuta el agente `hello`, que muestra el saludo definido en el código fuente.

## Próximas prácticas

- **Hands On 4:** comportamientos de agentes: `OneShotAgent`, `CyclicAgent` y `GenericAgent`.
- **Hands On 5:** comunicación entre agentes: `AgenteEmisor`, `AgenteReceptor` y `BlockReceptor`.

## Autoría
SaraRod02
