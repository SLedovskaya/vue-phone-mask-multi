# Vue-phone-mask-component

Vue.js multi phone mask component. 
Just start typing the number and the phone mask will apply automatically.

![Preview](https://s2.gifyu.com/images/readme2d75a66a4103c3d6.gif)

## Install

```
npm i vue-multi-mask-component-test

```

## Usage

```javascript
// import the component
import PhoneMask from 'vue-multi-mask-component-test'

// register it in your app
new Vue({
  el: '#app',
  components: {PhoneMask}
})

```

## Properties

| Property    | Required | Type                    | Default | Description                                |
|-------------|----------|-------------------------|---------|--------------------------------------------|
| lang        | false    | String                  |   RU    | Set language RU/EN.                        |
| showRegion  | false    | Boolean                 |   true  | Show region name                           |

Example:
```javascript
// set component language to english
<PhoneMask lang="EN"></PhoneMask>
```

## Dependencies

[Inputmask](https://github.com/RobinHerbots/Inputmask)

## Based on

Based on jQuery [inputmask-multi](https://github.com/andr-04/inputmask-multi) plugin

## License

This project is licensed under [MIT License](http://en.wikipedia.org/wiki/MIT_License)