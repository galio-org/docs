# Card
Did anybody say you need a card? Good think we have one.

<p align="center">
 <img src="https://i.imgur.com/P9eFZap.png" />
</p>

### Usage
Imports:
```js
import { Card } from 'galio-framework';
```

Simple example:
```jsx
<Card
  flex
  borderless
  style={styles.card}
  title="Christopher Moon"
  caption="139 minutes ago"
  location="Los Angeles, CA"
  avatar="http://i.pravatar.cc/100?id=skater"
  imageStyle={styles.cardImageRadius}
  imageBlockStyle={{ padding: theme.SIZES.BASE / 2 }}
  image="https://images.unsplash.com/photo-1497802176320-541c8e8de98d?&w=1600&h=900&fit=crop&crop=entropy&q=300"
/>
```

### Props

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

_The Card components accepts every piece of prop the `<Block />` component accepts. Those will be applied on the `<Block />` which wraps the whole `<Card />` component._
