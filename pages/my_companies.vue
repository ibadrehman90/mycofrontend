<template>
  <div class="row">
    <div class="col-6">
      <p>Your companies</p>
    </div>
    <div class="col-lg-4 col-md-6">
      <div class="form-outline ">
        <input type="search" id="form1" class="form-control rounded-pill searchBar" placeholder="Search..." aria-label="Search" />
      </div>
    </div>
    <div class="col-lg-2 col-md-6">
        <button class="btn btn-primary addcompbtn">
          Add Company
          <span class="btn-label">
              <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-plus" viewBox="0 0 16 16">
                <path d="M8 4a.5.5 0 0 1 .5.5v3h3a.5.5 0 0 1 0 1h-3v3a.5.5 0 0 1-1 0v-3h-3a.5.5 0 0 1 0-1h3v-3A.5.5 0 0 1 8 4z"/>
              </svg>
          </span>
        </button>
    </div>
    <div class="tabs">
      <ul class="nav nav-pills tabsLinks">
        <li class="nav-item p-1">
          <a class="nav-link active" aria-current="page" href="#">All</a>
        </li>
        <li class="nav-item p-1">
          <a class="nav-link" href="#">Active</a>
        </li>
        <li class="nav-item p-1">
          <a class="nav-link" href="#">Pending</a>
        </li>
        <li class="nav-item p-1">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Suspended</a>
        </li>
      </ul>
    </div>
    <div class="tblabels">
      <div class="row lbls">
        <div class="col-2">
          <span class="label">COMPANY NAME</span>
        </div>
        <div class="col-1"><span class="label">Renew</span></div>
        <div class="col-1"><span class="label">Office</span></div>
        <div class="col-1"><span class="label">Status</span></div>
        <div class="col-1"><span class="label">TAS</span></div>
        <div class="col-1"><span class="label">ROA</span></div>
        <div class="col-1"><span class="label">DSA</span></div>
        <div class="col-1"><span class="label">VBA</span></div>
        <div class="col-1"><span class="label">MESSAGES</span></div>
        <div class="col-1"><span class="label">MAIL</span></div>
        <div class="col-1"><span class="label">Formation</span></div>
      </div>
    </div>


    <div class="cardsList" v-on:click="goDetail('')">
        <div class="row lbls">
        <div class="col-2">
          <span class="label">MY REALLY LONG COMPANY NAME LTD</span>
        </div>
        <div class="col-1"><span class="label">09-11-2021</span></div>
        <div class="col-1"><span class="label">W1W5PE</span></div>
        <div class="col-1"><span class="label"><span class="badge bg-success">ACTIVE</span></span></div>
        <div class="col-1"><span class="label">
          <span class="badge rounded-pill bg-success">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-check2" viewBox="0 0 16 16">
              <path d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0z"/>
            </svg>
          </span></span>
        </div>
        <div class="col-1">
          <span class="label">
             <span class="badge rounded-pill bg-success">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-check2" viewBox="0 0 16 16">
              <path d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0z"/>
            </svg>
          </span>
          </span></div>
        <div class="col-1">
          <span class="label">
             <span class="badge rounded-pill bg-success">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-check2" viewBox="0 0 16 16">
              <path d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0z"/>
            </svg>
          </span>
          </span></div>
        <div class="col-1">
          <span class="label">
             <span class="badge rounded-pill bg-success">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-check2" viewBox="0 0 16 16">
              <path d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0z"/>
            </svg>
          </span>
          </span></div>
        <div class="col-1">
            <span class="chatbadge">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="#0000" class="bi bi-chat" viewBox="0 0 16 16">
              <path d="M8 15c4.418 0 8-3.134 8-7s-3.582-7-8-7-8 3.134-8 7c0 1.76.743 3.37 1.97 4.6-.097 1.016-.417 2.13-.771 2.966-.079.186.074.394.273.362 2.256-.37 3.597-.938 4.18-1.234A9.06 9.06 0 0 0 8 15z"/>
            </svg>
            <span class="start-100 translate-middle badge rounded-pill bg-info">0
              <span class="visually-hidden">unread messages</span>
            </span>
          </span>
          </div>
        <div class="col-1">
           <span class="chatbadge">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-envelope-fill" viewBox="0 0 16 16">
              <path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414.05 3.555ZM0 4.697v7.104l5.803-3.558L0 4.697ZM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586l-1.239-.757Zm3.436-.586L16 11.801V4.697l-5.803 3.546Z"/>
            </svg>
            <span class="start-100 translate-middle badge rounded-pill bg-info">4
              <span class="visually-hidden">unread messages</span>
            </span>
          </span>
        </div>
        <div class="col-1"><span class="label formlabel">Completed</span></div>
      </div>       
    </div>

     <div class="cardsList">
        <div class="row lbls">
        <div class="col-2">
          <span class="label">MY REALLY LONG COMPANY NAME LTD</span>
        </div>
        <div class="col-1"><span class="label">09-11-2021</span></div>
        <div class="col-1"><span class="label">W1W5PE</span></div>
        <div class="col-1"><span class="label"><span class="badge bg-success">ACTIVE</span></span></div>
        <div class="col-1"><span class="label">
          <span class="badge rounded-pill bg-success">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-check2" viewBox="0 0 16 16">
              <path d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0z"/>
            </svg>
          </span></span>
        </div>
        <div class="col-1">
          <span class="label">
             <span class="badge rounded-pill bg-success">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-check2" viewBox="0 0 16 16">
              <path d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0z"/>
            </svg>
          </span>
          </span></div>
        <div class="col-1">
          <span class="label">
             <span class="badge rounded-pill bg-success">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-check2" viewBox="0 0 16 16">
              <path d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0z"/>
            </svg>
          </span>
          </span></div>
        <div class="col-1">
          <span class="label">
             <span class="badge rounded-pill bg-danger">
           <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-x-lg" viewBox="0 0 16 16">
              <path fill-rule="evenodd" d="M13.854 2.146a.5.5 0 0 1 0 .708l-11 11a.5.5 0 0 1-.708-.708l11-11a.5.5 0 0 1 .708 0Z"/>
              <path fill-rule="evenodd" d="M2.146 2.146a.5.5 0 0 0 0 .708l11 11a.5.5 0 0 0 .708-.708l-11-11a.5.5 0 0 0-.708 0Z"/>
            </svg>
          </span>
          </span></div>
        <div class="col-1">
            <span class="chatbadge">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="#0000" class="bi bi-chat" viewBox="0 0 16 16">
              <path d="M8 15c4.418 0 8-3.134 8-7s-3.582-7-8-7-8 3.134-8 7c0 1.76.743 3.37 1.97 4.6-.097 1.016-.417 2.13-.771 2.966-.079.186.074.394.273.362 2.256-.37 3.597-.938 4.18-1.234A9.06 9.06 0 0 0 8 15z"/>
            </svg>
            <span class="start-100 translate-middle badge rounded-pill bg-info">1
              <span class="visually-hidden">unread messages</span>
            </span>
          </span>
          </div>
        <div class="col-1">
           <span class="chatbadge">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-envelope-fill" viewBox="0 0 16 16">
              <path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414.05 3.555ZM0 4.697v7.104l5.803-3.558L0 4.697ZM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586l-1.239-.757Zm3.436-.586L16 11.801V4.697l-5.803 3.546Z"/>
            </svg>
            <span class="start-100 translate-middle badge rounded-pill bg-info">3
              <span class="visually-hidden">unread messages</span>
            </span>
          </span>
        </div>
        <div class="col-1"><span class="label formlabelred">Start formation</span></div>
      </div>       
    </div>


     <div class="cardsListpending">
        <div class="row lbls">
        <div class="col-2">
          <span class="label">MY REALLY LONG COMPANY NAME LTD</span>
        </div>
        <div class="col-1"><span class="label">09-11-2021</span></div>
        <div class="col-1"><span class="label">W1W5PE</span></div>
        <div class="col-1"><span class="label"><span class="badge bg-warning">PENDING</span></span></div>
        <div class="col-1"><span class="label">
          <span class="badge rounded-pill bg-success">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-check2" viewBox="0 0 16 16">
              <path d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0z"/>
            </svg>
          </span></span>
        </div>
        <div class="col-1">
          <span class="label">
             <span class="badge rounded-pill bg-success">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-check2" viewBox="0 0 16 16">
              <path d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0z"/>
            </svg>
          </span>
          </span></div>
        <div class="col-1">
          <span class="label">
             <span class="badge rounded-pill bg-success">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-check2" viewBox="0 0 16 16">
              <path d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0z"/>
            </svg>
          </span>
          </span></div>
        <div class="col-1">
          <span class="label">
             <span class="badge rounded-pill bg-danger">
           <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-x-lg" viewBox="0 0 16 16">
              <path fill-rule="evenodd" d="M13.854 2.146a.5.5 0 0 1 0 .708l-11 11a.5.5 0 0 1-.708-.708l11-11a.5.5 0 0 1 .708 0Z"/>
              <path fill-rule="evenodd" d="M2.146 2.146a.5.5 0 0 0 0 .708l11 11a.5.5 0 0 0 .708-.708l-11-11a.5.5 0 0 0-.708 0Z"/>
            </svg>
          </span>
          </span></div>
        <div class="col-1">
            <span class="chatbadge">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="#0000" class="bi bi-chat" viewBox="0 0 16 16">
              <path d="M8 15c4.418 0 8-3.134 8-7s-3.582-7-8-7-8 3.134-8 7c0 1.76.743 3.37 1.97 4.6-.097 1.016-.417 2.13-.771 2.966-.079.186.074.394.273.362 2.256-.37 3.597-.938 4.18-1.234A9.06 9.06 0 0 0 8 15z"/>
            </svg>
            <span class="start-100 translate-middle badge rounded-pill bg-info">0
              <span class="visually-hidden">unread messages</span>
            </span>
          </span>
          </div>
        <div class="col-1">
           <span class="chatbadge">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-envelope-fill" viewBox="0 0 16 16">
              <path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414.05 3.555ZM0 4.697v7.104l5.803-3.558L0 4.697ZM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586l-1.239-.757Zm3.436-.586L16 11.801V4.697l-5.803 3.546Z"/>
            </svg>
            <span class="start-100 translate-middle badge rounded-pill bg-info">2
              <span class="visually-hidden">unread messages</span>
            </span>
          </span>
        </div>
        <div class="col-1"><span class="label formlabelorange">Edit</span></div>
      </div>       
    </div>


     <div class="cardsListsuspend">
        <div class="row lbls">
        <div class="col-2">
          <span class="label">MY REALLY LONG COMPANY NAME LTD</span>
        </div>
        <div class="col-1"><span class="label">09-11-2021</span></div>
        <div class="col-1"><span class="label">W1W5PE</span></div>
        <div class="col-1"><span class="label"><span class="badge bg-danger">SUSPENDED</span></span></div>
        <div class="col-1"><span class="label">
          <span class="badge rounded-pill bg-success">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-check2" viewBox="0 0 16 16">
              <path d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0z"/>
            </svg>
          </span></span>
        </div>
        <div class="col-1">
          <span class="label">
             <span class="badge rounded-pill bg-success">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-check2" viewBox="0 0 16 16">
              <path d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0z"/>
            </svg>
          </span>
          </span></div>
        <div class="col-1">
          <span class="label">
             <span class="badge rounded-pill bg-danger">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-x-lg" viewBox="0 0 16 16">
              <path fill-rule="evenodd" d="M13.854 2.146a.5.5 0 0 1 0 .708l-11 11a.5.5 0 0 1-.708-.708l11-11a.5.5 0 0 1 .708 0Z"/>
              <path fill-rule="evenodd" d="M2.146 2.146a.5.5 0 0 0 0 .708l11 11a.5.5 0 0 0 .708-.708l-11-11a.5.5 0 0 0-.708 0Z"/>
            </svg>
          </span>
          </span></div>
        <div class="col-1">
          <span class="label">
             <span class="badge rounded-pill bg-danger">
           <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-x-lg" viewBox="0 0 16 16">
              <path fill-rule="evenodd" d="M13.854 2.146a.5.5 0 0 1 0 .708l-11 11a.5.5 0 0 1-.708-.708l11-11a.5.5 0 0 1 .708 0Z"/>
              <path fill-rule="evenodd" d="M2.146 2.146a.5.5 0 0 0 0 .708l11 11a.5.5 0 0 0 .708-.708l-11-11a.5.5 0 0 0-.708 0Z"/>
            </svg>
          </span>
          </span></div>
        <div class="col-1">
          <span class="chatbadge">
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="#808080" class="bi bi-chat-suspend" viewBox="0 0 16 16">
              <path d="M8 15c4.418 0 8-3.134 8-7s-3.582-7-8-7-8 3.134-8 7c0 1.76.743 3.37 1.97 4.6-.097 1.016-.417 2.13-.771 2.966-.079.186.074.394.273.362 2.256-.37 3.597-.938 4.18-1.234A9.06 9.06 0 0 0 8 15z"/>
            </svg>
          </span>
          </div>
        <div class="col-1">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-envelope-suspend" viewBox="0 0 16 16">
            <path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414.05 3.555ZM0 4.697v7.104l5.803-3.558L0 4.697ZM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586l-1.239-.757Zm3.436-.586L16 11.801V4.697l-5.803 3.546Z"/>
          </svg>
        </div>
        <div class="col-1"></div>
      </div>       
    </div>
    <span class="label results">Showing 1 to 5 of 50 results</span>


  </div>
