# Switch

Este componente ha sido creado a partir del componente primitivo que provee React Native, así que hereda todas las props del componente original.

<p align="center">
  <img src="https://i.imgur.com/0HX86f2.png" />
</p>

|        Prop         |                                      Tipo                                      |                            Por defecto                             | Descripción |
| :-----------------: | :----------------------------------------------------------------------------: | :----------------------------------------------------------------: | :---------: |
|        color        | oneOfType(['primary', 'theme', 'error', 'warning', 'success', 'info']), string |                     GalioTheme.COLORS.PRIMARY                      |             |
|     desactivado     |                                      bool                                      |                               falso                                |             |
|    initialValue     |                                      bool                                      |                               falso                                |             |
|     trackColor      |                                     objeto                                     | { false: GalioTheme.COLORS.GREY, true: GalioTheme.COLORS.PRIMARY } |             |
| ios_backgroundColor |                                     texto                                      |                       GalioTheme.COLORS.GREY                       |             |
|      onChange       |                                    función                                     |                              () => {}                              |             |
| ...Switch.propTypes |                                                                                |                                                                    |             |
