<template>

  <header >
    <div class="px-3 py-2 bg-light shadow ">
      <div class="container">
       
        <div class=" navBar d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
             <div>
            <img class="logo" src="../static/imgs/logo.png"/>
        </div>
          <a href="/" class="d-flex align-items-center my-2 my-lg-0 me-lg-auto  text-decoration-none">
            <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"/></svg>
          </a>

          <ul class="nav col-12 col-lg-auto  my-2 justify-content-center my-md-0 text-small">
            <li>
              <a href="#" class="nav-link ">
                <svg class="bi d-block mx-auto mb-1" width="24" height="24"></svg>
                Upload ID
              </a>
            </li>
            <li>
              <a href="#" class="nav-link">
                <svg class="bi d-block mx-auto mb-1" width="24" height="24"><use xlink:href="#speedometer2"/></svg>
                Make a Payment
              </a>
            </li>
            <li>
              <a href="#" class="nav-link">
                <svg class="bi d-block mx-auto mb-1" width="24" height="24"><use xlink:href="#table"/></svg>
                Our Offices
              </a>
            </li>
            <li>
              <a href="#" class="nav-link">
                <svg class="bi d-block mx-auto mb-1" width="24" height="24"></svg>
                Live Chat
              </a>
            </li>
            <li>
              <a href="#" class="nav-link">
                <svg class="bi d-block mx-auto mb-1" width="24" height="24"></svg>
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#ffff" class="bi bi-bell-fill" viewBox="0 0 16 16">
                    <path d="M8 16a2 2 0 0 0 2-2H6a2 2 0 0 0 2 2zm.995-14.901a1 1 0 1 0-1.99 0A5.002 5.002 0 0 0 3 6c0 1.098-.5 6-2 7h14c-1.5-1-2-5.902-2-7 0-2.42-1.72-4.44-4.005-4.901z"/>
                </svg>
              </a>
            </li>
          </ul>
          <a href="#" class="d-block link-dark text-decoration-none dropdown-toggle"  data-bs-toggle="dropdown" aria-expanded="false">
            <svg class="bi d-block mx-auto mb-1" width="24" height="24"><use xlink:href="#grid"/></svg>
            <img src="https://github.com/mdo.png" alt="mdo" width="32" height="32" class="rounded-circle">
            <span class="name">Joe Bloggs</span>
          </a>
          <ul class="dropdown-menu text-small shadow" aria-labelledby="dropdownUser2">
            <li><a class="dropdown-item" href="#">New project...</a></li>
            <li><a class="dropdown-item" href="#">Settings</a></li>
            <li><a class="dropdown-item" href="#">Profile</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Sign out</a></li>
          </ul>
       
        </div>
      </div>
    </div>
  </header>
</template>

<script>

export default {

}
</script>

<style>

.navBar{
    margin-top:-20px;
}

.name{
    font-size: 0.8rem;
    padding:2px;
}

.form-control-dark {
  color: grey;
  background-color: var(--bs-dark);
  border-color: var(--bs-gray);
}
.form-control-dark:focus {
  color: rgb(95, 44, 44);
  background-color: var(--bs-dark);
  border-color: #fff;
  box-shadow: 0 0 0 .25rem rgba(255, 255, 255, .25);
}

.bi {
  vertical-align: -.125em;
  fill: currentColor;
}

.text-small {
  font-size: 85%;
}

.dropdown-toggle {
  outline: 0;
}

.text-white{
    color:grey
}

.nav-link{
    color:gray;
}

.nav-link:hover{
    color: #39A6E3;
}

.dropdown-item:hover{
    background-color:#39A6E3;
    color:white;
}

.logo{
    width: 170px;
    height: 20p;
    margin-top: 17px;
}


</style>