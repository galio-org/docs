# Cómo instalar Galio

Añádelo como una dependencia con npm/yarn:

`npm install galio-framework`
ó
`yarn install galio-framework`

A continuación importa los componentes que quieras usar en tu aplicación:

`import { Text } from 'galio-framework'`

Parece sencillo verdad? Usa los componentes de Galio tal y como lo harías normalmente con otros componentes.

```js
render() {
  return (
    <View>
      <Text p muted>Hola, Soy un componente de Galio</Text>
    </View>
  );
}
```
