 <!DOCTYPE html>

<link rel="stylesheet"type="text/css"href="styles.css"media="all">
<style>
 * {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}

body {
  font-family: Georgia, "Times New Roman", Times, serif;
  color: orange;
font-size: 2rem;
  padding: .6rem 2rem;
  font-weight: bold;
  color: white;
  background: linear-gradient(to right, blue, green);
  border-radius: 100px;
  box-shadow: rgba(1000, 1000, 1110, 2) 0px 7px 29px 0px;
  cursor: pointer;
  border:none;

  margin:0rem auto;
  padding: 1px 1rem;

  
  
 
}

.container {
  max-width: 45rem;
  margin: 1rem auto;
  padding: 1px 2rem;
  border: 10px solid;
 background-image:url("krish3.jpg");

  background: linear-gradient(to right, blue, green);
  border-radius: 10px;
  box-shadow: rgba(1000, 1000, 1110, 2) 0px 7px 29px 0px;
  cursor: pointer;
  border: none;
 

}

.main-heading {
  font-size: 5rem;
  margin: 2rem 0rem 1rem;
  color: white;
  text-align: center;
}

/* form section */
.form-class {
  margin: 2rem 0px;
}

.form-control {
  display: flex;
  flex-direction: column;
}

.heading-field {
  margin: 1rem 0px 0.6rem;
}

.field-head {
  font-size: 2rem;
}

.input-div {
  margin-bottom: 1rem;
}

.field-inputs {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
}

.form-control-input {
  font-size: 1.5rem;
  padding: 0.4rem 0px;
  text-indent: 0.5rem;
  border: none;
  outline: 1px solid #999;
  border-radius: 7px;
  width: 100%;
  color: #999;
}
option {
  color: #999;
}
.radio {
  outline: none;
}

.form-control-input:focus {
  color: #212529;
  background-color: #fff;
  border-color: #86b7fe;
  outline: 0;
  box-shadow: 0 0 0 0.25rem rgb(13 110 253 / 25%);
}

.help-text {
  font-size: 0.7rem;
  margin-top: 0.4rem;
  padding: 0.1rem;
}



h1 {
font-size:4rem;
}
.container::before{
 content:'';
 position: absolute;
 top:-50%
 left:-50%;
 width:380px;
height:420px;
background-color:linear-gradient<0dem,transparent,
  transparent,#45f3ff,#45f3ff,#45f3ff);
  z-index: 1;
  animation: animagte;
}
button{
font-size: 2rem;
  padding: .6rem 2rem;
  font-weight: bold;
  color: white;
  background: linear-gradient(to right, blue, green);
  border-radius: 100px;
  box-shadow: rgba(1000, 1000, 1110, 2) 10px 7px 20px 0px;
  cursor: pointer;
  border: none;
  align-items:center;
  justify-content:center;
  align-items:center;
  
}
  
</style>
<div class="container">
   <h1 main-heading>REGISTER FORM:</h1>
  

  <hr style="color:blue">
  <form class="form-class">
    <div class="form-control">

      <div class="heading-field">
        <h3 class="field-head">Student Name </h3>
      </div>
      <div class="field-inputs">
        <div class="input-div">
          <input type="text" class="form-control-input" id="first-name" name="first name" required>
          <div id="first-name-help" class="help-text">Enter Your First Name</div>
        </div>
        <div class="input-div">
          <input type="text" class="form-control-input" id="last-name" name="last name" required>
          <div id="last-name-help" class="help-text">Enter last First Name</div>
        </div>
      </div>
    </div>
      <div class="form-control">

      <div class="heading-field">
        <h3 class="field-head">Address</h3>
      </div>

      <div>
        <div class="input-div">
          <input type="text" class="form-control-input" id="street-address" name="address" required>
          <div id="street-address-help" class="help-text">Street Address</div>
        </div>
      </div>
      <div>
        <div class="input-div">
          <input type="text" class="form-control-input" id="street-address-2" name="street" required>
          <div id="street-address-2-help" class="help-text">Street Address Line 2</div>
        </div>
      </div>

      <div class="field-inputs">
        <div class="input-div">
          <input type="text" class="form-control-input" id="city-name" name="city" required>
          <div id="city-help" class="help-text">City</div>
        </div>
        <div class="input-div">
          <input type="text" class="form-control-input" id="state-name" name="state" required>
          <div id="state-name-help" class="help-text">State</div>
        </div>
      </div>
 <div class="heading-field">
        <h3 class="field-head">Contact </h3>
      </div>
      <div class="field-inputs">
        <div class="input-div">
         
          <input type="number" class="form-control-input" id="phone number" name="number" required>
          <div id="phone-number-help" class="help-text">phone number</div>
       </div>
        <div class="field-inputs">
        <div class="input-div">
         <input type="text"styles="float:left" class="form-control-input" id="gmail" name="gmail" required><br>
          <div id="gmail" class="help-text">gmail</div>
        </div>
       
       
      <div class=button>
        <button>submit</button>
      </div>
        
