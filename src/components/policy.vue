<template>
    <div class="component">
        <!-- <button class="btn btn-primary">click</button> -->
        <div class="container">
            <div class="row">
                <div class="col-md-2"></div>
                <div class="col-md-8">
                    <div class="header">
                        <h5>PRIVACY POLICY</h5>
                        <h1>Our Commitment to Protecting Your Privacy</h1>
                    </div><br>
                    <br>

                    <div class="body">
                        <p>
                            This Privacy Policy describes how Shift4, our Affiliates, 
                            which as of the effective date of this revision include Harbortouch Financial,
                            LLC, Restaurant Manager, LLC, Positouch, LLC, FuturePOS, LLC, Independent Resource Network,
                            LLC, Merchant-Link, LLC, LLC, Micros Retail Systems, LLC, Shift4Shop, LLC, Inspiration4, 
                            LLC, and The Customer Connection II, LLC. (collectively, “Shift4,” “us,” “we”) collect, use,
                            disclose, transfer, store, retain, or otherwise process any Personal Information received from
                            you when you apply or sign up for or use any of our payment processing, payment gateway, 
                            or point-of-sale services or our various other products (collectively, “Services”).
                        </p><br>

                        <p>
                            <b>
                                Please read this Policy carefully. By accessing, browsing or using our website or Services, 
                                you confirm that you have read, understand and agree to the terms of this Privacy Policy.
                            </b>
                        </p><br>

                        <p>
                            As used in this policy “Personal Information” means information and data that identifies you or 
                            makes you identifiable as a natural person, such as name, age, home address, home phone number, 
                            date of birth, social security number and personal e-mail address. “Personal Information” covers 
                            all information defined as “personal data” under Art. 4(1) of the European Union’s (EU) General Data 
                            Protection Regulation (GDPR). This privacy policy is designed to apply to our website visitors, users 
                            of our Services, prospective users of our Services, and our authorized distributors, wherever located. 
                            As a result, the privacy policy will include provisions applicable globally as well as provisions that 
                            are only required in particular jurisdictions. Shift4, may update this Privacy Policy from time to time. 
                            Updates will be reflected on our website, located at https://www.shift4.com/legal/. When we change the 
                            policy in a material way, a notice will be posted on our website along with the updated Privacy Policy.
                        </p>
                    </div>
                </div>
                <div class="col-md-2"></div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
  name: 'policy'
  
}
</script>

<style scoped>
.header {
    color: red;
}
.header h5 {
    font-weight: lighter;
}
.header h1 {
    font-weight: bolder;
}
.body p {
    font-size: 18px;
    font-weight: lighter;
    text-align: left;
}
.body p b {
    font-weight: 700;
}
.col-md-8 {
    text-align: center;
    padding: 40px;
}

@media screen and (max-width: 700px){
    * {
        margin: 0%;
        padding: 0%;   
    }
    .component {
        display: flex;
        overflow-x: hidden;
    }
    .col-md-8{
        overflow-x: hidden;
        padding: 18px;
    }
    .header{
        text-align: center;
    }
    .header h1 {
        /* width: 250px; */
        font-size: 30px;
        margin-top: 10px;
        padding: 20px;

    }
    .header h5 {
        /* width: 250px; */
        font-size: 20px;

    }
    .body p {
        font-size: 18px;
        font-weight: lighter;
        text-align: left;
        /* width: 280px; */
    }
}

</style>