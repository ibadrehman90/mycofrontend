<template>
  <div class="d-flex flex-column  p-4 bg-dark">
    <a href="/" class="d-flex align-items-center mb-3 mb-md-0 me-md-auto link-light text-decoration-none">
      <svg class="bi me-2" width="40" height="32"><use xlink:href="#bootstrap"/></svg>
      <span class="fs-4">MYCO</span>
    </a>
    <hr>
    <span class="lbl ">Menu</span>
    <ul class="nav flex-column mb-auto">
      <li class="nav-item">
        <a href="#" class="nav-link link-light" >
         
          <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="#ffff" class="icon bi bi-sliders2" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M10.5 1a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-1 0V4H1.5a.5.5 0 0 1 0-1H10V1.5a.5.5 0 0 1 .5-.5ZM12 3.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 0 1h-2a.5.5 0 0 1-.5-.5Zm-6.5 2A.5.5 0 0 1 6 6v1.5h8.5a.5.5 0 0 1 0 1H6V10a.5.5 0 0 1-1 0V6a.5.5 0 0 1 .5-.5ZM1 8a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 0 1h-2A.5.5 0 0 1 1 8Zm9.5 2a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-1 0V13H1.5a.5.5 0 0 1 0-1H10v-1.5a.5.5 0 0 1 .5-.5Zm1.5 2.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 0 1h-2a.5.5 0 0 1-.5-.5Z"/>
        </svg>
          <nuxt-link style="color:rgb(206, 206, 206)" to="/dashboard">Dashboard</nuxt-link>  
        </a>
      </li>
      <li>
        <a href="#" class="nav-link link-light">
          <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="#ffff" class="icon bi bi-person-square" viewBox="0 0 16 16">
            <path d="M11 6a3 3 0 1 1-6 0 3 3 0 0 1 6 0z"/>
            <path d="M2 0a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2H2zm12 1a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1v-1c0-1-1-4-6-4s-6 3-6 4v1a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1h12z"/>
         </svg>
          My Account
        </a>
      </li>
      <li>
        <a href="#" class="nav-link link-light">
         <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="#ffff" class="icon bi bi-building" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M14.763.075A.5.5 0 0 1 15 .5v15a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5V14h-1v1.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V10a.5.5 0 0 1 .342-.474L6 7.64V4.5a.5.5 0 0 1 .276-.447l8-4a.5.5 0 0 1 .487.022zM6 8.694 1 10.36V15h5V8.694zM7 15h2v-1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5V15h2V1.309l-7 3.5V15z"/>
            <path d="M2 11h1v1H2v-1zm2 0h1v1H4v-1zm-2 2h1v1H2v-1zm2 0h1v1H4v-1zm4-4h1v1H8V9zm2 0h1v1h-1V9zm-2 2h1v1H8v-1zm2 0h1v1h-1v-1zm2-2h1v1h-1V9zm0 2h1v1h-1v-1zM8 7h1v1H8V7zm2 0h1v1h-1V7zm2 0h1v1h-1V7zM8 5h1v1H8V5zm2 0h1v1h-1V5zm2 0h1v1h-1V5zm0-2h1v1h-1V3z"/>
        </svg>  
          <nuxt-link style="color:rgb(206, 206, 206)" to="/my_companies">My Companies</nuxt-link>    
          
        </a>
      </li>
      <li>
        <a href="#" class="nav-link link-light">
         <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="#ffff" class="icon bi bi-envelope-fill" viewBox="0 0 16 16">
            <path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414.05 3.555ZM0 4.697v7.104l5.803-3.558L0 4.697ZM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586l-1.239-.757Zm3.436-.586L16 11.801V4.697l-5.803 3.546Z"/>
        </svg>
          Contact Us
        </a>
      </li>
       <span class="lbl">Services</span>
      <li>
        <a href="#" class="nav-link link-light " data-bs-toggle="collapse" data-bs-target="#company-collapse">
          <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="#ffff" class="icon bi bi-building" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M14.763.075A.5.5 0 0 1 15 .5v15a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5V14h-1v1.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5V10a.5.5 0 0 1 .342-.474L6 7.64V4.5a.5.5 0 0 1 .276-.447l8-4a.5.5 0 0 1 .487.022zM6 8.694 1 10.36V15h5V8.694zM7 15h2v-1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5V15h2V1.309l-7 3.5V15z"/>
            <path d="M2 11h1v1H2v-1zm2 0h1v1H4v-1zm-2 2h1v1H2v-1zm2 0h1v1H4v-1zm4-4h1v1H8V9zm2 0h1v1h-1V9zm-2 2h1v1H8v-1zm2 0h1v1h-1v-1zm2-2h1v1h-1V9zm0 2h1v1h-1v-1zM8 7h1v1H8V7zm2 0h1v1h-1V7zm2 0h1v1h-1V7zM8 5h1v1H8V5zm2 0h1v1h-1V5zm2 0h1v1h-1V5zm0-2h1v1h-1V3z"/>
        </svg>  
          New Company
        <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="#ffff" class="dropdown-icon bi bi-caret-down-fill" viewBox="0 0 16 16">
            <path d="M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z"/>
        </svg>
        </a>
        <div class="collapse" id="company-collapse">
          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
            <li><a href="#" class="link-light">Overview</a></li>
            <li><a href="#" class="link-light">Updates</a></li>
            <li><a href="#" class="link-light">Reports</a></li>
          </ul>
        </div>
      </li>
        <li>
        <a href="#" class="nav-link link-light" data-bs-toggle="collapse" data-bs-target="#service-collapse" aria-expanded="false">
          <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="#ffff" class="icon bi bi-arrow-clockwise" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M8 3a5 5 0 1 0 4.546 2.914.5.5 0 0 1 .908-.417A6 6 0 1 1 8 2v1z"/>
            <path d="M8 4.466V.534a.25.25 0 0 1 .41-.192l2.36 1.966c.12.1.12.284 0 .384L8.41 4.658A.25.25 0 0 1 8 4.466z"/>
        </svg>
          Service Renewal
         <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="#ffff" class="dropdown-icon bi bi-caret-down-fill" viewBox="0 0 16 16">
            <path d="M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z"/>
        </svg>
        </a>
         <div class="collapse" id="service-collapse">
          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
            <li><a href="#" class="link-light">Overview</a></li>
            <li><a href="#" class="link-light">Updates</a></li>
            <li><a href="#" class="link-light">Reports</a></li>
          </ul>
        </div>
      </li>
        <li>
        <a href="#" class="nav-link link-light" data-bs-toggle="collapse" data-bs-target="#price-collapse" aria-expanded="false">
         <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="#ffff" class="icon bi bi-tag" viewBox="0 0 16 16">
            <path d="M6 4.5a1.5 1.5 0 1 1-3 0 1.5 1.5 0 0 1 3 0zm-1 0a.5.5 0 1 0-1 0 .5.5 0 0 0 1 0z"/>
            <path d="M2 1h4.586a1 1 0 0 1 .707.293l7 7a1 1 0 0 1 0 1.414l-4.586 4.586a1 1 0 0 1-1.414 0l-7-7A1 1 0 0 1 1 6.586V2a1 1 0 0 1 1-1zm0 5.586 7 7L13.586 9l-7-7H2v4.586z"/>
        </svg>
          Prices & Services
        <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="#ffff" class="dropdown-icon bi bi-caret-down-fill" viewBox="0 0 16 16">
            <path d="M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z"/>
        </svg>
        </a>
          <div class="collapse" id="price-collapse">
          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
            <li><a href="#" class="link-light">Overview</a></li>
            <li><a href="#" class="link-light">Updates</a></li>
            <li><a href="#" class="link-light">Reports</a></li>
          </ul>
        </div>
      </li>
        <li>
        <a href="#" class="nav-link link-light" data-bs-toggle="collapse" data-bs-target="#meeting-collapse" aria-expanded="false">
          <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="#ffff" class="icon bi bi-people-fill" viewBox="0 0 16 16">
            <path d="M7 14s-1 0-1-1 1-4 5-4 5 3 5 4-1 1-1 1H7zm4-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"/>
            <path fill-rule="evenodd" d="M5.216 14A2.238 2.238 0 0 1 5 13c0-1.355.68-2.75 1.936-3.72A6.325 6.325 0 0 0 5 9c-4 0-5 3-5 4s1 1 1 1h4.216z"/>
            <path d="M4.5 8a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5z"/>
        </svg> 
          Meeting Spaces
          <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="#ffff" class="dropdown-icon bi bi-caret-down-fill" viewBox="0 0 16 16">
            <path d="M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z"/>
        </svg>
        </a>
         <div class="collapse" id="meeting-collapse">
          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
            <li><a href="#" class="link-light">Overview</a></li>
            <li><a href="#" class="link-light">Updates</a></li>
            <li><a href="#" class="link-light">Reports</a></li>
          </ul>
        </div>
      </li>
      <span class="lbl ">Other</span>
       <li>
        <a href="#" class="nav-link link-light" data-bs-toggle="collapse" data-bs-target="#preferences-collapse" aria-expanded="false">
          <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="#ffff" class="icon bi bi-gear-fill" viewBox="0 0 16 16">
            <path d="M9.405 1.05c-.413-1.4-2.397-1.4-2.81 0l-.1.34a1.464 1.464 0 0 1-2.105.872l-.31-.17c-1.283-.698-2.686.705-1.987 1.987l.169.311c.446.82.023 1.841-.872 2.105l-.34.1c-1.4.413-1.4 2.397 0 2.81l.34.1a1.464 1.464 0 0 1 .872 2.105l-.17.31c-.698 1.283.705 2.686 1.987 1.987l.311-.169a1.464 1.464 0 0 1 2.105.872l.1.34c.413 1.4 2.397 1.4 2.81 0l.1-.34a1.464 1.464 0 0 1 2.105-.872l.31.17c1.283.698 2.686-.705 1.987-1.987l-.169-.311a1.464 1.464 0 0 1 .872-2.105l.34-.1c1.4-.413 1.4-2.397 0-2.81l-.34-.1a1.464 1.464 0 0 1-.872-2.105l.17-.31c.698-1.283-.705-2.686-1.987-1.987l-.311.169a1.464 1.464 0 0 1-2.105-.872l-.1-.34zM8 10.93a2.929 2.929 0 1 1 0-5.86 2.929 2.929 0 0 1 0 5.858z"/>
        </svg>
          Preferences
          <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="#ffff" class="dropdown-icon bi bi-caret-down-fill" viewBox="0 0 16 16">
            <path d="M7.247 11.14 2.451 5.658C1.885 5.013 2.345 4 3.204 4h9.592a1 1 0 0 1 .753 1.659l-4.796 5.48a1 1 0 0 1-1.506 0z"/>
        </svg>
        </a>
          <div class="collapse" id="preferences-collapse">
          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
            <li><a href="#" class="link-light">Overview</a></li>
            <li><a href="#" class="link-light">Updates</a></li>
            <li><a href="#" class="link-light">Reports</a></li>
          </ul>
        </div>
      </li>

       <div class="cardDiv">

        <div style="margin-top:10px">
            <div>
                <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="#ffff" class="quest bi bi-question-circle-fill" viewBox="0 0 16 16">
                 <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM5.496 6.033h.825c.138 0 .248-.113.266-.25.09-.656.54-1.134 1.342-1.134.686 0 1.314.343 1.314 1.168 0 .635-.374.927-.965 1.371-.673.489-1.206 1.06-1.168 1.987l.003.217a.25.25 0 0 0 .25.246h.811a.25.25 0 0 0 .25-.25v-.105c0-.718.273-.927 1.01-1.486.609-.463 1.244-.977 1.244-2.056 0-1.511-1.276-2.241-2.673-2.241-1.267 0-2.655.59-2.75 2.286a.237.237 0 0 0 .241.247zm2.325 6.443c.61 0 1.029-.394 1.029-.927 0-.552-.42-.94-1.029-.94-.584 0-1.009.388-1.009.94 0 .533.425.927 1.01.927z"/>
                </svg>
            </div>
           
            <div style="width:65%;float:right">
                <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="#ffff" class="chat bi bi-chat-text-fill" viewBox="0 0 16 16">
                    <path d="M16 8c0 3.866-3.582 7-8 7a9.06 9.06 0 0 1-2.347-.306c-.584.296-1.925.864-4.181 1.234-.2.032-.352-.176-.273-.362.354-.836.674-1.95.77-2.966C.744 11.37 0 9.76 0 8c0-3.866 3.582-7 8-7s8 3.134 8 7zM4.5 5a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1h-7zm0 2.5a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1h-7zm0 2.5a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1h-4z"/>
                </svg>
                 <p style="margin-left:5px;color:white;">Live chat</p>
            </div>
        </div>
        <div style="margin-left:20px;margin-right:20px;height:90px;margin-top:50px;">

            <span style="font-weight:bold;color:white">Need help?</span><br>
            <span style="color:white;font-size:14px;">Please check our docs</span>
             <div class="d-grid gap-2 ">
                <button class="btn btn-light docbtn" type="button">DOCUMENTATION</button>
            </div>

        </div>

    </div>
    </ul>
   
    <hr>
    
  </div>
  
