<template>
  <div class="page">
  <div id="app">
  
    <header class="navigation">

      <nav class="nav">
          <div class="nav-logo">
              <a href="">
                  <svg id="logo" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 197.86 228.47"><defs>
                     
                  </defs>

                      <path class="cls-1" d="M150,53.31l88.93,51.35V207.34L150,258.69,61.07,207.34V104.66L150,53.31m0-11.55L51.07,
                                                           98.88V213.12L150,270.24l98.93-57.12V98.88L150,41.76Z"
                            transform="translate(-51.07 -41.76)"/>
                      <g id="khaly">
                          <polygon class="cls-2" points="65.51 66.88 81.11 66.88 81.11 114.24 81.11 167.07 65.51 167.07 65.51 66.88"/>
                          <polygon class="cls-2" points="128.13 66.88 81.11 116.98 81.11 127.9 92.71 117.93 132.42 167.07
     150.93 167.07 103.76 109.47 147.47 66.88 128.13 66.88"/>
                      </g></svg>
              </a>
          </div>
          <div class="button">
            <div class="hamburger">
                <div class="open">

                <ol>
                    <li data-aos="slide-down" data-aos-duration="200"><a href="#apropos">A propos</a></li>
                    <li data-aos="slide-down" data-aos-duration="400"><a href="#work">Work</a></li>
                    <li data-aos="slide-down" data-aos-duration="800"><a href="mailto:khalysileye@gmail.com">Contact</a></li>
                </ol>
                <div  data-aos="slide-down" data-aos-duration="1000">
                    <a class="cv-button" href="http://khalysileye.com/Cv.pdf" target="_blank">CV</a>
                </div>
                </div>
            </div>
          </div>

          <div class="nav-item">
              <ol>
                  <li data-aos="slide-down" data-aos-duration="200"><a href="#apropos">A propos</a></li>
                  <li data-aos="slide-down" data-aos-duration="400"><a href="#work">Work</a></li>
                  <li data-aos="slide-down" data-aos-duration="800"><a href="mailto:khalysileye@gmail.com">Contact</a></li>
              </ol>
              <div  data-aos="slide-down" data-aos-duration="1000">
                  <a class="cv-button" href="">CV</a>
              </div>
          </div>
      </nav>
  </header>
  <div aria-orientation="left" class="reseaux-sociaux">
    <ul class="mes-comptes">
        <li><a href="https://github.com/ksthiam/" aria-label="github">
            <svg xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="github">
                <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22">

                </path>
            </svg>
            </a>
        </li>
        <li><a href="" aria-label="twitter">
            <svg xmlns="http://www.w3.org/2000/svg" role="img" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="twitter">
                <path d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z">

                </path>
            </svg>

        </a></li>
        <li>
            <a href="" aria-label="linkdin">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="linkedin"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path>
                    <rect x="2" y="9" width="4" height="12"></rect>
                    <circle cx="4" cy="4" r="2"></circle>
                </svg>
            </a>
        </li>
    </ul>

</div>

<div class="contact-email" aria-orientation="right" >
    <div class="email">
      <a href="mailto:khalysileye@gmail.com">khalysileye@gmail.com</a>

    </div>
</div>
</div>
    <router-view/>
    <footer>
      <div class="footer">
          <div class="footer-reseaux">
              <ul class="mes-comptes">
                  <li><a href="https://github.com/ksthiam/" aria-label="github">
                      <svg xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="github">
                          <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22">

                          </path>
                      </svg>
                  </a>
                  </li>
                  <li><a href="" aria-label="twitter">
                      <svg xmlns="http://www.w3.org/2000/svg" role="img" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="twitter">
                          <path d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z">

                          </path>
                      </svg>

                  </a></li>
                  <li>
                      <a href="" aria-label="linkdin">
                          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="linkedin"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path>
                              <rect x="2" y="9" width="4" height="12"></rect>
                              <circle cx="4" cy="4" r="2"></circle>
                          </svg>
                      </a>
                  </li>
              </ul>

          </div>
      Khaly Thiam - 2021
      </div>

  </footer>
    
  </div>
