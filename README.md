# The farmer was replaced

En este repositorio iré dejando mis avances en la programacion de funciones.
El esquema es bastante directo, las funciones se almacenan en un modulo denominado funciones, estas funciones deberán ser llamadas desde main.

Hasta el momento no sé si se pueden inportar archivos de codigo al juego, por lo que la manera directa de utilizar el codigo es copiar y pegar a las cajas de texto que proporciona el juego y continuar desde allí.

## Diagrama de main con módulo funciones

```mermaid
flowchart TD
    A[main] --> B[Importar módulo funciones]
    B --> C[funciones.harvest_all]
    B --> D[funciones.explota]
    B --> E[funciones.activa_ayuda]
    C --> F[Fin]
    D --> F
    E --> F
