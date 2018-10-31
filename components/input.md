# Input
A simple customizable input you'll love using.

**Usage**

Simple example:
```
<Input placeholder="Email" />
```

**Props**

|         Prop         |  Type  |          Default         |                                                                            Description                                                                            |
|:--------------------:|:------:|:------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| type                 | string | 'default'                | this is basically the TextInput's keyboardType prop and it has the next options: 'default', 'number-pad', 'decimal-pad', 'numeric', 'email-address', 'phone-pad'. |
| password             |  bool  | false                    | Tells the input that this is going to be a password input                                                                                                         |
| placeholderTextColor | string | theme.COLORS.PLACEHOLDER | Sets the placeholder's text color                                                                                                                                 |
| label                | string | null                     | Sets the label of the input                                                                                                                                       |
| bgColor              | string | null                     | Sets the Input's backgroundColor                                                                                                                                  |
| rounded              | bool   | false                    | Sets the corners to be rounded                                                                                                                                    |
| borderless           | bool   | false                    | Sets the Input's borderWidth to 0                                                                                                                                 |
| viewPass             | bool   | false                    | Adds the functionality of pressing a button in order to see your password's letters                                                                               |
| icon                 | string | null                     | Choose your Icon's name from Expo's icon list                                                                                                                     |
| iconColor            | string | null                     | Changes the Icon's color                                                                                                                                          |
| family               | string | null                     | Choose your Icon's family from the same list                                                                                                                      |
| color                | string | null                     | Sets the Input's text color.                                                                                                                                      |
| help                 | string | null                     | Sets a helper line for more information regarding your input.                                                                                                     |
| left                 | bool   | true                     | Sets the Icon to the left of the Input.                                                                                                                           |
| right                | bool   | false                    | Sets the Icon to the right of the Input.                                                                                                                          |
| topHelp              | bool   | true                     | Sets the helper line above the input.                                                                                                                             |
| bottomHelp           | bool   | false                    | Sets the helper line below the input.                                                                                                                             |

