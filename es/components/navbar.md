# NavBar

Cómo van a saber tus clientes en qué pantalla están si no añades un componente de barra de navegación?

**Uso**

Ejemplo sencillo:

```
<Navbar title="Titulo de la pantalla" />
```

**Props**

|     Prop      |     Type     | Valor por defecto |                                     Descripción                                     |
| :-----------: | :----------: | :---------------: | :---------------------------------------------------------------------------------: |
|     back      |     bool     |       false       |                        Añade un botón de "atrás" al NavBar.                         |
|  transparent  |     bool     |       false       |          Establece el color de fondo y el color del borde a 'transparente'          |
|     title     | node, string |       null        |                                  Título del NavBar                                  |
|  titleStyle   |    object    |       null        |                           Establece el estilo del título                            |
|     left      |     node     |       null        |                              Lado izquierdo del NavBar                              |
|   leftStyle   |    object    |       null        | Establece el estilo para la vista que envuelve el elemento lateral de la izquierda. |
| leftIconColor |    string    | theme.COLORS.ICON |                  Establece el color del icono del lado izquierdo.                   |
|  onLeftPress  |   function   |     () => {}      |                      Función para el lado izquierdo del navbar                      |
|     right     |     node     |       null        |                               Lado derecho del NavBar                               |
|  rightStyle   |    object    |       null        |  Establece el estilo para la vista que envuelve el elemento lateral de la derecha.  |
