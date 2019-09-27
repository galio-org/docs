# Toast Notification
Toast notifications appear when the user finishes an action and you want to show him a piece of information without redirecting him to another screen.

![Toast Notification](../assets/Toast-notification.gif)

### Usage
Imports:
```js
import { Toast, Block } from 'galio-framework';
```

Simple example:
```jsx
<Button shadowless onPress={() => setShow(!isShow)} style={{ marginBottom: 80 }}>click here for toast notifications</Button>
<Toast isShow={isShow} positionIndicator="top">This is a top positioned toast</Toast>
<Toast isShow={isShow} positionIndicator="center" color="success">This is a center positioned toast</Toast>
<Toast isShow={isShow} positionIndicator="bottom" color="warning">This is a bottom positioned toast</Toast>
```

Hook used for `isShow`:
```js
const [isShow, setShow] = useState(false);
```

### Props
|        Prop       |     Type    |  Default  |                                              Description                                             |
|:-----------------:|:-----------:|:---------:|:----------------------------------------------------------------------------------------------------:|
|       style       |    object   |    null   |                                  Styling the Block which encapsulate                                 |
|      children     | node/string |           | The content of your toast notification. You can even just write a text or create your own component. |
|       isShow      |     bool    |           |                             Toggle between the toast being shown or not.                             |
| positionIndicator |    string   |   'top'   |                                   one of: 'top', 'center', 'bottom'                                  |
|   positionOffset  |    number   |    120    |                                                                                                      |
|   fadeInDuration  |    number   |    300    |                              The number of ms for the fade in animation.                             |
|  fadeOutDuration  |    number   |    300    |                             The number of ms for the fade out animation.                             |
|       color       |    string   | 'primary' |                   one of: 'primary', 'theme', 'info', 'error', 'warning', 'success'                  |
|       round       |     bool    |   false   |                             Maybe you want a rounded toast notification?                             |
|     textStyle     |    object   |    null   |                         Style object for the children prop used as a string.                         |

