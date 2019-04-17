# Checkbox

Los checkboxes permiten al usuario completar tareas que involucran la toma de decisiones, como selecionar opciones, o activar-desactivar alguna configuración.

<p align="center">
  <img src="https://i.imgur.com/Vnyf1pJ.png" />
</p>

|     Prop      |                               Tipo                                |  Por defecto  |                                                  Descripción                                                  |
| :-----------: | :---------------------------------------------------------------: | :-----------: | :-----------------------------------------------------------------------------------------------------------: |
| checkboxStyle |                            cualquiera                             |     null      |                Enviando un objeto puedes aplicar el color, tamaño y mucho más de la checkbox.                 |
|  desactivada  |                               bool                                |     false     |                              Esto desactiva la posibilidad de usar la checkbox.                               |
| flexDirection | oneOf(['row', 'row-reverse', 'column', 'column-reverse']), string |     'row'     |          Quizás necesitas que la checkbox esté encima de una imagen. Puedes hacer eso con esta prop.          |
|   iconColor   |                               texto                               |    '#fff'     |                                     Esta prop cambia el color del icono.                                      |
|   iconName    |                               texto                               |    'check'    |                                          Esta prop cambia el icono.                                           |
|   iconSize    |                              número                               |      15       |                                     Esta prop cambia el tamaño del icono.                                     |
|  iconFamily   |                               texto                               | 'FontAwesome' | En caso de que necesites un icono de un paquete diferente, esta prop te ayuda a cambiar el paquete del icono. |
|     image     |                               texto                               |     null      |                              Esto te permite colocar una imagen en vez de texto.                              |
|  imageStyle   |                            cualquiera                             |     nulo      |                                    Diseña la forma en que tu imagen se ve!                                    |
| initialValue  |                               bool                                |     false     |                         Debe ser el estado inicial de la checkbox falso o verdadero?                          |
|     label     |                               texto                               |     nulo      |                                         El texto junto a la checkbox.                                         |
|  labelStyle   |                            cualquiera                             |     null      |                                    Aplica estilo al texto de la checkbox.                                     |
|   onChange    |                              función                              |   () => {}    | Esta prop toma una función de flecha y cada vez que el usuario presiona la checkbox dicha función es llamada. |
