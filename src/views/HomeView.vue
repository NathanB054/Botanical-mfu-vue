<template>
  <div class="home">
    <h1>สืบค้นข้อมูลพืชภูมิปัญญา</h1>
    <input type="text" class="searchTerm" name="" id="" placeholder="THAI NAME, LOCAL NAME, SCIENCIFIC NAME,FAMILY,COMMON NAME   (เติม '/'หน้าตัวอักษรเพื่อค้นหาผลลัพธ์ทั้งหมด)">
    <button type="submit">Search</button>
    <div class="subtxt" >
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <span id="index_1">ฐานข้อมูลทรัพยากร สวนพฤกษศาสตร์ - มหาวิทยาลัยแม่ฟ้าหลวง
          ได้สํารวจและเก็บรวบรวมข้อมูล พืชภูมิปัญญา </span><br><span
          id="index_2">และข้อมูลนกซึ่งแบ่งเป็นสองฐานข้อมูล ได้แก่พืชภูมิปัญญาบนดอยแม่สลอง
          อําเภอแม่ฟ้าหลวง จังหวัดเชียงราย</span> <br> 
          <span id="index_3">และข้อมูลนกบนพื้นที่ปกป้องทรัพยากรของมหาวิทยาลัยแม่ฟ้าหลวง จังหวัดเชียงราย</span>
      </div>

      <div class="image-flex">
      <div class="hover02 column">
        <router-link class="link"to="/">
          <figure><img src="../assets/pla.jpg" class="image-orgz "></figure>
          <div class="text3">สืบค้นข้อมูลพืชภูมิปัญญา</div>
        </router-link>
      </div>
      <div class="hover02 column">
        <a href="/animal" style="text-decoration: none;">
          <figure><img src="../assets/ani.jpg" class="image-orgz "></figure>
          <div class="text3">สืบค้นข้อมูลสัตว์</div>
        </a>
      </div>
      <div class="hover02 column">
        <a href="/people" style="text-decoration: none;">
          <figure><img src="../assets/peo.jpg" class="image-orgz "></figure>
          <div class="text3">สืบค้นข้อมูลปราชญ์ท้องถิ่น</div>
        </a>
      </div>
    </div>

  </div>


    
</template>

<script>

export default {
  name: 'HomeView',
  components: {
    
  }
}
</script>


<style scoped>
.home{
  text-align: center;
}
.searchTerm {
    width: 50%;
    border: 0px solid #00B4CC;
    border-right: none;
    padding: 5px;
    border-radius: 30px 30px;
    outline: none;
    color: #747a77;
    background-color: #cc9bcb71;
}
.subtxt{
    display: inline-block;
    align-content: center;
    font-size: 18px;
    font-family: 'Kanit', sans-serif;
    color: #390F65;
    text-align: justify;
    padding: 20px 0px;
    width: 50%;
    word-wrap: break-word;
}
.image-flex {
    display: flex;
    justify-content: center;
}
.column {
    float: left;
    /* width: 30%; */
    padding: 5px;
}
.hover02 figure img {
    width: 15em;
    height: auto;
    -webkit-transition: .3s ease-in-out;
    transition: .3s ease-in-out;
}
.image-orgz {
    border-radius: 30%;
    height: 10em;
    width: 15em;
    margin: 30px;
}
img, svg {
    vertical-align: middle;
}


</style>