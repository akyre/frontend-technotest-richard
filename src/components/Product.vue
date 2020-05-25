<template>
    <div class="Home">
      <div class="code-review">
        <div class="code-review-title">
          Code review
        </div>
        <div class="code-review-content">
          <div class="code-review-content-texte">
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam commodo consequat velit, sit amet consectetur lectus varius non. Phasellus semper risus et eros faucibus commodo. Maecenas efficitur nunc vitae sagittis hendrerit. Sed sed ante vehicula, accumsan est quis, aliquam tortor.
              <br /><br />
              Sed consequat euismod erat, ut molestie erat blandit at. Vestibulum luctus efficitur diam a rutrum. Integer sit amet viverra justo, et aliquet mauris. Cras faucibus ante vitae mattis congue. Ut eget viverra sapien. Nullam non varius neque. Nunc condimentum laoreet lorem, et commodo eros
            </p>
            <button class="code-review-content-texte-button" onClick="">
              <p>Get started</p>
            </button>
          </div>
          <div class="code-review-content-deco">
            <div class="code-review-content-deco-color" />
            <div class="code-review-content-image">
              <img src="../assets/code-review-image.png">
            </div>
          </div>
        </div>
      </div>

      <div class="code-analytics">
        <div class="code-analytics-title">
          Code Analytics
        </div>
        <div class="code-analytics-content">
          <div class="code-analytics-content-deco">
            <div class="code-analytics-content-deco-color" />
            <div class="code-analytics-content-image">
              <img src="../assets/code-analytics-image.png">
            </div>
          </div>
          <div class="code-analytics-content-texte">
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam commodo consequat velit, sit amet consectetur lectus varius non. Phasellus semper risus et eros faucibus commodo. Maecenas efficitur nunc vitae sagittis hendrerit. Sed sed ante vehicula, accumsan est quis, aliquam tortor.
              <br /><br />
              Sed consequat euismod erat, ut molestie erat blandit at. Vestibulum luctus efficitur diam a rutrum. Integer sit amet viverra justo, et aliquet mauris. Cras faucibus ante vitae mattis congue. Ut eget viverra sapien. Nullam non varius neque. Nunc condimentum laoreet lorem, et commodo eros
            </p>
            <button class="code-analytics-content-texte-button" onClick="">
              <p>Get started</p>
            </button>
          </div>
        </div>
      </div>

      <div class="code-benchmarking">
        <div class="code-benchmarking-title">
          Code benchmarking
        </div>
        <div class="code-benchmarking-content">
          <div class="code-benchmarking-content-texte">
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam commodo consequat velit, sit amet consectetur lectus varius non. Phasellus semper risus et eros faucibus commodo. Maecenas efficitur nunc vitae sagittis hendrerit. Sed sed ante vehicula, accumsan est quis, aliquam tortor.
              <br /><br />
              Sed consequat euismod erat, ut molestie erat blandit at. Vestibulum luctus efficitur diam a rutrum. Integer sit amet viverra justo, et aliquet mauris. Cras faucibus ante vitae mattis congue. Ut eget viverra sapien. Nullam non varius neque. Nunc condimentum laoreet lorem, et commodo eros
            </p>
            <button class="code-benchmarking-content-texte-button" onClick="">
              <p>Get started</p>
            </button>
          </div>
          <div class="code-benchmarking-content-deco">
            <div class="code-benchmarking-content-deco-color" />
            <div class="code-benchmarking-content-image">
              <img src="../assets/code-benchmarking-image.png">
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Roboto:100,100i,300,300i,400,400i,500,500i,700,700i,900,900i&display=swap');

/* product presentation */

.Product-presentation {
  background: #F6F9FC 0% 0% no-repeat padding-box;
  border-top: 3px solid #F6F9FC;
  margin-bottom: 200px;
}

.product-presentation-deco {
  background: white;
  display: flex;
}

