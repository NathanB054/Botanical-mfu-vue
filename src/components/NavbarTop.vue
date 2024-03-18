<template lang="">
<nav>
<div class='navbarTop'>
<!-- Logo clickable -->
  <div>
  <router-link to="/"><img width="100px" height="auto" src="../assets/logomfu.png"></router-link>
</div> 
<!-- =============== -->
  <div class='txt'>
  <p>โครงการอนุรักษ์พันธุกรรมพืชอันเนื่องมาจากพระราชดำริ สมเด็จพระเทพรัตนสุดา ฯ</p>
  <p>สยามบรมราชกุมารี สนองพระราชดำริ โดยมหาวิทยาลัยแม่ฟ้าหลวง</p>
  </div>

  <!-- Menu -->
      <ul class='menu'>
       <li><router-link class="link"to="/">หน้าหลัก </router-link></li>
       <li><router-link class="link" to="/contact">ติดต่อเรา </router-link></li>
       <li><router-link class="link" to="/staff">เจ้าหน้าที่  </router-link></li>
      </ul>
</div>
</nav>

<div id="my_div">
    <img src="../assets/imgunder.png" id="mainimg" class="responsive">
    <p id="textimgunder" style="font-size:2.2vw; " >ฐานข้อมูลทรัพยากร อพ.สธ. - มหาวิทยาลัยแม่ฟ้าหลวง</p>
 </div>
</template>
<script>
export default {
  name: 'NavbarTop'
}
</script>
<style scoped>

/* Navbar */
nav{
  background: #f4cff4;
  color: #673363;
}
.navbarTop{
  display: flex;
}
/* Navbar */


/* Text navbar */
.txt{
 margin-top: 1%;
}
.txt p {
  margin: 0.5em 0 0 0.9em;
}
/* Text navbar */

/* Menu navbar */
.menu{
  margin: 2% 1% 0 50%;
  display: flex;
  list-style-type: none;
}
.menu li{
  margin: 0 0.5em 0 0.5em;
  font-size: 1.2rem;
  font-family: 'Kanit', sans-serif;
}
.link{
  text-decoration: none;
}
/* Menu navbar */




#my_div {
    height: 8em;
    width: 100%;
    position: relative;
    overflow: hidden;
  }
  
  #my_div img {
    max-width: 100%;
  }
  
  #my_div p {
    position: absolute;
    color: white;
    top: 20%;
    text-align: center;
    font-weight: bold;
    width: 100%;
    margin-top: 0px;
  }
  #textimgunder {
    font-size: 2.6em;
    position: absolute;

  }

</style>
