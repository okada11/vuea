<template>
  <footer id="footer">
    <div class="footer-wrap">
      <h1 class="header-logo">estra inc.</h1>
      <nav class="header-nav">
        <ul>
          <li><a href="#">home</a></li>
          <li><a href="#">about</a></li>
          <li><a href="#">service</a></li>
          <li><a href="#">works</a></li>
          <li><a href="#">price</a></li>
          <li><a href="#">contact</a></li>
        </ul>
      </nav>
    </div>
    <small>Copyright 2019 estra inc.All Rights Reserved.</small>
  </footer>            
</template>

<style scoped>
#footer {
  height: 120px;
  text-align: center;
  background-color: black;
}

.footer-wrap {
  justify-content: space-between;
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.header-logo {
  font-size: 20px;
  font-weight: bold;
  color: #f2f2f2;
  line-height: 70px;
}

.header-nav ul {
  display: flex;
}

.header-nav li {
  display: inline-block;
  margin-right: 35px;
  font-size: 16px;
}

.header-nav a {
  color: #f2f2f2;
}

small {
  text-align: center;
  color: white;
}
@media screen and  (max-width: 768px) {
 .header-nav {
    display: none;
  }

  small {
    display: none;
    
  }

  .footer-wrap {
    display: inline-block;
    text-align: center;
    justify-content: center;
    align-items: center;
 }
 #footer {
   
   text-align: center;
 }
}
</style>