<template>
  <header class="phone-viewport">
    <md-toolbar>
      <md-button class="md-icon button" v-on:click.native="toggleLeftSidenav">
        <md-icon>Menu</md-icon>
      </md-button>

      <h1 class="md-title">{{ title }}</h1>
    
    </md-toolbar>

    <md-sidenav class="md-left" ref="LeftSidenav">
      <md-toolbar class="md-medium">
        <div class="md-toolbar-container">
          <h2 class="md-title">Sidenav content</h2>
        </div>
      </md-toolbar>

      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse eu leo metus. Nullam laoreet scelerisque lacus, vitae imperdiet libero. 
        Etiam porttitor mattis libero a facilisis. 
        Nunc faucibus ligula ante, ac dictum eros ultricies ut. 
        Nam augue dolor, ultrices vitae venenatis eget, ornare in quam. 
        Ut tempor dui efficitur nisi dignissim commodo. 
        Cras non nisl mattis, ultricies tellus in, consequat erat. 
        Proin cursus aliquam velit, ut feugiat arcu suscipit eget. 
        Sed iaculis accumsan urna, luctus facilisis justo rutrum efficitur. Mauris quis leo finibus, facilisis urna quis, ornare nulla. 
        Sed vestibulum elit orci, non sagittis lacus tristique et. 
        Fusce a blandit massa. Mauris enim nisl, vestibulum vitae 
        molestie eget, blandit non ante. Pellentesque eu justo tincidunt, 
        ultricies erat nec, luctus libero.
      </p>
    </md-sidenav>
    
  </header>
</template>

<script>
import CcHello from './components/HelloWorld'

export default {
  name: 'ShrimpFarmComponent',

  data (){
    return {
      title: 'Shrimp Farm'
    }
  },

  components: {
    CcHello
  }
}
</script>

<style>
#app {
  margin-top: 60px;
  margin-left: 30px;
  margin-right: 30px; 
}

</style>