</template>

<script>
  
export default {
  name: 'App'

}

</script>

<style>
 
 .cls-1,.cls-2 {
  fill:#64ffda;

    }.cls-2{
      stroke:#64ffda;
      stroke-miterlimit:10;
      stroke-width:0.25px;

     }

     @import url('http://fonts.cdnfonts.com/css/sf-mono');

body {
    margin: 0px;
    width: 100%;
    min-height: 100%;
    overflow-x: hidden;
    background-color: #0A192F;
    color: #8892b0;;
    font-family: "Calibre","San Francisco","SF Pro Text",-apple-system,system-ui,sans-serif;;
    font-size: 20px;
    line-height: 1.3;

}
.page{
    min-height: 100vh;
    display: grid;
    grid-template-rows: 1fr auto;
    grid-template-columns: 100%;
}
.navigation{
    display: flex;
    justify-content: space-between;
    -webkit-box-align: center;
    align-items: center;
    position: fixed;
    top: 0px;
    z-index: 11;
    padding: 0px 50px;
    width: 100%;
    height: 100px;
    background-color: #0A192F;
}
.nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: relative;
    width: 90%;
    counter-reset: item 0;
    z-index: 12;
}
.nav-logo {
    color: #64ffda;
     width: 42px;
     height: 42px;

}
.nav-item{
    display: flex;
    align-items: center;
    font-family: "SF Mono", "Fira Code", "Fira Mono", "Roboto Mono", monospace;
    color: #ccd6f6;

}
.nav-item ol{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0;
    margin: 0;
    list-style: none;
}
.nav-item ol li{
    margin: 0 5px;
    position: relative;
    counter-increment: item 1;
    font-size: 13px;

}
.nav-item ol li a{
    padding: 10px;
    text-decoration: none;
    color: #FFFFFF;
}
.nav-item ol li a:hover{

    color: #64ffda;
}
.nav-item ol li a::before{
    content: "0" counter(item) ".";
    margin-right: 5px;
    text-align: right;
    color: #64ffda;
}
.nav-item .cv-button{
    color: #64ffda;
    background-color: transparent;
    border: 1px solid #64ffda;
    border-radius: 4px;
    padding: 0.75rem 1rem;
    font-family: "SF Mono","Fira Code","Fira Mono","Roboto Mono",monospace;
    line-height: 1;
    text-decoration: none;
    cursor: pointer;
    margin-left: 15px;
    font-size: 13px;
}
.nav-item .cv-button:hover{
    background-color: #133040;

}
.reseaux-sociaux{
    width: 40px;
    position: fixed;
    bottom: 0px;
    left: 40px;
    right: auto;
    z-index: 10;
    color: #ccd6f6;
}
.mes-comptes li a svg{
    width: 20px;
    height: 20px;
    color: #ccd6f6;
}
.mes-comptes {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 0px;
    padding: 0px;
    list-style: none;
}

