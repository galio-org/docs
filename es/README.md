# Galio

<img src="https://raw.githubusercontent.com/galio-org/galio/master/assets/galio_thumbnail.jpg">

Galio es un projecto 100% libre y gratis, bajo licencia MIT. Permanecerá siempre gratis para su uso, respaldado por una comunidad genial alrededor de todo el mundo. Cuidadosamente creada, con componentes listos para usar, tipografía y un tema base precioso que se adapta a cualquier projecto, estarás creando software con estilo. Creada con ejemplos de apps reales, con demos de uso de los componentes y guías que te permiten crear y correr tu aplicación movil más rápido que nunca.

## Cómo instalar Galio

Añádelo como una dependencia con npm/yarn:

`npm install galio-framework`
ó
`yarn install galio-framework`

A continuación importa los componentes que quieras usar en tu aplicación:

`import { Text } from 'galio-framework'`

Parece sencillo verdad? Usa los componentes de Galio tal y como lo harías normalmente con otros componentes.

```
render() {
  return (
    <View>
      <Text p muted>Hola, Soy un componente de Galio</Text>
    </View>
  );
}
```

# Componentes

Estamos constantemente buscando nuevas formas de mejorar y crear más componentes. Permanece atento/a y constrúyelos junto a nosotros.

## Block

El componente por excelencia usado para crear prácticamente todo en tu app.

**Uso**

Ejemplo sencillo:

```
<Block>{children}</Block>
```

**Props**

|    Prop     |     Tipo     | Valor por defecto |                    Descripción                     |
| :---------: | :----------: | :---------------: | :------------------------------------------------: |
|   bottom    |     bool     |       false       |    alignItems: 'flex-end' alignSelf: 'flex-end'    |
|    card     |     bool     |       false       | changes the View's border-radus, -width and -color |
|   center    |     bool     |       false       |      alignItems: 'center' alignSelf: 'center'      |
|    flex     | bool, number |       false       |             flex: 1 **ó** <yourNumber>             |
|    fluid    |     bool     |       false       |                   width: 'auto'                    |
|   height    |    number    |       null        |             cambia la altura del Block             |
|    left     |     bool     |       false       |              alignItems: 'flex-start'              |
|   middle    |     bool     |       false       |      alignItems: 'center' alignSelf: 'center'      |
|    right    |     bool     |       false       |              alignItems: 'flex-start'              |
|     row     |     bool     |       false       |                flexDirection: 'row'                |
|    safe     |     bool     |       false       |       Envuelve el Bloque en una SafeAreaView       |
|   shadow    |     bool     |       false       |               Añade sombra al Block                |
| shadowColor |    string    |       null        |            Cambia el color de la sombra            |
|    space    |    string    |       null        | Las opciones son: 'between', 'around' or 'evenly'  |
|     top     |     bool     |       false       |  alignItems: 'flex-start' alignSelf: 'flex-start'  |
|    width    |    number    |       null        |             Cambia el ancho del Block              |

## Button

Un bonito botón que encaja incluso con los desarrolladores más exigente.

**Uso**

Ejemplo sencillo:

```
<Button>Pulsa aquí!</Button>
```

**Props**

|             Prop              |     Type     | Valor por defecto  |                                                      Descripción                                                       |
| :---------------------------: | :----------: | :----------------: | :--------------------------------------------------------------------------------------------------------------------: |
| ...TouchableOpacity.propTypes |              |                    |                                                                                                                        |
|          capitalize           |     bool     |       false        |                                      Transforma la primera letra en una mayúscula                                      |
|             color             |    string    |     'primary'      |          Las opciones son: 'primary', 'theme', 'error', 'warning', 'succes', 'transparent' o tu propio color           |
|           disabled            |     bool     |       false        |                                                   Desactiva el botón                                                   |
|             icon              | bool, string |       false        |                                    Coge el icono que quieras de los que ofrece Expo                                    |
|           iconColor           | bool, string | theme.COLORS.BLACK |                                              Establece el color del icono                                              |
|          iconFamily           | bool, string |       false        |                     Escoge la familia de iconos que encaje con el icono que hayas elegido de Expo                      |
|           iconSize            |    number    |         14         |                                             Establece el tamaño del icono                                              |
|            loading            |     bool     |       false        |                                  Usa el <ActivityIndicator /> para el efecto de carga                                  |
|          loadingSize          |    string    |      'small'       |                                           Las opciones son: 'small', 'large'                                           |
|           lowercase           |     bool     |       false        |                                        Convierte todas las letras a minúsculas                                         |
|           onlyIcon            |     bool     |       false        |                                 Estilo específico para poner solo un icono en el botón                                 |
|            opacity            |    number    |        0.8         |                                              Cambia la opacidad del botón                                              |
|            radius             |    number    |         0          |                                               Cambia el radio del botón                                                |
|          shadowColor          | bool, string |       false        | El valor por defecto de shadowColor está basado en el color del botón, pero puedes establecer un shadoColor específico |
|          shadowless           |     bool     |       false        |                                                   Elimina la sombra                                                    |
|             size              |    number    |      'large'       |                                           Las opciones son: 'large', 'small'                                           |
|           uppercase           |     bool     |       false        |                                        Convierte todas las letras en mayúsculas                                        |

