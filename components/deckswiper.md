# Deck Swiper
Swipe left, swipe right or don't swipe at all, this component is built to accept any type of component and make it swipeable. Galio's community plans on creating more props for easier access and manipulation of the swipe animation.

<p align="center">
  <img src="https://raw.githubusercontent.com/galio-org/docs/master/assets/deck-swiper.gif" alt="Deck Swiper example react native" />
</p>

### Usage
Imports:
```js
import { DeckSwiper, Block } from 'galio-framework';
```

Simple example:
```jsx
<Block>
  <DeckSwiper components={elements} />
</Block>
```
The elements array looks like following:
```jsx
const elements = [
  <View style={{ backgroundColor: '#B23AFC', height: 250, width: 250 }}>
    <Text>You wanna see a cool component?</Text>
    <Text>Galio has this cool Deck Swiper</Text>
  </View>,
  <View style={{ backgroundColor: '#FE2472', height: 250, width: 250 }}>
    <Text>What did you expect?</Text>
    <Text>This React Native component works perfectly</Text>
  </View>,
  <View style={{ backgroundColor: '#FF9C09', height: 250, width: 250 }}>
    <Text>Maybe you want to build the next Tinder</Text>
  </View>,
  <View style={{ backgroundColor: '#45DF31', height: 250, width: 250 }}>
    <Text>or maybe you just want a nice deck swiper component</Text>
    <Text>Galio has everything sorted out for you</Text>
  </View>
];
```

### Props

|         Prop        |   Type   | Default |                              Description                              |
|:-------------------:|:--------:|:-------:|:---------------------------------------------------------------------:|
|        style        |  object  |         | Styling the Block which encapsulates the components used for swiping. |
|      components     |   array  |   null  |           An array of components used for building the deck.          |
|     onSwipeRight    | function |  ()=>{} |              Function called when the user swipes right.              |
|     onSwipeLeft     | function |  ()=>{} |               Function called when the user swipes left.              |
| focusedElementStyle |  object  |         |               Styling for the first element of the deck.              |
|   nextElementStyle  |  object  |         |   Styling for the elements underneath the first element of the deck.  |