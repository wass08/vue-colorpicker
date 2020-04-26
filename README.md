# vue-one-simplecolorpicker
A simple colorpicker for Vue JS!

![N|Solid](//s3-eu-west-1.amazonaws.com/dev.appdrag.com/appalga/assets/colorpicker.jpg)

### Installation



```sh
$ npm install --save vue-one-simple-colorpicker
```

**main.js**

```
import colorpicker from  'vue-one-simple-colorpicker';
import Vue from "vue";

Vue.use(colorpicker);
```

**Usage in Component (Vue)**
v-model can be hexadecimal, rgb/rgba or css text color.
```
<template>
  <color-picker v-model="color"/>
</template>

<script>

export default {
  data(){
    return {
      color: 'red'
    }
  }
}
</script>
```

License
----

MIT

