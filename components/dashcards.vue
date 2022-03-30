<template>
    <div class="row">
            <div class="col-4">
                <div class="card shadow">
                <div class="card-body">
                    <p class="card-title title">Settings</p>
                    <p class="sub-heading">Account</p>
                    <div class="form-check form-switch">
                        <input class="form-check-input" type="checkbox" id="flexSwitchCheckChecked" checked>
                        <label class="form-check-label lbl" for="flexSwitchCheckChecked">Email me when someone follows me.</label>
                    </div>
                        <div class="form-check form-switch">
                        <input class="form-check-input" type="checkbox" id="flexSwitchCheckChecked" >
                        <label class="form-check-label lbl" for="flexSwitchCheckChecked">Email me when someone answers on my post.</label>
                    </div>
                    <p class="sub-heading">Application</p>
                        <div class="form-check form-switch">
                        <input class="form-check-input" type="checkbox" id="flexSwitchCheckChecked" >
                        <label class="form-check-label lbl" for="flexSwitchCheckChecked">New launches and projects.</label>
                    </div>
                        <div class="form-check form-switch">
                        <input class="form-check-input" type="checkbox" id="flexSwitchCheckChecked" checked>
                        <label class="form-check-label lbl" for="flexSwitchCheckChecked">Subscribe to newsletter</label>
                    </div>
                </div>
            </div>
             </div>
             <div class="col-4">
               <div class="card shadow">
                    <div class="card-body">
                        <p class="card-title title">Profile Information</p>
                        <span class="lbl">
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Lectus quam
                            tincidunt cras suspendisse sed vel pellentesque posuere aenean. Diam at duieu massa lacinia eget.
                        </span>
                        <center>
                             <hr class="separator">
                        </center>
                        <div class="alldetails">
                            <label class="details">Full Name: <span class="lblx">Joe M Bloggs</span></label>
                            <label class="details">Mobile: <span class="lblx">(+44)123 1234 123</span></label>
                            <label class="details">Email: <span class="lblx">joebloggs@gmail.com</span></label>
                            <label class="details">Location: <span class="lblx">United Kingdom</span></label>
                        </div>
                    </div>
                </div>
             </div>
            <div class="col-4">
                <div class="card shadow">
                <div class="card-body">
                    <p class="card-title title">We're here to help</p>
                    <span class="lbl">Our support team are here to help you with any support issues you might have.</span>
                    <p class="calllbl">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#39A6E3" class="" viewBox="0 0 16 16">
                            <path fill-rule="evenodd" d="M1.885.511a1.745 1.745 0 0 1 2.61.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.678.678 0 0 0 .178.643l2.457 2.457a.678.678 0 0 0 .644.178l2.189-.547a1.745 1.745 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.634 18.634 0 0 1-7.01-4.42 18.634 18.634 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877L1.885.511z"/>
                        </svg>
                        CALL SUPPORT ON
                    </p>
                    <span class="lbl">London</span>
                    <p class="details">020 7183 3787</p>
                    <span class="lbl">Edinburgh</span>
                    <p class="details">0131 516 2337</p>
                    <p class="chatlbl">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="#39A6E3" class="" viewBox="0 0 16 16">
                            <path d="M8 15c4.418 0 8-3.134 8-7s-3.582-7-8-7-8 3.134-8 7c0 1.76.743 3.37 1.97 4.6-.097 1.016-.417 2.13-.771 2.966-.079.186.074.394.273.362 2.256-.37 3.597-.938 4.18-1.234A9.06 9.06 0 0 0 8 15z"/>
                        </svg>
                        LIVE CHAT
                    </p>
                </div>
            </div>
            </div>
         </div>
</template>

<script>
export default {

}
</script>

<style scoped>

.title{
    color:black;
    font-size:0.9rem;
    font-weight:600;
}

.sub-heading{
    color:black;
    font-size: 0.8rem;
    padding:2px;
}

.lbl{
     color:gray;
    font-size: 0.7rem;
}


.form-switch .form-check-input:focus {
    border-color: rgba(0, 0, 0, 0.25);
    outline: 0;
    box-shadow: 0 0 0 0 rgba(0, 0, 0, 0);
    
}
.form-switch .form-check-input:checked {
    background-color: #39A6E3;
    border-color: #39A6E3;
    border: none;
}
.separator{
    color: gray;
    width: 70%;
}
.alldetails{
    margin-top: 32px;
}
.details{
    display:block;
    font-size: 0.7rem;
}
.lblx{
    color:gray;
    font-size: 0.7rem;
    display: inline-block;
    margin-left: 5px;
}

.calllbl{
    color:black;
    font-weight: 500;
    font-size: 0.7rem;
    margin-top: 30px;
}
.chatlbl{
    color:black;
    font-weight: 500;
    font-size: 0.7rem;
    margin-top: 10px;
}
</style>