.triangle-deco1 {
  border-top: 600px solid #F6F9FC;
  border-left: 600px solid transparent;
  border-right: 600px solid transparent;
}

.triangle-deco2 {
  border-top: 346px solid #F6F9FC;
  border-left: 346px solid transparent;
  border-right: 346px solid transparent;
}

.saying {
  margin-top: 50px;
  margin-left: 25%;
  margin-right: 20%;
  height: 117px;
  text-align: left;
  letter-spacing: 1px;
  color: #91AFFF;
  opacity: 1;
}

.saying-text {
  font-weight: lighter;
  font-style: italic;
  font-size: 51px;
  float: left;
  font-family: "Light Italic 71px/34px Roboto";
}

.saying-author {
  font-size: 26px;
  float: right;
  font-family: "Light 26px/34px Roboto";
}

.description {
  margin-left: 13%;
  margin-right: 13%;
  margin-top: 145px;
  font-size: 60px;
  font-family: "Regular 80px/94px Roboto";
  text-align: center;
  color: #91AFFF;
  opacity: 1;
}

.buttons-container {
  margin-top: 145px;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  /* border: 3px solid #F6F9FC; */
  margin-bottom: 50px;
}

.button1 {
  display: inline-block;
  text-decoration: none;
  font-family: "Regular 80px/94px Roboto";
  color: white;
  border-radius: 24px;
  padding: 0px 20px;
  -moz-transition: all 0.2s;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
  background: #FF1053 0% 0% no-repeat padding-box;
  font-size: 2em;
  /* margin-bottom: 65px; */
  border: none;
}

.button2 {
  display: inline-block;
  text-decoration: none;
  font-family: "Regular 80px/94px Roboto";
  color: white;
  border-radius: 24px;
  padding: 0px 40px;
  -moz-transition: all 0.2s;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
  background: #73C1C6 0% 0% no-repeat padding-box;
  font-size: 1.5em;
  /* margin-bottom: 65px; */
  border: none;
}

.button1:hover {
  cursor: pointer;
}

.button2:hover {
  cursor: pointer;
}

/* code review */

.code-review {
  margin-bottom: 350px;
}

.code-review-title {
  margin-left: 12.5%;
  font-family: "Medium 100px/117px Roboto";
  color: #91AFFF;
  /* font-size: 75px; */
  font-size: 4vw;
}

.code-review-content {
  margin-left: 12.5%;
  background: #F6F9FC;
  position: relative;
  /* border: 3px solid green; */
  border: 3px solid #F6F9FC;
}

.code-review-content-texte {
  margin-top: 88px;
  margin-left: 51px;
  width: 55%;
  font-size: 29.5px;
  text-align: left;
  font-family: "Regular 43px/56px PT Sans Narrow";
  color: #ADC4FF;
  margin-bottom: 65px;
}

.code-review-content-texte-button {
  font-family: "Medium 55px/64px Roboto;";
  color: white;
  border-radius: 25px;
  padding: 0px 20px;
  -moz-transition: all 0.2s;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
  background: #FF1053 0% 0% no-repeat padding-box;
  font-size: 1em;
  text-align: center;
  margin: 0 auto;
  display: block;
  border: none;
  border: none;
}

.code-review-content-texte-button:hover {
  border: red;
  cursor: pointer;
}

.code-review-content-deco {
  position: absolute;
  top: 20%;
  right: 5%;
  width: 34%;
  height: 60%;
  /* border: 3px solid blue; */
}

.code-review-content-deco-color {
  position: absolute;
  width: 100%;
  height: 100%;
  background: #FF1053 0% 0% no-repeat padding-box;
  transform: matrix(0.99, -0.16, 0.16, 0.99, 0, 0);
}

.code-review-content-image {
  position: absolute;
  top: 20%;
  right: -5%;
  width: 95%;
  height: 75%;
  /* border: 3px solid yellow; */
}

.code-review-content-image img {
  width: 100%;
  height: 100%;
}

