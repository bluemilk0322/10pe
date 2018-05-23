<template>
    <div class="columns is-gapless">
        <Menu></Menu>
        <Index_Content></Index_Content>
    </div>
</template>

<script>
import Menu from '@/components/Menu';
import Index_Content from '@/components/Content/Index_content';
  export default {
    name: 'Index',
    components: {
      Menu,
      Index_Content
  }
}
</script>

<style>
.columns{
    height: 100%;
}
</style>
