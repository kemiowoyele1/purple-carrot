<template>
<div>
        <div class="nav-bar">
      
     <div class="nav-container">
        <div class="nav-logo"></div>
        <div  id="mobileMenu">
            <ul class="nav-links">
                <a href="#"><li>WHY PLANTS</li></a>
                <a href="#"><li>MENUS</li></a>
                <a href="#"><li>PRICING</li></a>
                <a href="#"><li>GIFTS</li></a>
                <a href="#"><li>CONTACT</li></a>
            </ul>
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
*{
    padding: 0;
    margin: 0;
}
.nav-bar{
    border-bottom: 0.5px dotted silver;
    height: fit-content;
    width: 100%;
    display: flex;
    position: fixed;
    height: 90px;
    background-color: white;
    z-index: 100;
}

.nav-container{
    width: 80vw;
    margin: auto;
    display: flex;
  justify-content: space-between;
   
}
.nav-logo{
     background: url(../assets/images/purple.PNG);
    height: 90px;
    width:25%;
    background-size: 100% 100%;
      border-bottom: 0.5px dotted silver;
  
}
#mobileMenu{
    position: absolute;
    left: 60vw;
    width: 30%;
    height: 100%;
 
   }
.nav-links{
    display: flex;
    justify-content: space-between;
    width: 100%;
    height: 100%;
  }
.nav-links a{
    text-decoration: none;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #444;
    font-size: 16px;
    line-height: 26px;
    font-family: OpenSans;
    font-stretch: 100%;
 }
li{
    list-style: none;
}






</style>