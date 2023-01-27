<template>
  <!-- header -->
  <header id="site-header" class="fixed-top">
    <div class="container">
      <nav class="navbar navbar-expand-lg stroke">
        <!-- <a class="navbar-brand" href="index.html">
          <span class="fa fa-laptop"></span> Divya
        </a> -->
        <a class="navbar-brand" href="#index.html">
          <img
            src="../assets/images/Signaturelogo.png"
            alt="Divya"
            title="Divya"
            style="height: 100px"
          />
        </a>
        <button
          class="navbar-toggler collapsed bg-gradient"
          type="button"
          data-toggle="collapse"
          data-target="#navbarTogglerDemo02"
          aria-controls="navbarTogglerDemo02"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon fa icon-expand fa-bars"></span>
          <span class="navbar-toggler-icon fa icon-close fa-times"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
              <a class="nav-link" href="index.html"
                >Home <span class="sr-only">(current)</span></a
              >
            </li>
            <li class="nav-item @@about__active">
              <a class="nav-link" href="about.html">About</a>
            </li>
            <li class="nav-item @@contact__active">
              <a class="nav-link" href="contact.html">Contact</a>
            </li>
          </ul>
        </div>
        <!-- toggle switch for light and dark theme -->
        <div class="mobile-position">
          <nav class="navigation">
            <div class="theme-switch-wrapper">
              <label class="theme-switch" for="checkbox">
                <input type="checkbox" id="checkbox" />
                <div class="mode-container">
                  <i class="gg-sun"></i>
                  <i class="gg-moon"></i>
                </div>
              </label>
            </div>
          </nav>
        </div>
        <!-- //toggle switch for light and dark theme -->
      </nav>
    </div>
  </header>
  <!-- //header -->
</template>
<script>
// import "../assets/js/theme-change.js";
const toggleSwitch = document.querySelector(".theme-switch-wrapper");
// const currentTheme = localStorage.getItem("theme");

// if (currentTheme) {
//   document.documentElement.setAttribute("data-theme", currentTheme);

//   if (currentTheme === "dark") {
//     toggleSwitch.checked = true;
//   }
// }

// function switchTheme(e) {
//   if (e.target.checked) {
//     document.documentElement.setAttribute("data-theme", "dark");
//     localStorage.setItem("theme", "dark");
//   } else {
//     document.documentElement.setAttribute("data-theme", "light");
//     localStorage.setItem("theme", "light");
//   }
// }

console.log("Checkbox..", toggleSwitch);
// toggleSwitch.addEventListener("change", switchTheme, false);

export default {};
</script>
