# Deck Swiper

Swipe left, swipe right or don't swipe at all, this component is built to accept any type of component and make it swipeable.

**image**

**Usage**

Simple example:
```jsx
  <DeckSwiper components={elements} />
```
The elements array looks like following:
```jsx
const elements = [
  <View style={{ backgroundColor: 'red', height: 150, width: 150 }}>
    <Text>You wanna see some weird shit?</Text>
    <Text>Expect the worst</Text>
  </View>,
  <View style={{ backgroundColor: 'blue', height: 150, width: 150 }}>
    <Text>What did you expect?</Text>
    <Text>Nothing, you big ass weird shit</Text>
  </View>,
  <View style={{ backgroundColor: 'green', height: 150, width: 150 }}>
    <Text>Broski... Calmeaza-te... You ain't shit</Text>
    <Text>Trust me about that</Text>
  </View>,
  <View style={{ backgroundColor: 'yellow', height: 150, width: 150 }}>
    <Text>Y'all expecting to win but only one of us can really do it</Text>
    <Text>Trust me, it's gonna be me.</Text>
  </View>
];
```

**Props**

|         Prop        |   Type   | Default |                              Description                              |
|:-------------------:|:--------:|:-------:|:---------------------------------------------------------------------:|
|        style        |  object  |         | Styling the Block which encapsulates the components used for swiping. |
|      components     |   array  |   null  |           An array of components used for building the deck.          |
|     onSwipeRight    | function |  ()=>{} |              Function called when the user swipes right.              |
|     onSwipeLeft     | function |  ()=>{} |               Function called when the user swipes left.              |
| focusedElementStyle |  object  |         |               Styling for the first element of the deck.              |
|   nextElementStyle  |  object  |         |   Styling for the elements underneath the first element of the deck.  |