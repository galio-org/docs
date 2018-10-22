# Galio 

<img src="https://raw.githubusercontent.com/galio-org/galio/master/assets/galio_thumbnail.jpg">

Galio is a 100% free and open source project, licensed under MIT. It will always remain free to use, powered by a massive world-wide community. Carefully crafted. Ready-made components, typography, and a gorgeous base theme that adaps to each project. You'll be building in style. Built with real app examples, component demos, guides, and how-to's to get you up and running with mobile apps faster than ever before.

## How to install

Just add it as an npm/yarn dependency:

```npm install galio-framework```
or
```yarn install galio-framework```

And just import the component you want in your application:

```import { Text } from 'galio-framework'```

This seems really easy right? Just use your component like you would normally do with any other component.

```
render() {
  return (
    <View>
      <Text p muted>Hi, I'm a Galio component</Text>
    </View>
  );
}```

# Components

We always continue to improve and create more components. Watch us closely and build with us.


## Block
The main component used to create almost everything in your app.

**Usage**

Simple example:
```
<Block>{children}</Block>
```

## Button
A nice button which suits even the most picky developers.

**Usage**

Simple example:
```
<Button>Press here!</Button>
```

## Card
Did anybody say you need a card? Good think we have one.

**Usage**

Simple example:
```
<Card 
  neutral
  fullBackgroundImage
  image="https://images.unsplash.com/photo-1536567893079-f54abdc73dc2?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=e6a56a131b11a6366446c42381192329&auto=format&fit=crop&w=1350&q=80"
  authorImageSrc="http://i.pravatar.cc/100"
  authorTitle="Offset"
  authorSubTitle="420 minutes ago"
/>
```

## Icon
That little Facebook icon never looked better.

**Usage**

Simple example:
```
<Icon name="pin-3" family="Galio" color={rgb(100,120,40)} size={10} />
```

## Input
A simple customizable input you'll love using.

**Usage**

Simple example:
```
<Input placeholder="Email" />
```

## NavBar
How are your clients going to know which screen they're visiting if you don't have a navbar component?

**Usage**

Simple example:
```
<Navbar title="Screen Title" />
```

## Text
It's never been easier to write and style text.

**Usage**

Simple example:
```
<Text p>Galio is awesome</Text>
```
