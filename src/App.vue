<script >
// importazione

import appHeader from './components/appHeader.vue';

export default {
  data() {
    return { count: 0 }
  },
  // dichiarazione
  components: {
    appHeader
  }
}

</script>

<template>
    <div>
        <!--utilizzo-->
        <appHeader />
        <body>
            <div>
                ciao
            </div>
        </body>
 



    </div>
  
</template>

<style scoped>

</style>
