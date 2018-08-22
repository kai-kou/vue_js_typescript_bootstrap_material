<template>
  <div class="about">
    <h1>This is an about page</h1>
    <btn color="primary">Primary</btn>
  </div>
</template>

<script lang="ts">
  import {
    Component,
    Vue
  } from 'vue-property-decorator';
  
  import {
    Container,
    Navbar,
    NavbarItem,
    NavbarNav,
    NavbarCollapse,
    Btn,
    Fa,
    ListGroup,
    ListGroupItem,
    CardBody,
    Footer,
    waves,
  } from 'mdbvue';
  @Component({
    components: {
      Container,
      Navbar,
      NavbarItem,
      NavbarNav,
      NavbarCollapse,
      Btn,
      Fa,
      ListGroup,
      ListGroupItem,
      CardBody,
      Footer,
      waves,
    },
  })
  export default class About extends Vue {}
</script>