.mes-comptes li{
    list-style-type: none;
    text-decoration: none;
    padding: 10px;
}
.mes-comptes::after{
    content: "";
    display: block;
    width: 2px;
    height: 90px;
    margin: 0px auto;
    background-color: #ccd6f6;

}
.contact-email{
    width: 40px;
    position: fixed;
    bottom: 0px;
    left: auto;
    right: 40px;
    z-index: 10;
    color: #ccd6f6;
}
.email{
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
}
.email a{
    margin: 20px auto;
    padding: 10px;
    font-family: "SF Mono","Fira Code","Fira Mono","Roboto Mono";
    font-size: 12px;
    letter-spacing: 0.1em;
    -webkit-writing-mode: vertical-rl;
    writing-mode: vertical-rl;
}
.email a {
    color:  #ccd6f6;
}
.email::after{
    content: "";
    display: block;
    width: 1px;
    height: 90px;
    margin: 0px auto;
    background-color: #ccd6f6;
}
main{
    margin: 0px auto;
    width: 100%;
    max-width: 1600px;
    min-height: 100vh;
}
main.page-main{
    padding: 50px 5px;
}
.apropos{
    display: flex;
    flex-direction: column;
    align-items: flex-start;

}
.apropos h1{
    margin: 0px 0px 30px 4px;
    font-size: 16px;
    font-weight: 400;
    font-family: "SF Mono", "Fira Code", "Fira Mono", "Roboto Mono", monospace;
    color: #64ffda;
}
.gros-titre{
    font-size: 60px;
    font-weight: 600;
}
.gros-titre h2{
    margin-top: 0px;
    margin-bottom: 0px;
    color: #ccd6f6;
}
.gros-titre h3{
    margin-top: 0px;
    margin-bottom: 0px;
    color: #8892b0;
}
.apropos p{
    margin: 20px 0px 0px;
    max-width: 500px;
    font-size: 16px;

}
.apropos .email-link{
    color: #64ffda;
    background-color: transparent;
    border: 1px solid #64ffda;
    border-radius: 4px;
    padding: 1.25rem 1.75rem;
    font-size: 14px;
    font-family: "SF Mono", "Fira Code", "Fira Mono", "Roboto Mono", monospace;
    line-height: 1;
    text-decoration: none;
    cursor: pointer;
    margin-top: 50px;
}
section {
    margin: 0px auto;
    padding: 100px 0px;
    max-width: 1000px;
}
.apropos-section{
    max-width: 900px;
    padding-bottom: 0px;

}
.apropos-section h2{
    display: flex;
    align-items: center;
    position: relative;
    margin: 10px 0px 40px;
    width: 100%;
    font-size: 30px;
    white-space: nowrap;
    color: #ccd6f6;
}
.apropos-section h2::before{

    position: relative;
    bottom: -4px;
    counter-increment: section 1;
    content: "0" counter(section) ".";
    margin-right: 10px;
    color: #64ffda;
    font-size: 25px;
    font-family: "SF Mono", "Fira Code", "Fira Mono", "Roboto Mono", monospace;
    font-weight: 400;
}
.work-section h2::before{

    position: relative;
    bottom: -4px;
    counter-increment: section 2;
    content: "0" counter(section) ".";
    margin-right: 10px;
    color: #64ffda;
    font-size: 25px;
    font-family: "SF Mono", "Fira Code", "Fira Mono", "Roboto Mono", monospace;
    font-weight: 400;
}
.apropos-section h2::after{
    content: "";
    display: block;
    position: relative;
    top: 5px;
    width: 300px;
    height: 1px;
    margin-left: 20px;
    background-color: #ccd6f6;
}
.inner{
    display: grid;
    grid-template-columns: 3fr 2fr;
    gap: 50px;
}
.competences{
    display: grid;
    grid-template-columns: repeat(2, minmax(140px, 200px));
    padding: 0px;
    margin: 20px 0px 0px;
    overflow: hidden;
    list-style: none;
    font-size: 14px;
    font-family: "SF Mono", "Fira Code", "Fira Mono", "Roboto Mono", monospace;
}
.lescom ul.competences li::before{
    content: "▹";
    left: 0px;
    color: #64ffda;
    line-height: 12px;

}
.inner p{
    font-size: 16px;
}
.inner p a{
    color: #64ffda;
    text-decoration: none;
}
.profil-apropos .wrapper img{
    box-shadow: 0 10px 30px -15px #64ffda;
    display: block;
    position: relative;
    width: 100%;
    border-radius: 4px;
}
.work{
    display: grid;
    gap: 10px;
    grid-template-columns: repeat(12, 1fr);
    align-items: center;
    padding-bottom: 150px;
}
.work .projet-description{
    box-shadow: 0 10px 30px -15px rgba(2,12,27,0.7);
    position: relative;
    z-index: 2;
    padding: 25px;
    border-radius: 4px;
    background-color: #233554;
    color: #a8b2d1;
    font-size: 14px;
}
.work .project {
    position: relative;
    grid-area: 1 / 1 / -1 / 7;
}
.work:nth-of-type(2n+1) .project{
    grid-column: 7 / -1;
    text-align: right;
}
.work:nth-of-type(2n+1) .project-liste{
    justify-content: flex-end;
}
.work .project-liste{
    display: flex;
    flex-wrap: wrap;
    position: relative;
    z-index: 2;
    margin: 25px 0px 10px;
    padding: 0px;
    list-style: none;
}
.work:nth-of-type(2n+1) .project-liste li{
    margin: 0px 0px 5px 20px;
}
.work .project-liste li{
    margin: 0px 20px 5px 0px;
    color: #ccd6f6;
    font-family: "SF Mono", "Fira Code", "Fira Mono", "Roboto Mono", monospace;
    font-size: 12px;
    white-space: nowrap;
}
.work .projet-image{

    box-shadow: 0 10px 30px -15px rgba(2,12,27,0.7);
    grid-area: 1 / 6 / -1 / -1;
    position: relative;
    z-index: 1;
}
.work:nth-of-type(2n+1) .projet-image{
    grid-column: 1 / 8;
}
 .projet-image a{

    width: 100%;
    background-color: #64ffda;
    border-radius: 4px;
    vertical-align: middle;
}

 .projet-image a::before{

    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    inset: 0px;
    z-index: 3;
    background-color: #0a192f;
    mix-blend-mode: screen;
}

