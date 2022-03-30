<template>

  <div class="p-5 mb-4 bg-light rounded-3 jumbo">
      <div class="container-fluid py-5">
          <form class=" mysearchBar row row-cols-lg-auto g-3 align-items-center ">
            <div class="col-4"></div>  
             <div class="col-4"></div>  
            <div class="col-4 py-1">
                <div class="input-group">
                    <input type="text" class="form-control rounded-pill"  placeholder="Search...">
                </div>
            </div>
          </form>
      </div>
    </div>  
</template>

<script>
export default {

}
</script>

<style scoped>

.jumbo{
    background-image: url('../static/imgs/banner.png');
   
}

.mysearchBar{
    margin-top: -60px;
}



</style>