/* Code Analytics */

.code-analytics {
  margin-bottom: 350px;
}

.code-analytics-title {
  font-family: "Medium 100px/117px Roboto";
  color: #91AFFF;
  font-size: 75px;
  font-size: 4vw;
  margin-left: 57%;
}

.code-analytics-content {
  margin-right: 12.5%;
  background: #F6F9FC;
  position: relative;
  /* border: 3px solid green; */
  border: 3px solid #F6F9FC;
}

.code-analytics-content-texte {
  margin-top: 88px;
  margin-left: 44%;
  width: 55%;
  font-size: 29.5px;
  text-align: left;
  font-family: "Regular 43px/56px PT Sans Narrow";
  color: #ADC4FF;
  margin-bottom: 65px;
}

.code-analytics-content-texte-button {
  font-family: "Medium 55px/64px Roboto";
  color: white;
  border-radius: 25px;
  padding: 0px 20px;
  -moz-transition: all 0.2s;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
  background: #73C1C6 0% 0% no-repeat padding-box;
  font-size: 1em;
  text-align: center;
  margin: 0 auto;
  display: block;
  border: none;
}

.code-analytics-content-texte-button:hover {
  border: #73C1C6;
  cursor: pointer;
}

.code-analytics-content-deco {
  position: absolute;
  top: 20%;
  left: 8%;
  width: 30%;
  height: 65%;
  /* border: 3px solid blue; */
}

.code-analytics-content-deco-color {
  position: absolute;
  width: 100%;
  height: 100%;
  background: #73C1C6 0% 0% no-repeat padding-box;
  transform: matrix(0.99, -0.16, 0.16, 0.99, 0, 0);
}

.code-analytics-content-image {
  position: absolute;
  top: 3%;
  right: -5%;
  width: 95%;
  height: 85%;
  /* border: 3px solid yellow; */
}

.code-analytics-content-image img {
  width: 100%;
  height: 100%;
}

/* code benchmarking */

.code-benchmarking {
  margin-bottom: 350px;
}

.code-benchmarking-title {
  margin-left: 12.5%;
  font-family: "Medium 100px/117px Roboto";
  color: #91AFFF;
  font-size: 75px;
}

.code-benchmarking-content {
  margin-left: 12.5%;
  background: #F6F9FC;
  position: relative;
  /* border: 3px solid green; */
  border: 3px solid #F6F9FC;
}

.code-benchmarking-content-texte {
  margin-top: 88px;
  margin-left: 51px;
  width: 55%;
  font-size: 29.5px;
  text-align: left;
  font-family: "Regular 43px/56px PT Sans Narrow";
  color: #ADC4FF;
  margin-bottom: 65px;
}

.code-benchmarking-content-texte-button {
  font-family: "Medium 55px/64px Roboto;";
  color: white;
  border-radius: 25px;
  padding: 0px 20px;
  -moz-transition: all 0.2s;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
  background: #FFE27B 0% 0% no-repeat padding-box;
  font-size: 1em;
  text-align: center;
  margin: 0 auto;
  display: block;
  border: none;
}

.code-benchmarking-content-texte-button:hover {
  border: #FFE27B;
  cursor: pointer;
}

.code-benchmarking-content-deco {
  position: absolute;
  top: 30%;
  right: 10%;
  width: 25%;
  height: 40%;
  /* border: 3px solid blue; */
}

.code-benchmarking-content-deco-color {
  position: absolute;
  width: 100%;
  height: 100%;
  background: #FFE27B 0% 0% no-repeat padding-box;
  transform: matrix(0.95, 0.33, -0.33, 0.95, 0, 0);
}

.code-benchmarking-content-image {
  position: absolute;
  top: -8%;
  right: -7%;
  width: 95%;
  height: 90%;
  /* border: 3px solid yellow; */
}

.code-benchmarking-content-image img {
  width: 100%;
  height: 100%;
}

</style>