.work .projet-image img{

    border-radius: 4px;
    mix-blend-mode: multiply;
    /*filter: grayscale(100%) contrast(1) brightness(90%);*/
    width: 100%;
}
.work .projet-titre{
    margin: 10px 0px;
    color: #64ffda;
    font-family: "SF Mono", "Fira Code", "Fira Mono", "Roboto Mono", monospace;
    font-size: 12px;
    font-weight: 400;
}
.autres-projets{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0;
}
.autres-projets .autres-projets-grid{
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(400px, 1fr));
    gap: 15px;
    position: relative;
    margin-top: 50px;
}
.projet-inner{
    box-shadow: 0 10px 30px -15px rgba(2,12,27,0.7);;
    display: flex;
    justify-content: space-between;
    flex-direction: column;
    align-items: flex-start;
    position: relative;
    height: 100%;
    padding: 2rem 1.75rem;
    border-radius: 4px;
    background-color: #112240;;

}
.projet-top{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 35px;
}
.project-top .folder svg {
    width: 40px;
    height: 40px;
}
.folder {
    color: #64ffda;
}
.project-links {
    display: flex;
    align-items: center;
    margin-right: -10px;
    color: #a8b2d1;
}
.project-links a {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 5px 7px;
}

.project-links svg {
    width: 22px;
    height: 22px;
    margin-top: -4px;

}
.project-tech-list {
    display: flex;
    align-items: flex-end;
    flex-grow: 1;
    flex-wrap: wrap;
    padding: 0px;
    margin: 20px 0px 0px;
    list-style: none;
}
.footer{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: auto;
    min-height: 70px;
    padding: 15px;
    text-align: center;
    font-family: "SF Mono", "Fira Code", "Fira Mono", "Roboto Mono", monospace;
    color: #a8b2d1;
    font-size: 13px;
}

