<!DOCTYPE html>
<html lang="ua">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Сайт Шльопи</title>
    <link rel="icon"  href="/firsteproject/img/shlepa.jpeg">
    <link rel="stylesheet" href="/firsteproject/projectadriankars.css" />
  </head>
  <body>
    <header>
      <div class="page_eng">
        <a href="#">EN</a>
      </div>  
      
      <img class="img" src="/firsteproject/img/shlepa.jpeg" alt="shlepa" />
      <h2 class="nick" >кіт-шльопа</h2>
    </header>

    <main>
      <h1 class="fullnick" >Україньский Кіт-Шльопа</h1>
      <p class="info" >Пожирач Рибок Та Мишей / Господар Життя</p>
      <ul class="links">
        <li><a target="_blank" href="#"><img src="/firsteproject/img/1298747_instagram_brand_logo_social media_icon.png" style="width: 20px;" alt="inst"></a></li>
        <li><a target="_blank" href="##"><img style="width: 20px;" src="/firsteproject/img/5296499_fb_facebook_facebook logo_icon.png" alt="facebook"></a></li>
      </ul>
      <div class="email">
      <a href="mailto:taras.levchuk221@gmail.com">email</a>  
      </div> 

      <a href="#" class="shop">
        
        Shop
        
      </a>  
      

    </main>

    <footer>
      <div class="by">Зроблено мною</div> 
    </footer>
  </body>
</html>


<style>
body,
h1,
h2,
p,
ul {
  margin: 0;
}

.img {
  border-radius: 50%;
  width: 200px;
  height: 200px;
  object-fit: cover;
  display: block;
  margin: 0 auto;
  border: 2px solid lightskyblue;
  
}
body {
  width: 500px;
  margin-left: auto;
  margin-right: auto;
  background-color: black;
  height: 100vh;
  padding: 15px;
  color: white;
}

html {
  background-color: white;
}

.nick,
.fullnick,
.info,
.email,
.by {
  text-align: center;
  color: white;
}

ul {
  list-style: none;
}

.links {
  display: flex;
  padding: 0;
  justify-content: center;
}

header,
main,
footer,
.nick,
.fullnick,
.info,
.links {
  margin-bottom: 15px;
}

footer {
  margin-top: 44%;
}

a {
  color: lightskyblue;
  text-decoration: none;
}

a:hover,
a:focus
{
  color: aqua;
  transition: 0.3s;
  opacity: 80%;
  
}
li {
  margin-left: 10px;
}

.by {
  font-size: 13px;
  letter-spacing: 1px;

  
}

.shop{
    display: flex;
    justify-content: center;
    width: 100%;
    height: 50px;
    background-color: purple;
    align-items: center;
    margin-top: 15px;
    padding-bottom:1px;
    border-radius: 30px;
    font-size: 19px;
    font-weight: bold;
    border: 1px solid;
}

.shop:hover{
    
}



.page_eng {
    display: block;
    width: fit-content;
    padding-left: 95%;
  }

  .by:focus-visible{
    transition: 0.3s;
    text-align: left;
  }
  <style/>
