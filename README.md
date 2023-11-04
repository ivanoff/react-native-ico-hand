# Hand Icons for React Native

### react-native-ico-hand

244 Vector Icons for React Native

<img src="./static/clapping-clap.png" alt="clapping-clap" width="150" height="150"> <img src="./static/computer-mouse-clicker.png" alt="computer-mouse-clicker" width="150" height="150"> <img src="./static/computer-mouse-mouse.png" alt="computer-mouse-mouse" width="150" height="150">

## List of icons

- [List of Hand Icons](http://ico.simpleness.org/pack/hand)

## Usage

```
import Icon from 'react-native-ico-hand';


// Inside some view component
render() {
    return (
        <>
          <Icon name="clapping-clap" />
          <Icon name="computer-mouse-clicker" height="40" width="40" />
          <Icon name="computer-mouse-mouse" color="red" />
          <Icon name="computer-mouse-mouse" colors={{ "#000000": "#FFFFFF" }} />
          <Icon name="computer-mouse-clicker" badge="10" />
          <Icon name="computer-mouse-clicker" badge={{value: 'A', fontSize: 25, radius: 22, position:'top_left', color:'orange', backgroundColor:'blue'}}/>
          <Icon name="clapping-clap" background="circle" />
          <Icon name="clapping-clap" background={{ type: "button", color: 'green' }} />
        </>
    );
}

```

## Installation

#### yarn

```bash
yarn add react-native-ico-hand react-native-svg
```

#### npm

```bash
npm install --save react-native-ico-hand react-native-svg
```

### Link react-native-svg

```bash
react-native link react-native-svg
```

### pod install ( for iOS )

```
cd ios && pod install && cd ..
```

## API

### <Icon name [color width height background badge ...rest] />

Returns a SvgXml icon by name and group.

 name | optional | default value | description | examples
------|----------|---------------|-------------|---------
name | no |  | name of icon | "clapping-clap"
color | yes | | line color, css style | "#00ff00", "#0f0", "green"
colors | yes | | replace colors | {"#FFFFFF": "#000000"} // white to black
width | yes | 20 | width of the icon | 40
height | yes | 20 | height of the icon | 40
background | yes | | background type | "circle"
background | yes | | background object | {type: "circle", color: 'yellow'}
badge | yes | | badge string | "10"
badge | yes | | badge object | {value: 'A', fontSize: 25, radius: 22, position:'top_left', color:'orange', backgroundColor:'blue'}
...rest | yes | | other props | style={{backgroundColor: "#00f"}}

## Icons Made by

[Dave Gandy](https://www.flaticon.com/authors/dave-gandy)

## Created by

Dimitry Ivanov <2@ivanoff.org.ua> # curl -A cv ivanoff.org.ua
