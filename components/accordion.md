# Accordion
Having different information with a drop-down so your users can realy whatever they're really interested in.

![Accordion](../assets/accordion.gif)

### Usage
Imports:
```js
import { Accordion, Block } from 'galio-framework';
```

Simple example:
```jsx
<Block style={{ height: 200 }}>
  <Accordion dataArray={data} />
</Block>
```

The data array looks like:
```js
const data = [
  { title: "First Chapter", content: "Lorem ipsum dolor sit amet", 
    icon: {
      name: 'keyboard-arrow-up',
      family: 'material',
      size: 16,
    } 
 },
  { title: "2nd Chapter", content: "Lorem ipsum dolor sit amet" },
  { title: "3rd Chapter", content: "Lorem ipsum dolor sit amet" }
];
```

### Props

|       Prop       |    Type   |  Default |                                                    Description                                                   |
|:----------------:|:---------:|:--------:|:----------------------------------------------------------------------------------------------------------------:|
|       style      |   object  |          |             Styling the Block which encapsulates the whole FlatList used for rendering the elements.             |
|     dataArray    |   array   |   null   |        Array of objects with the following keys: title, content, icon: { name, family, size, color, style}       |
|      opened      |   number  |          | Index number representing which of the elements of your array should be opened when the component first renders. |
|     listStyle    |   object  |          |                                               FlatList style prop.                                               |
|       icon       | component |          |                                    Icon for the un-expanded piece of content.                                    |
|   expandedIcon   | component |          |                                      Icon used when the content is expanded.                                     |
|    headerStyle   |   object  |          |                                    Object styling the header of the Accordion.                                   |
|   contentStyle   |   object  |          |                               Object styling the content section of the Accordion.                               |
| onAccordionClose |  function | () => {} |                        Function called when the user closes one of the Accordion's items.                        |
|  onAccordionOpen |  function | () => {} |                        Function called when the user expands one of the Accordion's items.                       |