<template>
  <div>
    <orther-file>
  </div>
</template>

<script lang="ts">
import * as _ from 'lodash'
import OrtherFile from './OrtherFile.vue'

export default {
  components: { OrtherFile },
  props: ['foo', 'bar']
}
</script>