# Slider

We all need a slider in our application. This is a JavaScript component built with the PanResponder and Animated APIs.

<p align="center">
 <img src="https://i.imgur.com/sp42kcd.png" />
</p>

### Usage
Imports:
```js
import { Slider, Block } from 'galio-framework';
```

Simple example:
```jsx
<Block flex>
  <Slider
    maximumValue={30}
    value={10}
    onSlidingcomplete={() => this.registerTheValue()}
  />
</Block>
```

### Props

|        Prop       |  Type  |  Default |                                            Description                                           |
|:-----------------:|:------:|:--------:|:------------------------------------------------------------------------------------------------:|
|       activeColor       | string |     GalioTheme.COLORS.PRIMARY    |                 This sets the active color of your slider.                |
|       value       | number |     0    |                 The initial value at which the thumb of the slider is positioned                 |
|      disabled     |  bool  |   false  |                         This prop makes the slider unusable to the user.                         |
|    minimumValue   | number |     0    |                              Sets the minimum value for the Slider.                              |
|    maximumValue   | number |    100   |                              Sets the maximum value for the Slider.                              |
|     trackStyle    |   any  |    {}    |                    By passing an object you can style the track of the Slider.                   |
|     thumbStyle    |   any  |    {}    |                    By passing an object you can style the thumb of the Slider.                   |
|        step       | number |     0    |                      This is a stepper. It sets fixed values for the thumb.                      |
| onSlidingComplete |  func  | () => {} | By passing an arrow function you can decide what is going to happen when the Sliding is complete |
|   onSlidingStart  |  func  | () => {} |    By passing an arrow function you can decide what is going to happen when the Sliding starts   |
|   onValueChange   |  func  | () => {} |  By passing an arrow function you can decide what is going to happen when the Sliding is moving. |
