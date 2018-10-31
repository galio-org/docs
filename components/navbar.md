# NavBar
How are your clients going to know which screen they're visiting if you don't have a navbar component?

**Usage**

Simple example:
```
<Navbar title="Screen Title" />
```

**Props**

|      Prop     |     Type     |      Default      |                          Description                          |
|:-------------:|:------------:|:-----------------:|:-------------------------------------------------------------:|
| back          | bool         | false             | Adds a back button for your navBar.                           |
| transparent   | bool         | false             | Sets the backgroundColor and borderColor to 'transparent'     |
| title         | node, string | null              | Title of the NavBar                                           |
| titleStyle    | object       | null              | Sets the styling for the title                                |
| left          | node         | null              | Left side of the NavBar                                       |
| leftStyle     | object       | null              | Sets the styling for the View wrapping the left side element. |
| leftIconColor | string       | theme.COLORS.ICON | Sets the color of the left side's icon.                       |
| onLeftPress   | function     | () => {}          | Function for the left side of the navbar                      |
| right         | node         | null              | Right side of the NavBar                                      |
| rightStyle    | object       | null              | Sets the styling for the View wrapping the left side element. |
