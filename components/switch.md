# Switch

This component was built on top of React Native's Switch component and so it inherits all the props the native component has.

<p align="center">
  <img src="https://raw.githubusercontent.com/galio-org/docs/master/assets/switch-example.png" />
</p>

|         Prop        |                                      Type                                      |                               Default                              | Description |
|:-------------------:|:------------------------------------------------------------------------------:|:------------------------------------------------------------------:|:-----------:|
|        color        | oneOfType(['primary', 'theme', 'error', 'warning', 'success', 'info']), string |                      GalioTheme.COLORS.PRIMARY                     |             |
|       disabled      |                                      bool                                      |                                false                               |             |
|     initialValue    |                                      bool                                      |                                false                               |             |
|      trackColor     |                                     object                                     | { false: GalioTheme.COLORS.GREY, true: GalioTheme.COLORS.PRIMARY } |             |
| ios_backgroundColor |                                     string                                     |                       GalioTheme.COLORS.GREY                       |             |
|    onValueChange    |                                    function                                    |                              () => {}                              |             |
| ...Switch.propTypes |                                                                                |                                                                    |             |
