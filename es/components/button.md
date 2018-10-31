# Button

Un bonito botón que encaja incluso con los desarrolladores más exigentes.

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