.open{
    display: none;
}
.mouse_scroll{
    display: none;
}
.footer-reseaux{
    display: none;
}
@media (max-width: 768px){
    .nav-item{
        display: none;
    }
    .active .open{
        display: flex;
        justify-content: center;
        align-items: center;
        position: fixed;
        top: -50px;
        bottom: 0px;
        right: -22px;
        /* padding: 0 0px; */
        width: min(100vw, 415px);
        height: 100vh;
        outline: 0px;
        background-color: #112240;
        /* z-index: 9; */
        transform: translateX(0vw);
        visibility: visible;
    }
    .active .open ol li{
        list-style-type: none;
        padding: 5px;
        font-family: "SF Mono", "Fira Code", "Fira Mono", "Roboto Mono", monospace;
        font-size: 18px;
    }
    .active .open ol li a{
        text-decoration: none;
        color: #64ffda;
    }
    .active .cv-button{
        position: absolute;
        right: -12px;
        top: 63px;
        color: #64ffda;
        background-color: transparent;
        border: 1px solid #64ffda;
        border-radius: 4px;
        font-size: 16px;
        font-family: "SF Mono", "Fira Code", "Fira Mono", "Roboto Mono", monospace;
        line-height: 1;
        text-decoration: none;
        cursor: pointer;
        padding: 18px 50px;
        margin: 10% auto 0px;
        width: max-content;
    }


    .button{
        display: flex;
        justify-content: center;
        align-items: center;
        position: relative;
        z-index: 10;
        margin-right: 30px;
        padding: 15px;
        border: 0px;
        background-color: transparent;
        color: inherit;
        text-transform: none;
        transition-timing-function: linear;
        transition-duration: 0.15s;
        transition-property: opacity, filter;
    }
    .hamburger{

        position: absolute;
        top: 50%;
        right: 0px;
        width: 30px;
        height: 2px;
        border-radius: 4px;
        background-color: #64ffda;
        transition: transform 0.22s cubic-bezier(0.55, 0.055, 0.675, 0.19) 0s;
        transform: rotate(
                0deg
        );
    }
    .hamburger::before{
        content: "";
        display: block;
        position: absolute;
        left: auto;
        right: 0px;
        height: 2px;
        border-radius: 4px;
        background-color: #64ffda;
        transition-timing-function: ease;
        transition-duration: 0.15s;
        transition-property: transform;

    }
    .hamburger::before{
        width: 120%;
        top: -10px;
        opacity: 1;
    }
    .hamburger::after{
        width: 80%;
        bottom: -10px;
        transform: rotate(0deg);

    }
    .hamburger::after{
        content: "";
        display: block;
        position: absolute;
        left: auto;
        right: 0px;
        height: 2px;
        border-radius: 4px;
        background-color: #64ffda;
        transition-timing-function: ease;
        transition-duration: 0.15s;
        transition-property: transform;

    }
    .hamburger.active{
        background-color: transparent;
    }
    .hamburger.active::after{
        transform: translateY(0px) rotateZ(45deg);
        width: 37px;
        top: -10px;

    }
    .hamburger.active::before{
        transform: translateY(0px) rotateZ(-45deg);
        width: 120%;
        z-index: 1;

    }
    .reseaux-sociaux, .contact-email{
        display: none;
    }
    main.page-main {
        width: 80%;
        padding: 100px 5px;
    }
    .gros-titre{
        font-size: 16px;
    }
    .inner{
        display: block;
    }
    .lescom{
        padding-bottom: 25px;
    }
    .work{
        display: block;
    }
    .work:nth-of-type(2n+1) .project {

        text-align: start;
    }
    .mouse_scroll {
        display: block;
        margin: 0 auto;
        width: 24px;
        height: 100px;
        margin-top: 5rem;
        color: #24D69F;
    }


    .m_scroll_arrows
    {
        display: block;
        width: 5px;
        height: 5px;
        -webkit-transform: rotate(45deg); /* Chrome, Safari, Opera */
        transform: rotate(45deg);

        border-right: 4px solid #24D69F;
        border-bottom: 4px solid #24D69F;
        margin: 0 0 3px 4px;

        width: 16px;
        height: 16px;
    }


    .unu
    {
        margin-top: 1px;
    }

    .unu, .doi, .trei
    {
        -webkit-animation: mouse-scroll 1s infinite;
        -moz-animation: mouse-scroll 1s infinite;
        animation: mouse-scroll 1s infinite;

    }

    .unu
    {
        -webkit-animation-delay: .1s;
        -moz-animation-delay: .1s;
        -webkit-animation-direction: alternate;

        animation-direction: alternate;
    }

    .doi
    {
        -webkit-animation-delay: .2s;
        -moz-animation-delay: .2s;
        -webkit-animation-direction: alternate;

        animation-delay: .2s;
        animation-direction: alternate;

        margin-top: -6px;
    }

    .trei
    {
        -webkit-animation-delay: .3s;
        -moz-animation-delay: .3s;
        -webkit-animation-direction: alternate;

        animation-delay: .3s;
        animation-direction: alternate;


        margin-top: -6px;
    }

    .mouse {
        height: 42px;
        width: 24px;
        border-radius: 14px;
        transform: none;
        border: 2px solid #24D69F;
        top: 170px;
    }

    .wheel {
        height: 5px;
        width: 2px;
        display: block;
        margin: 5px auto;
        background: #24D69F;
        position: relative;

        height: 4px;
        width: 4px;
        border: 2px solid #24D69F;
        -webkit-border-radius: 8px;
        border-radius: 8px;
    }
    .wheel {
        -webkit-animation: mouse-wheel 0.6s linear infinite;
        -moz-animation: mouse-wheel 0.6s linear infinite;
        animation: mouse-wheel 0.6s linear infinite;
    }

    @-webkit-keyframes mouse-wheel{
        0% {
            opacity: 1;
            -webkit-transform: translateY(0);
            -ms-transform: translateY(0);
            transform: translateY(0);
        }

        100% {
            opacity: 0;
            -webkit-transform: translateY(6px);
            -ms-transform: translateY(6px);
            transform: translateY(6px);
        }
    }
    @-moz-keyframes mouse-wheel {
        0% { top: 1px; }
        25% { top: 2px; }
        50% { top: 3px;}
        75% { top: 2px;}
        100% { top: 1px;}
    }
    @-o-keyframes mouse-wheel {

        0% { top: 1px; }
        25% { top: 2px; }
        50% { top: 3px;}
        75% { top: 2px;}
        100% { top: 1px;}
    }
    @keyframes mouse-wheel {

        0% { top: 1px; }
        25% { top: 2px; }
        50% { top: 3px;}
        75% { top: 2px;}
        100% { top: 1px;}
    }

    @-webkit-keyframes mouse-scroll {

        0%   { opacity: 0;}
        50%  { opacity: .5;}
        100% { opacity: 1;}
    }
    @-moz-keyframes mouse-scroll {

        0%   { opacity: 0; }
        50%  { opacity: .5; }
        100% { opacity: 1; }
    }
    @-o-keyframes mouse-scroll {

        0%   { opacity: 0; }
        50%  { opacity: .5; }
        100% { opacity: 1; }
    }
    @keyframes mouse-scroll {

        0%   { opacity: 0; }
        50%  { opacity: .5; }
        100% { opacity: 1; }
    }
    .noscroll{
        overflow: hidden;
    }
    .parent > div[class] {
        animation-name: changeme;
        animation-duration: 10s;
        animation-iteration-count: infinite;
        margin-bottom: 4px;
        margin: 0 auto;
    }
    @keyframes changeme {
        0% {
            min-width: 4em;
            width: 4em;
            background-color: #24D69F;
            height: 1vh;
        }
        100% {
            width: 50vw;
            min-width: 14em;
            background-color: #1E272C;
            height: 1vh;
        }
    }
    .footer-reseaux{
        display: block;
    }
    .mes-comptes::after {
        display: none;

    }
    .footer-reseaux ul{
        display: -webkit-box;
    }
    .mes-comptes li{
        display: inline-block;
    }

}



</style>
