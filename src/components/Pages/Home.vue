<template>
  <AppLayout>
    <HomeBanner/>
  </AppLayout>
</template>

<script>
import AppLayout from '../Layouts/AppLayout.vue';
import HomeBanner from '../Layouts/Partials/HomeBanner.vue';

export default {
name:"home",
components:{
    AppLayout,
    HomeBanner,
}
}
</script>

<style>

</style>