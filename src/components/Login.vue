<template>
  <body>
    <div class="container"></div>
    <div class="box">
      <form action="post">
        <h3 class="masuk1">Masuk</h3>
        <input class="input-email" type="text" placeholder="Email" required>
        <br>
        <input class= "input-password" type="password" placeholder="Password" required>
        <br>
        <a href="" class="lupa">Lupa Password?</a>
        <br>
        <a href="Product.vue"><button name="submit">Masuk</button></a>
        <hr class="garis">
        <h3 class="login-text">Belum punya akun ? <a href="Register.vue">Daftar Sekarang</a></h3>
      </form>
    </div>
  </body>
</template>

<style>
    body {
  margin: 0;
  padding: 0;
}

.container {
  width: 100%;
}


.box {
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

.masuk1 {
position: absolute;
width: 87px;
height: 25px;
left: 360px;
top: 160px;
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

.input-email {
  margin-bottom: 20px;
}

button >  {
margin-top: 10px;
width: 500px;
height: 59px;
left: 507px;
top: 467px;
color: white;
background: #EB3F36;
box-shadow: 0px 7px 6px rgba(0, 0, 0, 0.17);
border-radius: 7px;
text-decoration: none;
}

button a {
color: white;
text-decoration: none;

}

.submit > a {
  text-decoration: none;
}


.garis {
  margin-inline: auto;
  width: 420px;
  height: 1px;
  color: #C2C2C2;
}


.login-text {
    color: #7C7C7C;
    font-size: 16px;
    font-weight: 400;
}
.lupa {
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