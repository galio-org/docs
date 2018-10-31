# Button
A nice button which suits even the most picky developers.

**Usage**

Simple example:
```
<Button>Press here!</Button>
```

**Props**

|              Prop             |     Type     |       Default      |                                              Description                                             |
|:-----------------------------:|:------------:|:------------------:|:----------------------------------------------------------------------------------------------------:|
| ...TouchableOpacity.propTypes |              |                    |                                                                                                      |
| capitalize                    |     bool     |        false       | Transforms the first character in a capital letter                                                   |
| color                         |    string    |      'primary'     |  your options are: 'primary', 'theme', 'error', 'warning', 'succes', 'transparent' or your own color |
| disabled                      |     bool     |        false       |                                          Disables the button                                         |
| icon                          | bool, string |        false       |                             pick whatever icon you want from Expo's icons                            |
| iconColor                     | bool, string | theme.COLORS.BLACK | sets the icon's color                                                                                |
| iconFamily                    | bool, string |        false       | pick whatever icon family suits the icon you chose from Expo's icons                                 |
| iconSize                      |    number    |         14         |                                         sets the icon's size                                         |
| loading                       |     bool     |        false       |                         Uses the <ActivityIndicator /> for the loading effect                        |
| loadingSize                   |    string    |       'small'      |                                  your options are: 'small', 'large'                                  |
| lowercase                     |     bool     |        false       | makes all letters lowercase                                                                          |
| onlyIcon                      |     bool     |        false       | adds specific styling for using only an icon in your button                                          |
| opacity                       |    number    |         0.8        | changes the button's opacity                                                                         |
| radius                        |    number    |          0         | changes the button's radius                                                                          |
| shadowColor                   | bool, string |        false       | the default shadowColor is based on the button's color but you can also write a specific shadowColor |
| shadowless                    |     bool     |        false       | removes shadow                                                                                       |
| size                          |    number    |       'large'      | your options are: 'large', 'small'                                                                   |
| uppercase                     |     bool     |        false       | makes all letters uppercase                                                                          |
