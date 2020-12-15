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
      <small>Copyright 2019 estra inc.All Rights Reserved.</small>
    </div>
  </footer>            
</template>

<style scoped>
#footer {
  height: 80px;
  text-align: center;
  line-height: 80px;
  background-color: black;
}

.footer-wrap {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.header-logo {
  font-size: 20px;
  font-weight: bold;
  margin-left: 35px;
  color: #f2f2f2;
  line-height: 70px;
}

.header-nav ul {
  display: flex;
}

.header-nav li {
  margin-right: 35px;
  font-size: 16px;
}

.header-nav a {
  color: #f2f2f2;
}
@media screen and  (max-width: 768px) {
  .header-nav {
    display: none;
  }

  small {
    display: none;
  }

  .footer-wrap {
    display: flex;
    justify-content: center;
    align-items: center;
  }
}
</style>