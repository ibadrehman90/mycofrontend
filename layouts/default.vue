<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-2 p-0">
        <Sidebar/>
      </div>
      <div class="col-10 p-0">
        <Header/>
        <div class="section">
          <div class="row">
            <div class="col-1"></div>
            <div class="col-10">
               <nuxt/>
            </div>
            <div class="col-1"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import SideBar from '../components/sidebar.vue'
import Header from '../components/header.vue'
export default {
  components: {
    SideBar,
    Header
  }
};
</script>


<style>

.section{
  margin-top:30px;
}


</style>