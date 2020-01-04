# react-native-splited-progress-bar

![CircleProgressBar](https://user-images.githubusercontent.com/36489841/71761365-421cf480-2edf-11ea-86d0-c1e897e7da67.jpg)

## Installation

`$ npm install react-native-splited-progress-bar --save`

## Usage

```js

import {CircleProgressBar} from 'react-native-splited-progress-bar';

<CircleProgressBar
    percentage={25}
/>
```

### `CircleProgressBar`

| Prop                   | Description                                                     | Default                |
| ---------------------- | --------------------------------------------------------------- | ---------------------- |
| **`percentage`**       | number of percentage                                            | `0`                    |
| **`size`**             | size of progress bar to show in app                             | `100`                  |
| **`splited`**          | splited progressbar or not                                      | `true`                 |
| **`compeletedColor`**  | Color of the circle.                                            | `#39bc65`              |
| **`inCompeletedColor`**| Color of the inCompeleted area.                                 | `#C1C1C1`              |
| **`innerComponent`**   | The component to show in progresbar                             | `Component`            |
| **`isRtl`**            | for Rtl application                                             | `false`                |
