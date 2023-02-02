<script setup lang="ts">
import 'element-plus/es/components/popover/style/css'
import { ElConfigProvider, ElPopover } from 'element-plus'
import { defineComponent } from 'vue'

defineComponent({
  components: {
    ElConfigProvider,
    ElPopover
  },
  setup() {
    return {}
  },
})
</script>

<template>
  <div class="greetings">
    <el-popover>
      <template #reference>
        <span>123123123</span>
      </template>
      <div>6789678678</div>
    </el-popover>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
