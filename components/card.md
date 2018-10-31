# Card
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