</template>

<script>
export default {

  methods: {
    goDetail: function (message) {
      this.$router.push('/company_details'); 
      //if the route accepts params, you can also use
      // this.$router.push({name:'home', params: {id: '[paramdata]'}}); 
    }
  }

}
</script>

<style>
.searchBar{
  width: 300px;
}
.tabs{
  margin-top: 20px;
}

.tabsLinks{
  font-size: 0.7rem;
  
}

.nav-pills .nav-link{
  background-color: rgb(240, 238, 238);
}

.nav-pills .nav-link.active{
  background-color: #273550;
}

.tblabels{
  width: 100%;
  height: 35px;
  background-color: rgba(128, 128, 128, 0.192);
  margin-top: 10px;
  border-radius: 5px;
}
.label{
  font-size: 0.7rem;
}

.cardsList{
  width: 100%;
  margin-top: 20px;
  height: 60px;
  border-left: 4px solid lightgreen;
  background-color: #FAF9F6;
}

.cardsListpending{
  width: 100%;
  margin-top: 20px;
  height: 60px;
  border-left: 4px solid rgb(226, 173, 59);
  background-color: #FAF9F6;
}

.cardsListsuspend{
  width: 100%;
  margin-top: 20px;
  height: 60px;
  border-left: 4px solid rgb(235, 77, 77);
  background-color: #FAF9F6;
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
    height: 60px;
    border-left: 4px solid lightgreen;
}

.badge{
  margin-top: 15px;
  
}

.bg-success{
  color:rgb(80, 189, 80);
  background-color: rgb(163, 238, 163) !important;
}

.chatbadge{
  margin-top: 15px;
}

.formlabel{
  color: rgb(80, 189, 80);
}

.bg-danger{
  color: red;
  background-color: rgb(250, 198, 198) !important;
}

.formlabelred{
  color:rgb(247, 105, 105);
  overflow-wrap: break-word; 
}

.formlabelorange{
  color:orange;
}

.bi-chat-suspend{
  color:lightgray;
  margin-top:15px;
}

.bi-envelope-suspend{
   color:lightgray;
  margin-top:15px;
}

.results{
  margin-top: 20px;
}

</style>