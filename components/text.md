# Text
It's never been easier to write and style text. We're using a helper function to normalize the next so that it could look good on any kind of device.

**Usage**

Simple example:

```
<Text p>Galio is awesome</Text>
```

**Props**

|  Prop  |  Type  | Default |                  Description                 |
|:------:|:------:|:-------:|:--------------------------------------------:|
| h1     |  bool  | false   | Sets the text's fontSize to 44px.            |
| h2     |  bool  | false   | Sets the text's fontSize to 38px.            |
| h3     |  bool  | false   | Sets the text's fontSize to 30px.            |
| h4     |  bool  | false   | Sets the text's fontSize to 24px.            |
| h5     |  bool  | false   | Sets the text's fontSize to 18px.            |
| p      |  bool  | false   | Sets the text's fontSize to 16px.            |
| size   | number | 0       | Sets the fontSize of the text.               |
| color  | string | null    | Sets the color of the text.                  |
| muted  |  bool  | false   | Changes the text color to theme.COLORS.MUTED |
| bold   |  bool  | false   | Sets the fontWeight to 'bold'.               |
| italic |  bool  | false   | Sets the fontStyle to 'italic'.              |