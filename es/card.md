# Card

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

|      Prop       |     Type     | Valor por defecto |                                                     Descripción                                                     |
| :-------------: | :----------: | :---------------: | :-----------------------------------------------------------------------------------------------------------------: |
|      card       |     bool     |       true        |                                            Añade los estilos necesarios                                             |
|     shadow      |     bool     |       true        |                                    Añade los estilos necesarios para las sombras                                    |
|   borderless    |     bool     |       false       |                                                 Añade borde al Card                                                 |
|      image      |    string    |       null        |                                     Escribe la ruta relativa o URL a la imagen                                      |
| imageBlockStyle |    string    |       null        |                                    Estilos para el Block que envuelve la imagen                                     |
|   imageStyle    |    object    |       null        |                                               Estilos para la imagen                                                |
|     avatar      |    string    |       null        |                                Escribe la ruta relativa o URL a la imagen del avatar                                |
|    location     |    string    |       null        |                               De dónde viene esto? Escribe la localización del autor                                |
|  locationColor  | bool, string |       false       | El valor por defecto de locationColor está basado en themes.COLORS.MUTED, pero puedes cambiarlo por tu propio color |
|      title      |    string    |       null        |                                        Escribe el título principal del Card                                         |
|   titleColor    |    string    |       null        |                                             Cambia el color del título                                              |
|     caption     |    string    |                   |                                             Escribe la leyenda del Card                                             |
|  captionColor   |    string    |                   |                                            Cambia el color de la leyenda                                            |
|   footerStyle   |    object    |                   |                           Estilos para el Block que envuelve la sección entera del autor                            |
