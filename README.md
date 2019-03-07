# react-native-animation-effects

react native chonse select tab horizontal

## Install
	npm install --save react-native-animation-effects
	yarn add react-native-animation-effects

## Usage
#### Example
```javascript
import React, { Component } from 'react';
import { StyleSheet } from 'react-native';
import {
    Blink,
    Scale,
    Bounce,
    Rotate,
    Circle,
    SlideLeft,
    SlideInTop,
    SlideInBottom,
    ScaleSlide
} from 'react-native-animation-effects';

export default class ExampleComponent extends Component {
    render() {
        return (
            <View style={styles.container}>
                <Blink>
                    <Text>Animation blink example</Text>
                </Blink>
                <Bounce>
                    {/* <ExamComponent /> */}
                </Bounce>
            </View>
        );
    }
}

const styles = StyleSheet.create({
    container: {
        flex: 1
    }
});
```
