import NavbarTop from '@/components/NavbarTop'

<template>
    <div class="contact">
        <h1 style="font-size: 4em; color: #b22160; margin-top: 35px;">ติดต่อเรา</h1>
    <div id="form-main">
        <div id="form-div">
            <form class="form" id="form1">
                <!-- Your form fields -->
                <p class="name">
                    <input name="name" type="text" class="feedback-input" placeholder="ชื่อ-สกุล" id="name" />
                </p>
                <p class="email">
                    <input name="email" type="text" class="feedback-input" id="email" placeholder="อีเมล" />
                </p>
                <p class="text">
                    <textarea name="text" class="feedback-input" id="comment" placeholder="รายละเอียด"></textarea>
                </p>
                <div class="submit">
                    <input type="button" value="ส่ง" id="button-blue" onclick="validateAndSubmit()" />
                    <div class="ease"></div>
                </div>
            </form>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  
  export default {
    name: 'contact',
    components: {
      
    }
  }
  </script>

<style scoped>
.contact{
  text-align: center;
  height: 51vh;
}
#form-main {
    float: left;
    padding-top: 0px;
}
#form-div {
    padding-left: 20%;
    padding-right: 20%;
    padding-top: 35px;
    padding-bottom: 50px;
    width: 75em;
    height: 30em;
    float: left;
    left: 50%;
    position: absolute;
    margin-top: 1px;
    margin-left: -36em;
}
p {
    display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
}
#name {
    margin-top: -1em;
    background-size: 30px 30px;
    background-position: 11px 8px;
    background-repeat: no-repeat;
    background-color: #efdcef;
    border-radius: 1em;
    font-family: 'Kanit', sans-serif;
}

input[type="text" i] {
    padding-block: 1px;
    padding-inline: 2px;
}
.feedback-input {
    font-family: 'Kanit', sans-serif;
    font-weight: 500;
    font-size: 18px;
    border-radius: 0;
    color: #390f65;
    line-height: 22px;
    background-color: #fbfbfb;
    padding: 13px 13px 13px 54px;
    margin-bottom: 10px;
    width: 100%;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    -ms-box-sizing: border-box;
    box-sizing: border-box;
    border: 3px solid rgba(0, 0, 0, 0);
}
#email {
    background-size: 30px 30px;
    background-position: 11px 8px;
    background-repeat: no-repeat;
    background-color: #efdcef;
    border-radius: 1em;
    font-family: 'Kanit', sans-serif;
}
#comment {
    background-size: 30px 30px;
    background-position: 11px 8px;
    background-repeat: no-repeat;
    background-color: #efdcef;
    border-radius: 1em;
    font-family: 'Kanit', sans-serif;
}
input::placeholder { 
  padding: 55px; 
} 

</style>
  