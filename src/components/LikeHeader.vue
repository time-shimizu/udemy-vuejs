<template>
  <div>
    <slot>デフォルトのタイトル</slot>
  </div>
</template>

<script>
export default {
  props: ["headerText"]
};
</script>