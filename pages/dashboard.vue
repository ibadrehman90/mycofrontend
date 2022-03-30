<template>
   
    <div>
         <Jumbotron/>
         <div class="row">
            <div class="col-1"></div>
            <div class=" mycard col-10 bg-light shadow">
                <div class="row">
                    <div class="col-8">
                        <div class="row">
                            <div class="col-2">
                                <img src="https://github.com/mdo.png"  class="img-fluid thumb" alt="...">
                            </div>
                            <div class="col-8 p-0 descp">
                                   <span class="designations title">Joe Bloggs</span>
                                   <span class="designations lbl">joebloggs@gmail.com</span>
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <button class="btn btn-primary addbtn">
                            <span class="btn-label">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-plus" viewBox="0 0 16 16">
                                    <path d="M8 4a.5.5 0 0 1 .5.5v3h3a.5.5 0 0 1 0 1h-3v3a.5.5 0 0 1-1 0v-3h-3a.5.5 0 0 1 0-1h3v-3A.5.5 0 0 1 8 4z"/>
                                </svg>
                            </span>
                            Add Company
                    </button>
                    </div>
                </div>
            </div>
            <div class="col-1"></div>
         </div>
         <div class="dashcards">
              <Dashcards/>
         </div>
         <div class="active">
             <p>Your Active Companies</p>
             <div class="card shadow comCard">
                <div class="card-body">
                    <div class="row">
                        <div class="col-9">
                            <p class="lbl">MY REALLY LONG COMPANY NAME LTD</p>
                        </div>
                        <div class="col-3">
                              <button class="btn btn-primary addcompbtn">
                                  View Company
                                <span class="btn-label">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-caret-right-fill" viewBox="0 0 16 16">
                                        <path d="m12.14 8.753-5.482 4.796c-.646.566-1.658.106-1.658-.753V3.204a1 1 0 0 1 1.659-.753l5.48 4.796a1 1 0 0 1 0 1.506z"/>
                                    </svg>
                                </span>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
         </div>
    </div>
  
</template>

<script>
import Jumbotron from '../components/jumbotron.vue'
import Dashcards from '../components/dashcards.vue'
export default {
    components: {
    Jumbotron,
    Dashcards
  }

}
</script>

<style>

.mycard{
    margin-top: -80px;
    z-index: 9999;
    border-radius:8px;
}

.addbtn{
    float:right;
    position: relative;
    background-color: #39A6E3;
    border-color: #39A6E3;
    font-size: 0.8rem;
    top:22px;
}

.addbtn:hover{
    background-color: #273550;
    border-color: #273550;
    color:white;
}

.thumb{
    width:60px;
    height: 60px;
    border-radius:5px;
    margin-top: 12px;
    
}

a{
    text-decoration: none !important;
    color: black;
}
.descp{
     margin-top: 18px;
}
.designations {
  position: relative;
  display: block;
 
}

.title{
    font-size: 1rem;
    display: block;
}

.lbl{
    font-size: 0.8rem;
    color:gray;
    display: block;
}

.dashcards{
    margin-top: 30px;
}

.addcompbtn{
     float:right;
    position: relative;
    background-color: #39A6E3;
    border-color: #39A6E3;
    font-size: 0.8rem;
    
}

.addcompbtn:hover{
     background-color: #273550;
    border-color: #273550;
    color:white;
}

.comCard{
    border-left: 4px solid lightgreen;
}


</style>