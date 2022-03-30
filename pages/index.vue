<template>
    <dashboard/>
  <!-- <NuxtLink to="/"><dashboard/></NuxtLink> -->
</template>

<script lang="ts">

import dashboard from '../pages/dashboard.vue'
export default{

  components:{
    dashboard
  },
 
  head() {
    return {
      title: "Virtual Office Services | MYCO Works",
      meta: [
        {
          hid: "MYCO Works is a trusted B2B service provider",
          name: "MYCO Works is a trusted B2B service provider",
          content: "MYCO Works is a trusted B2B service provider specialising in Virtual Business Address, Company Formations, Meeting Room Hire & Business Call Answering Services."
        }
      ]
    };
  }
}
</script>
