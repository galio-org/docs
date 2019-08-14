# Radio

Check out how awesome these radio buttons look! Who wouldn't want to use them?

<p align="center">
  <img src="https://i.imgur.com/3J49DW9.png">
</p>

**Usage**

Simple example:
```jsx
<Radio 
  label="This looks like a nice option"
  color={galioTheme.COLORS.PRIMARY}
  initialValue={true}
  disabled
/>
```

**Props**

|       Prop      |                                  Type                                 |  Default  | Description |
|:---------------:|:---------------------------------------------------------------------:|:---------:|:-----------:|
|      color      |                                 string                                | 'primary' |             |
|  containerStyle |                                  any                                  |           |             |
| radioOuterStyle |                                  any                                  |           |             |
| radioInnerStyle |                                  any                                  |           |             |
|     disabled    |                                  bool                                 |   false   |             |
|  flexDirection  | oneOfType(['row', 'row-reverse', 'column', 'column-reverse']), string |   'row'   |             |
|   initialValue  |                                  bool                                 |   false   |             |
|      label      |                                 string                                |    null   |             |
|    labelStyle   |                                  any                                  |    null   |             |
|     onChange    |                                function                               |  () => {} |             |