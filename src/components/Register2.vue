<template>
    <div class="container2"></div>
    <div class="box2">
      <form action="post3">
        <p class="header-text-register2"><i class="fas fa-arrow-left"></i>&nbspKembali</p>
        <input class= "HP" type="text" placeholder="Nomor Telepon">
        <input class="password" type="password" placeholder="Password">
        <br>
        <input class= "password2" type="password" placeholder="Konfirmasi Password">
        <br>
        <!-- <a href="" class="lupa2">Lupa Password?</a> -->
        <br>
        <a href="Product.vue"><button>Selanjutnya</button></a>
        <hr class="garis2">
        <h3 class="login-text2">Sudah punya akun ? <a href="Login.vue">Masuk</a></h3>
      </form>
    </div>
</template>

<style>
  body {
  margin: 0;
  padding: 0;
}

.container2 {
  width: 100%;
}


.box2 {
  width: 568px;
  height: 509px;
  background: #FFFFFF;
  color : white ;
  display: flex;
  justify-content: center;
  flex-direction: column;
  text-align: center;
  margin: 100px auto auto auto ;
  box-shadow: 0px 1px 12px rgba(0, 0, 0, 0.25);
}

.header-text-register2 {
position: absolute;
width: 87px;
height: 25px;
left: 360px;
top: 1360px;

display: flex;
flex-direction: row;
font-family: 'Gotham';
font-style: normal;
font-weight: 700;
font-size: 26px;
line-height: 25px;
/* identical to box height */

letter-spacing: 0.04em;

color: #730C07;
}

input {
width: 500px;
height: 40px;
background: #FFFFFF;
box-shadow: 0px 1px 4px rgba(0, 0, 0, 0.25);
border-radius: 7px;
margin: 10px;
}

.password {
  margin-top: 20px;
  margin-bottom: 20px;
}

button > a {
margin-top: 10px;
width: 500px;
height: 59px;
left: 507px;
top: 467px;
color: white;
background: #EB3F36;
box-shadow: 0px 7px 6px rgba(0, 0, 0, 0.17);
border-radius: 7px;
}

.garis2 {
    width: 300px;
}

.login-text2 {
    color: #7C7C7C;
    font-size: 16px;
    font-weight: 400;
}
.lupa2 {
    color:#730C07 ;
    display: flex;
    justify-content: flex-end;
    margin-right: 25px;
    font-size: 12px;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif ;
    font-weight: 400;
}

h3 > a {
    color: #730C07;
    text-decoration: none;
    font-size: 16px;
    font-weight: 400;
}
</style>



