<template>
    <NavBarComponent></NavBarComponent>
    <div class="container">
        <div class="row">
            <ImageHeaderComponent></ImageHeaderComponent>
        </div>

        <div class="items-navbar"></div>
    </div>
</template>

<script>
    import NavBarComponent from "@/shared/modules/navbar/navbar.component.vue";
    import ImageHeaderComponent from "@/modules/image-header/image-header.vue";

    export default {
      name: 'AppComponent',
      components: {
          ImageHeaderComponent,
          NavBarComponent,
      },
    }
</script>

<style scoped>
    body {
        margin: 0;
        padding: 0;
    }
</style>
