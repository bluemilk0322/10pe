<template>
  <div class="column is-2">
    <div class="menu is-dark">
      <menus label="The University Topic">
        <menu-item icon="twitter">
          <span>10PE</span>
          <menus slot="sub">
            <menu-item :to="{ path: '/components/menu/submenu1', query: { userId: 321 }}" icon="qq" :is-active="true">子子目录1</menu-item>
            <menu-item icon="google">
              <span>子子目录2</span>
              <menus slot="sub">
                <menu-item icon="home">第三级1</menu-item>
                <menu-item icon="home">第三级2</menu-item>
                <menu-item icon="home">
                  <span>第三级3</span>
                  <menus slot="sub" type="float">
                    <menu-item icon="home">第四级1</menu-item>
                  </menus>
                </menu-item>
              </menus>
            </menu-item>
          </menus>
        </menu-item>
        <menu-item icon="wechat" to="/components/menu/submenu2">子目录2</menu-item>
        <div class="divider"></div>
        <menu-item icon="facebook" to="/components/menu/submenu3"><span>子目录3</span></menu-item>
      </menus>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Menu'
  }
</script>

<style scoped>
/* .menus label{
    font-size: 50px;
} */
.column is-2{
    height: 100%;
}
</style>
