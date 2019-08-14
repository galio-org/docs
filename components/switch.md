# Switch

This component was built on top of React Native's Switch component and so it inherits all the props the native component has.

<p align="center">
  <img src="https://i.imgur.com/0HX86f2.png" />
</p>

**Usage**

Simple example:
```jsx
<Switch
  value={this.state["switch-1"]}
  onValueChange={() => this.toggleSwitch("switch-1")}
/>
```

**Props**

|         Prop        |                                      Type                                      |                               Default                              | Description |
|:-------------------:|:------------------------------------------------------------------------------:|:------------------------------------------------------------------:|:-----------:|
|        color        | oneOfType(['primary', 'theme', 'error', 'warning', 'success', 'info']), string |                      GalioTheme.COLORS.PRIMARY                     |             |
|       disabled      |                                      bool                                      |                                false                               |             |
|     initialValue    |                                      bool                                      |                                false                               |             |
|      trackColor     |                                     object                                     | { false: GalioTheme.COLORS.GREY, true: GalioTheme.COLORS.PRIMARY } |             |
| ios_backgroundColor |                                     string                                     |                       GalioTheme.COLORS.GREY                       |             |
|    onChange    |                                    function                                    |                              () => {}                              |             |
| ...Switch.propTypes |                                                                                |                                                                    |             |