## Card

Dijo alguién que necesitabas una Card? Menos mal que tenemos una.

**Uso**

Ejemplo sencillo:

```
<Card
  neutral
  fullBackgroundImage
  image="https://images.unsplash.com/photo-1536567893079-f54abdc73dc2?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=e6a56a131b11a6366446c42381192329&auto=format&fit=crop&w=1350&q=80"
  authorImageSrc="http://i.pravatar.cc/100"
  authorTitle="Offset"
  authorSubTitle="Hace 420 minutos"
/>
```

**Props**

|      Prop       |     Type     | Default |                                                     Descripción                                                     |
| :-------------: | :----------: | :-----: | :-----------------------------------------------------------------------------------------------------------------: |
|      card       |     bool     |  true   |                                            Añade los estilos necesarios                                             |
|     shadow      |     bool     |  true   |                                    Añade los estilos necesarios para las sombras                                    |
|   borderless    |     bool     |  false  |                                                 Añade borde al Card                                                 |
|      image      |    string    |  null   |                                     Escribe la ruta relativa o URL a la imagen                                      |
| imageBlockStyle |    string    |  null   |                                    Estilos para el Block que envuelve la imagen                                     |
|   imageStyle    |    object    |  null   |                                               Estilos para la imagen                                                |
|     avatar      |    string    |  null   |                                Escribe la ruta relativa o URL a la imagen del avatar                                |
|    location     |    string    |  null   |                               De dónde viene esto? Escribe la localización del autor                                |
|  locationColor  | bool, string |  false  | El valor por defecto de locationColor está basado en themes.COLORS.MUTED, pero puedes cambiarlo por tu propio color |
|      title      |    string    |  null   |                                        Escribe el título principal del Card                                         |
|   titleColor    |    string    |  null   |                                             Cambia el color del título                                              |
|     caption     |    string    |         |                                             Escribe la leyenda del Card                                             |
|  captionColor   |    string    |         |                                            Cambia el color de la leyenda                                            |
|   footerStyle   |    object    |         |                           Estilos para el Block que envuelve la sección entera del autor                            |

## Icono

Ese iconito de Facebook nunca se vio tan bien.

**Uso**

Ejemplo sencillo:

```
<Icon name="pin-3" family="Galio" color={rgb(100,120,40)} size={10} />
```

**Props**

|  Prop  |  Type  | Valor por defecto  |                        Descripción                        |
| :----: | :----: | :----------------: | :-------------------------------------------------------: |
|  name  | string |        null        | Elije el nombre de tu icono de la lista de iconos de Expo |
| family | string |        null        |      Elije la familia del icono desde la misma lista      |
|  size  | number |  theme.SIZES.BASE  |           Esto establece el tamaño de tu icono            |
| color  | string | theme.COLORS.BLACK |            Esto establece el color de tu icono            |

## Input

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

## NavBar

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

## Texto

It's never been easier to write and style text. We're using a helper function to normalize the next so that it could look good on any kind of device.

**Uso**

Ejemplo sencillo:

```
<Text p>Galio es increíble</Text>
```

**Props**

|  Prop  |  Type  | Valor por defecto |                  Descripción                   |
| :----: | :----: | :---------------: | :--------------------------------------------: |
|   h1   |  bool  |       false       |     Establece el tamaño del texto a 44px.      |
|   h2   |  bool  |       false       |     Establece el tamaño del texto a 38px.      |
|   h3   |  bool  |       false       |     Establece el tamaño del texto a 30px.      |
|   h4   |  bool  |       false       |     Establece el tamaño del texto a 24px.      |
|   h5   |  bool  |       false       |     Establece el tamaño del texto a 18px.      |
|   p    |  bool  |       false       |     Establece el tamaño del texto a 16px.      |
|  size  | number |         0         |         Establece el tamaño del texto.         |
| color  | string |       null        |         Establece el color del texto.          |
| muted  |  bool  |       false       | Cambia el color del texto a theme.COLORS.MUTED |
|  bold  |  bool  |       false       |  Establece el peso/grosor del texto a 'bold'.  |
| italic |  bool  |       false       | Establece el peso/grosor del texto a 'italic'. |
