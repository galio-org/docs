# Block
This component is the main component block used to build everything in Galio and any type of layout. There are so many props available for easier access to different styling options that you'll rarely write another `style` prop. 

### Usage
Imports:
```js
import { Block } from 'galio-framework';
```

Simple example:
```jsx
<Block>{children}</Block>
```

### Props

|     Prop    |     Type     | Default |                     Description                    |
|:-----------:|:------------:|:-------:|:--------------------------------------------------:|
| bottom      |     bool     |  false  |    alignItems: 'flex-end' alignSelf: 'flex-end'    |
| card        |     bool     |  false  | changes the View's border-radus, -width and -color |
| center      |     bool     |  false  |      alignItems: 'center' alignSelf: 'center'      |
| flex        | bool, number |  false  |             flex: 1 **or** `<yourNumber>`            |
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
