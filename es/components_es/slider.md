# Slider

Todos necesitamos un slider en nuestras apps. Este es un componente de JavaScript creado con PanResponder y la API Animated.

<p align="center">
 <img src="https://i.imgur.com/sp42kcd.png" />
</p>

|       Prop        |    Tipo    |        Por defecto        |                                               Descripción                                               |
| :---------------: | :--------: | :-----------------------: | :-----------------------------------------------------------------------------------------------------: |
|    activeColor    |   texto    | GalioTheme.COLORS.PRIMARY |                               Esto establece el color activo del slider.                                |
|       value       |   número   |             0             |                        El valor inicial en el que el slider estará posicionado.                         |
|     disabled      |    bool    |           false           |                                     Esta prop desactiva el slider.                                      |
|   minimumValue    |   número   |             0             |                                  Establece el valor mínimo del Slider.                                  |
|   maximumValue    |   número   |            100            |                                Establece el valor máximo para el slider.                                |
|    trackStyle     | cualquiera |            {}             |                  Pasando un objeto puedes aplicar el estilo del recorrido del slider.                   |
|    thumbStyle     | cualquiera |            {}             |       Pasando un objeto puedes establecer el estilo del botón (el círculo que mueves) del slider.       |
|       step        |   número   |             0             | Esto es un marcador de intervalos. Con esto puedes fijar los valores por los que puede pasar el slider. |
| onSlidingComplete |  función   |         () => {}          |         Pasando una función flecha puedes decidir qué pasará cuando el slider llegué al final.          |
|  onSlidingStart   |  función   |         () => {}          |        Pasando una función flecha puedes decidir qué pasará cuando el slider empiece a moverse.         |
|   onValueChange   |  función   |         () => {}          |        Pasando una función flecha puede decidir qué pasará mientras el slider se esté moviendo.         |
