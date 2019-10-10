# Input
Built on top of React Native's `TextInput` component, this basic component which allows the user to enter text was styled based on Galio's own identity theme.

<p align="center">
 <img src="assets/10.png" />
</p>

### Usage
Imports:
```js
import { Input, Block } from 'galio-framework';
```

<p align="center">
  <img src="https://raw.githubusercontent.com/galio-org/docs/master/assets/input_simple.png" alt="TextInput simple example react native" />
</p>

Code example:
```jsx
<Input placeholder="regular" />
<Input placeholder="theme" color={theme.COLORS.THEME} style={{ borderColor: theme.COLORS.THEME }} placeholderTextColor={theme.COLORS.THEME} />
<Input placeholder="info" color={theme.COLORS.INFO} style={{ borderColor: theme.COLORS.INFO }} placeholderTextColor={theme.COLORS.INFO}/>
<Input placeholder="warning" color={theme.COLORS.WARNING} style={{ borderColor: theme.COLORS.WARNING }} placeholderTextColor={theme.COLORS.WARNING}/>
<Input placeholder="error" color={theme.COLORS.ERROR} style={{ borderColor: theme.COLORS.ERROR }} placeholderTextColor={theme.COLORS.ERROR}/>
<Input placeholder="success" color={theme.COLORS.SUCCESS} style={{ borderColor: theme.COLORS.SUCCESS }} placeholderTextColor={theme.COLORS.SUCCESS}/>
```
<p align="center">
  <img src="https://raw.githubusercontent.com/galio-org/docs/master/assets/input_advanced.png" alt="Input advanced example react native" />
</p>

Code example:
```jsx
<Input placeholder="password" password viewPass />
<Input placeholder="rounded input" rounded />
<Input
  placeholder="Input with Icon on right"
  right
  icon="heart"
  family="antdesign"
  iconSize={14}
  iconColor="red"
/>
<Input
  placeholder="Input with custom styling and help"
  style={{ borderColor: "red" }}
  help="Bottom help text"
  bottomHelp
  placeholderTextColor="#4F8EC9"
/>
```

### Props

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

