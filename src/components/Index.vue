<template>
    <div class="columns" style="background-color: #f0f0f0;">
        <Menu></Menu>
    </div>
</template>

<script>
import Menu from '@/components/Menu';
  export default {
    name: 'Index',
    components: {
      Menu
  }
}
</script>

<style scoped>
.columns{
    height: 100%;
}
</style>
