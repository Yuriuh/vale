<template>
<div>
  <h1>Switch 组件示例</h1>
  <Demo :component="Switch1Demo" />
  <Demo :component="Switch2Demo" />
</div>
</template>

<script lang="ts">
import Switch from '../lib/Switch.vue'
import Button from '../lib/Button.vue'
import Switch1Demo from './Switch1.demo.vue'
import Switch2Demo from './Switch2.demo.vue'
import Demo from './Demo.vue'
import {
  ref
} from 'vue'
export default {
  components: {
    Button,
    Demo
  },
  setup() {
    return {
      Switch1Demo,
      Switch2Demo,
    }
  }
}
</script>