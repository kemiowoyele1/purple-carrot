<template>
   <div class="home">
        <div class="main-view1">
       
    </div>
    <div class="home-view2">
       <div class="onions"></div>
       <div class="lemon"></div>
       <div class="pear"></div>
       <div class="nuts"></div>
    </div>
     <div class="carton"></div>
     <div class="home-view3"></div>
     <div class="home-view4"></div>
     <div class="home-view5">
         <div class="view5-container">
             <div class="fivea">
                <div class="left-side5">
                     <div class="bar"></div>
                 <div class="view5-text">
                     People are digging our <br>  meals! Hear what they <br> are saying about plant- <br> based living.
                 </div>
                </div>
                
            
             <div class="carousel"></div>
              </div>
              <div class="logo-div">
                  <span class="logos logo1"></span>
                  <span class="logos logo2"></span>
                  <span class="logos logo3"></span>
                  <span class="logos logo4"></span>
                  <span class="logos logo5"></span>
                  <span class="logos logo6"></span>
              </div>
         </div>
     </div>

    
   </div>
</template>
<style  scoped>
*{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}
.home{
    width: 100vw;
    overflow: hidden;
}
.main-view1{
    position: relative;
    height: 120vh;
    background-color: rgb(24, 82, 6);
    width: 100vw;
    margin-top: 90px;
    background: url(../assets/images/main1.jpg);
    background-size: 100% 100%;
}
.home-view2{
    position: relative;
    height: 100vh;
    background-color: rgb(24, 82, 6);
    width: 100vw;
    background: url(../assets/images/main2.jpg);
    background-size: 100% 100%;
}
.onions{
       position: absolute;
    height: 30vh;
    margin-top: 70vh;
    width: 100vw;
    background: url(../assets/images/onions.png);
    background-size: 100% 100%;
 
}
.pear{
       position: absolute;
    height: 90vh;
    margin-top: 3vh;
    width: 100vw;
     left: 0vw;
    background: url(../assets/images/pear.png);
    background-size: 100% 100%;
    z-index: 10;
    transform: rotate(8deg);
}
.lemon{
       position: absolute;
    height: 65vh;
    margin-top: 22vh;
    width: 95%;
    left: 8vw;
    background: url(../assets/images/lemon.png);
    background-size: 100% 100%;
    z-index: 5;
 
}
.nuts{
  position: absolute;
     margin-top: 33vh;
    height: 50vh;
    width: 90vw;
     left:3vw;
    background: url(../assets/images/nuts.png);
    background-size: 100% 100%;
  }

.carton{
  position: relative;
    height: 35vh;
    width: 100vw;
    background: url(../assets/images/carton.jpg);
    background-size: 100% 100%;
  }
.home-view3{
    position: relative;
    height: 150vh;
    background-color: rgb(24, 82, 6);
    width: 100vw;
    background: url(../assets/images/main3.jpg);
    background-size: 100% 100%;
    z-index: 5;
}
.home-view4{
    position: relative;
    height: 150vh;
    background-color: rgb(24, 82, 6);
    width: 100vw;
    background: url(../assets/images/main4.jpg);
    background-size: 100% 100%;
    z-index: 5;
}
.home-view5{
    position: relative;
    height: 50vh;
    width: 100vw;
    background-size: 100% 100%;
    z-index: 5;
    border-right: 1px solid black;
    border-bottom: 2px solid black;
}
.view5-container{
    height: 100%;
    width: 70%;
    margin: 0 auto;
    color: #444;
}
.fivea{
    width: 100%;
    height: 70%;
    display: flex;
    justify-content: space-between;
 }
.left-side5{
 width: 40%;
    height: 100%;
   
}
.carousel{
    width: 60%;
    height: 100%;
    display: flex;
    justify-content: space-between;
    /* background-color: rgb(28, 37, 160); */
 
}
.logo-div{
    height: 15%;
    width: 80%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    margin-top: 4%;
}
.bar{
    position: relative;
    border:1px solid rgb(74, 3, 88);
    width: 50%;
    margin-top: 0;
}
.view5-text{
    font-size: 25px;
    text-align: left;
    font-weight: 600;
}
.logo1{
    position: relative;
    width: 15%;
    height: 100%;
    background: url(../assets/images/eater.svg);
    background-size: 100% 100%;
}
.logo2{
    position: absolute;
    width: 5%;
    margin-left: 9%;
    height: 15%;
    background: url(../assets/images/today.svg);
    background-size: 100% 100%;
}
.logo3{
    position: absolute;
    width: 10%;
    margin-left:15%;
    height: 15%;
    background: url(../assets/images/shape.svg);
    background-size: 100% 100%;
 }
.logo4{
    position: absolute;
    width: 15%;
    margin-left:26%;
    height: 15%;
    background: url(../assets/images/fast-company.svg);
    background-size: 100% 100%;
 }
</style>