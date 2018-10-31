# Block

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
|    flex     | bool, number |       false       |             flex: 1 **ó** `<yourNumber>`             |
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