</template>

<script>

export default {

    name:"SideBar",
    head: {
    script: [
      {
        src: "/sidebar.js",
      },
    ]
  }
    
}

</script>



<style scoped>
.dropdown-toggle { outline: 0; }

.nav-flush .nav-link {
  border-radius: 0;
}

.btn-toggle {
  display: inline-flex;
  align-items: center;
  padding: .25rem .5rem;
  font-weight: 600;
  color: #ffff;
  background-color: transparent;
  border: 0;
}

.nav-link{
    color: rgb(206, 206, 206);
    font-size:0.8rem;
}
.nav-link:hover
{
    background-color: #273550;
    border-left: 3px solid #39A6E3;
    color:white;
}
.nav-link:focus {
  color: #ffff;
  
}

/* .nav-link::before {
  width: 1.25em;
  line-height: 0;
  content: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 16 16'%3e%3cpath fill='none' stroke='rgba%280,0,0,.5%29' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M5 14l6-6-6-6'/%3e%3c/svg%3e");
  transition: transform .35s ease;
  transform-origin: .5em 50%;
} */

.nav-link[aria-expanded="true"] {
  color: rgb(255, 255, 255);
}
.nav-link[aria-expanded="true"]::before {
  transform: rotate(90deg);
}

.btn-toggle-nav a {
  display: inline-flex;
  padding: .1875rem .5rem;
  margin-top: .125rem;
  margin-left: 1.25rem;
  text-decoration: none;
  font-size:0.75rem;
}
.btn-toggle-nav a:hover,
.btn-toggle-nav a:focus {
  background-color: #39A6E3;
}

.scrollarea {
  overflow-y: auto;
}

.fw-semibold { font-weight: 600; }
.lh-tight { line-height: 1.25; }

.bg-dark{
    background-color: #2C3B58 !important;
    height: 100%;
}
.lbl{
    color:#818CA3;
    padding: 5px;
    font-size: 0.8rem;
}

.icon{
    margin-right: 5px;
}

.dropdown-icon{
    float: right;
}

.btn-toggle:hover,
.btn-toggle:focus {
  color: rgba(255, 255, 255, 0.85);
  background-color: #263632;
}

.cardDiv{
    margin-top: 20px;
    height: 150px;
    background-color: #39A6E3;
    border-radius: 25px;
    margin-bottom: 20px;
}

.card{
    width: 80%;
    margin: 10px auto;
    background-color: #39A6E3;
    border-radius: 25px;
    vertical-align: middle;
}

.docbtn{
     border-radius: 10px;
     font-size: small;
     margin-top:5px;
}

.docbtn:hover{
    background-color:#2C3B58;
    color:white;
}

.quest{
    float: left;
    margin-left: 20px;
    color:white;
}

.chat{
    float: right;
    margin-right: 20px;
    color:white;
}

</style>