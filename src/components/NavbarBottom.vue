<template>
 <!-- Remove the container if you want to extend the Footer to full width. -->
<div class="container mt-5">
  <!-- Footer -->
  <footer
          class="text-center text-lg-start text-white">
    <!-- Grid container -->
    <div class="container p-4 pb-0">
      <!-- Section: Links -->
      <section class="">
        <!--Grid row-->
        <div class="row">
          <!--Grid column LOGO-->
          <div class="col-lg-4 col-md-6 mb-4 mb-md-0">
          <img src="../assets/logomfu.png" alt="" width="150">
          </div>

          <!--Grid column-->
          <div class="col-lg-2 col-md-6 mb-4 mb-md-0">
           <p>ศูนย์ประสานงานโครงการอนุรักษ์พันธุกรรมพืชอันเนื่องมาจากพระราชดำริ สมเด็จพระเทพรัตนสุดาฯ สยามบรมราชกุมารี สนองพระราชดำริ โดยมหาวิทยาลัยแม่ฟ้าหลวง</p>
            <ul class="list-unstyled mb-0">
              <li>
              <p>333 ม.1 ต.ท่าสุด อ.เมือง จังหวัดเชียงราย 57100</p>
              <p>โทรศัพท์: 0 5391 7742</p>
              <p>Email : rspg.botanical@mfu.ac.th</p>
              </li>
              <li>
                <a href="https://www.facebook.com/rspg.mfu/" class="text-white">Facebook : อพ.สธ. - มหาวิทยาลัยแม่ฟ้าหลวง</a>
            </li>
              <li>
                <a href="http://rspg.mfu.ac.th" class="text-white">Website : http://rspg.mfu.ac.th</a>
              </li>
            </ul>
          </div>


          <!--Grid column-->
          <div class="col-lg-2 col-md-6 mb-4 mb-md-0">
           <p>สืบค้นข้อมูลที่เกี่ยวข้อง</p>
            <ul class="list-unstyled mb-0">
              <li>
                <router-link to="/">สืบค้นข้อมูลพืชภูมิปัญญา</router-link>
            </li>
              <li>
                <router-link to="/">สืบค้นข้อมูลสัตว์</router-link>
              </li>
              <li>
                <router-link to="/">สืบค้นข้อมูลปราชญ์ท้องถิ่น</router-link>
              </li>
            </ul>
          </div>

          <!--Grid column-->
          <div class="col-lg-2 col-md-6 mb-4 mb-md-0">
           <p>เว็บไซต์ที่เกี่ยวข้อง</p>
            <ul class="list-unstyled mb-0">
              <li>
               <a href="https://www.mfu.ac.th/home.html">มหาวิทยาลัยแม่ฟ้าหลวง.</a>
            </li>
              <li>
                <router-link to="/">ศูนย์ประสานงาน อพ.สธ.-มฟล</router-link>
              </li>
           
            </ul>
          </div>

        </div>
        <!--Grid row-->
      </section>

    </div>
  </footer>
  <!-- Footer -->
</div>
<!-- End of .container -->
</template>

<script>
    export default {
        name: 'NavbarBot'
    }
</script>

<style scoped>

div .container{
    max-width: 200%;
    margin: 0;
    padding: 0;
}

ul li p{
    margin: 0;
}
p{
    font-size: 12px;
}
a{
    font-size: 12px;
}

footer{
    background-image: url('../assets/imgfooter.png');
}

</style>