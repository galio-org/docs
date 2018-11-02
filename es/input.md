# Input

Un input simple y personalizable que amarás usar.

**Uso**

Ejemplo sencillo:

```
<Input placeholder="Email" />
```

**Props**

|         Prop         |  Type  |    Valor por defecto     |                                                                                 Descripción                                                                                 |
| :------------------: | :----: | :----------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|         type         | string |        'default'         | Esto es basicamente el tipo de teclado del input de texto y tiene las siguientes opciones: 'default', 'number-pad', 'decimal-pad', 'numeric', 'email-address', 'phone-pad'. |
|       password       |  bool  |          false           |                                                         Esto le dice al inputo que va a ser un input de contraseñas                                                         |
| placeholderTextColor | string | theme.COLORS.PLACEHOLDER |                                                                Establece el color del texto del placeholder                                                                 |
|        label         | string |           null           |                                                                       Establece la etiqueta del input                                                                       |
|       bgColor        | string |           null           |                                                                    Establece el color de fondo del input                                                                    |
|       rounded        |  bool  |          false           |                                                                  Establece los bordes para ser redondeados                                                                  |
|      borderless      |  bool  |          false           |                                                                 Establece el tamaño del borde del input a 0                                                                 |
|       viewPass       |  bool  |          false           |                                                  Añade la funcionalidad de presionar un botón para poder ver la contraseña                                                  |
|         icon         | string |           null           |                                                         Elige el icono por el nombre de la lista de iconos de Expo                                                          |
|      iconColor       | string |           null           |                                                                          Cambia el color del icono                                                                          |
|        family        | string |           null           |                                                               Elige la familia del icono desde la misma lista                                                               |
|        color         | string |           null           |                                                                   Establece el color de texto del input.                                                                    |
|         help         | string |           null           |                                               Añade una linea de ayuda para añadir más información relacionada con el input.                                                |
|         left         |  bool  |           true           |                                                          Establece la posición del icono a la izquierda del input.                                                          |
|        right         |  bool  |          false           |                                                           Establece la posición del icono a la derecha del input.                                                           |
|       topHelp        |  bool  |           true           |                                                              Establece la linea de ayuda por encima del input.                                                              |
|      bottomHelp      |  bool  |          false           |                                                              Establece la linea de ayuda por debajo del input.                                                              |
