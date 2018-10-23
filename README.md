# Galio 

<img src="https://raw.githubusercontent.com/galio-org/galio/master/assets/galio_thumbnail.jpg">

Galio is a 100% free and open source project, licensed under MIT. It will always remain free to use, powered by a massive world-wide community. Carefully crafted. Ready-made components, typography, and a gorgeous base theme that adaps to each project. You'll be building in style. Built with real app examples, component demos, guides, and how-to's to get you up and running with mobile apps faster than ever before.

## How to install

Just add it as an npm/yarn dependency:

```npm install galio-framework```
or
```yarn install galio-framework```

And just import the component you want in your application:

```import { Text } from 'galio-framework'```

This seems really easy right? Just use your component like you would normally do with any other component.

```
render() {
  return (
    <View>
      <Text p muted>Hi, I'm a Galio component</Text>
    </View>
  );
}
```

# Components

We're always finding new ways to improve and create more components. Watch us closely and build with us.


## Block
The main component used to create almost everything in your app.

**Usage**

Simple example:
```
<Block>{children}</Block>
```

**Props**

|     Prop    |     Type     | Default |                     Description                    |
|:-----------:|:------------:|:-------:|:--------------------------------------------------:|
| bottom      |     bool     |  false  |    alignItems: 'flex-end' alignSelf: 'flex-end'    |
| card        |     bool     |  false  | changes the View's border-radus, -width and -color |
| center      |     bool     |  false  |      alignItems: 'center' alignSelf: 'center'      |
| flex        | bool, number |  false  |             flex: 1 **or** <yourNumber>            |
| fluid       |     bool     |  false  |                    width: 'auto'                   |
| height      |    number    |   null  | changes the height of the Block                    |
| left        |     bool     |  false  | alignItems: 'flex-start'                           |
| middle      |     bool     |  false  |      alignItems: 'center' alignSelf: 'center'      |
| right       |     bool     |  false  |              alignItems: 'flex-start'              |
| row         |     bool     |  false  |                flexDirection: 'row'                |
| safe        |     bool     |  false  | Wraps the Block with a SafeAreaView                |
| shadow      |     bool     |  false  | adds shadow on the Block                           |
| shadowColor |    string    |   null  | changes the shadow's color                         |
| space       |    string    |   null  | your options are: 'between', 'around' or 'evenly'  |
| top         |     bool     |  false  |  alignItems: 'flex-start' alignSelf: 'flex-start'  |
| width       |    number    |   null  | changes the width of the Block                     |

## Button
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

## Card
Did anybody say you need a card? Good think we have one.

**Usage**

Simple example:
```
<Card 
  neutral
  fullBackgroundImage
  image="https://images.unsplash.com/photo-1536567893079-f54abdc73dc2?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=e6a56a131b11a6366446c42381192329&auto=format&fit=crop&w=1350&q=80"
  authorImageSrc="http://i.pravatar.cc/100"
  authorTitle="Offset"
  authorSubTitle="420 minutes ago"
/>
```

**Props**

|       Prop      |     Type     | Default |                                            Description                                           |
|:---------------:|:------------:|:-------:|:------------------------------------------------------------------------------------------------:|
| card            |     bool     |   true  | adding the necessary styles                                                                      |
| shadow          |     bool     |   true  | adding the necessary styles for shadows                                                          |
| borderless      |     bool     |  false  | adding the card's border                                                                         |
| image           |    string    | null    | write your relative path or URL to the image                                                     |
| imageBlockStyle |    string    | null    | styles for the Block wrapping the Image                                                          |
| imageStyle      |    object    | null    | styles for the Image                                                                             |
| avatar          |    string    | null    | write your relative path or URL to the avatar's image                                            |
| location        |    string    | null    | where is this coming from? write the location of the author                                      |
| locationColor   | bool, string | false   | the default locationColor is based on themes.COLORS.MUTED, but you can also write your own color |
| title           | string       | null    | write your main card's title                                                                     |
| titleColor      | string       | null    | change your title's color                                                                        |
| caption         | string       |         | write your main card's title                                                                     |
| captionColor    | string       |         | change your caption's color                                                                      |
| footerStyle     | object       |         | styles for the block wrapping the whole author's section                                         |

## Icon
That little Facebook icon never looked better.

**Usage**

Simple example:
```
<Icon name="pin-3" family="Galio" color={rgb(100,120,40)} size={10} />
```

**Props**

|  Prop  |  Type  |       Default      |                  Description                  |
|:------:|:------:|:------------------:|:---------------------------------------------:|
| name   | string | null               | Choose your Icon's name from Expo's icon list |
| family | string | null               | Choose your Icon's family from the same list  |
| size   | number | theme.SIZES.BASE   | This sets your Icon's size                    |
| color  | string | theme.COLORS.BLACK | This sets your Icon's color                   |

## Input
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

## NavBar
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

## Text
It's never been easier to write and style text. We're using a helper function to normalize the next so that it could look good on any kind of device.

**Usage**

Simple example:

```
<Text p>Galio is awesome</Text>
```

**Props**

|  Prop  |  Type  | Default |                  Description                 |
|:------:|:------:|:-------:|:--------------------------------------------:|
| h1     |  bool  | false   | Sets the text's fontSize to 44px.            |
| h2     |  bool  | false   | Sets the text's fontSize to 38px.            |
| h3     |  bool  | false   | Sets the text's fontSize to 30px.            |
| h4     |  bool  | false   | Sets the text's fontSize to 24px.            |
| h5     |  bool  | false   | Sets the text's fontSize to 18px.            |
| p      |  bool  | false   | Sets the text's fontSize to 16px.            |
| size   | number | 0       | Sets the fontSize of the text.               |
| color  | string | null    | Sets the color of the text.                  |
| muted  |  bool  | false   | Changes the text color to theme.COLORS.MUTED |
| bold   |  bool  | false   | Sets the fontWeight to 'bold'.               |
| italic |  bool  | false   | Sets the fontStyle to 'italic'.              |