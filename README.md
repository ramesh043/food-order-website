![image](https://github.com/ramesh043/food-order-website/assets/84142679/84f586a7-d5a5-45ce-ba67-dd175159d0b8)
# Food Order Website 
## You can see the entire Code 
### Basic Tecchnologies We use Html and CSS

### [you can click on link to see live webiste in your browser] 👉 <a href="https://food-orders-demo.netlify.app/">Food Order Website</a>
## Starter Project
- Create index.html
- Css external file (.css)
- folders/files already setup
- images folder (Sperate Folder)
- index.js for easier imports
## html code for reference
### header part or navbar 
```html

 <header>
      <nav class="nav-bar">
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Order</a></li>
          <li><a href="#">Food</a></li>
          <li><a href="#">Restaurant</a></li>
          <li><a href="#">Testimonials</a></li>
          <li><a href="#">Contact US</a></li>
          <img
            src="images/menu-bar.png"
            alt="menu-bar-png"
            class="menu-bar"
            width="40"
          />
        </ul>
      </nav>
    </header>
```
## Hero Section
```html
  <section class="section">
      <div class="hero-section">
        <div class="hero-section-content">
          <h1 class="hero-section-heading">Lorem IPSUM</h1>
          <p class="hero-section-paragraph">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamusid
            est vitae dolor rhoncus tristique. Maecenas metus quam,rhoncus
            euismod lorem in, sollicitudin viverra eros. Donecdictum luctus quam
            ut tristique. Curabitur nec faucibus purus.Quisque congue sem nec
            justo mollis, in tincidunt erat pretium.Sed pulvinar, massa ac porta
            viverra.
          </p>
          <a href="#" class="btn btn-block">Click Me</a>
        </div>
        <div class="hero-section-img">
          <img
            src="images/pexels-robin-stickel-70497.jpg"
            alt="robin-stickel-hero-image"
            width="600px"
            height="695px"
              style="object-fit: cover"
            />
          </div>
        </div>
      </section>
```
## Another Section to see Images and Gallery Here
```html
    <section class="section-img-container">
      <div class="grid-container">
        <div class="item-1">
          <img src="images/pexels-eva-bronzini-6141651.jpg" width="150px" />
        </div>
        <div class="item-2">
          <img src="images/pexels-mister-mister-3434523.jpg" width="320px" />
        </div>
        <div class="item-3">
          <img src="images/pexels-rachel-claire-6752433.jpg" width="150px" />
        </div>
        <div class="item-4">
          <div class="gallery-content">
            <p
              style="
                padding-bottom: 1rem;
                text-transform: uppercase;
                font-size: 14px;
                font-family: 'Trebuchet MS', 'Lucida Sans Unicode',
                  'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
                letter-spacing: 2px;
              "
            >
              lorem Ipsum
            </p>
            <h1 style="padding-bottom: 1rem">lorem Epsum Editor</h1>
            <div class="icons">
              <a href="#">Click </a>
              <img
                src="images/icons8-arrow-30.png"
                alt="icon-arrow"
                width="24px"
              />
            </div>
          </div>
        </div>
      </div>
    </section>
    <footer class="footer">
      <div class="social-links">
        <a href=" " class="link-icon"
          ><img src="images/github (1).png" width="20px" />GitHub</a
        >
      </div>
      <div class="footer-content">
        <marquee>❤️Created By Ramesh</marquee>
      </div>
    </footer>
```
## CSS Styling Code Here You can check here 
 - use Flexbox
 - Use Universal Selector
 - fonts
 - Responsive Design
 - Media Quries (tablet,mobile and laptop)
```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
ul {
  list-style-type: none;
}
a {
  text-decoration: none;
  letter-spacing: 2px;
  font-weight: 600;
}

/* To apply Header Style Here  */
header {
  position: fixed;
  top: 0;
  padding: 10px;
  background-color: #f97272;
  width: 100%;
}

.nav-bar ul {
  display: flex;

  justify-content: space-evenly;
  align-items: center;
}
.nav-bar ul li a {
  color: black;
  font-size: 18px;
  font-weight: 700;
  letter-spacing: 2px;
}
.section {
  background: linear-gradient(to right, rgba(255, 255, 97, 0.33) 5%, #bc7fcd);
  /* padding: 5rem; */
  height: 100vh;
}
.hero-section {
  /* padding: 4rem; */

  display: flex;
}
.hero-section-content {
  padding: 15rem;
}
.hero-section-content h1 {
  font-size: 3.6em;
  padding-bottom: 3rem;
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
  letter-spacing: 5px;
  font-weight: bolder;
  text-transform: uppercase;
}
.hero-section-content p {
  padding-bottom: 3rem;
  font-family: "Trebuchet MS", sans-serif;
  font-size: 13px;
  line-height: 1.5;
}
.btn {
  background-color: #f97272;
  padding: 0.7rem 3.5rem;
  text-transform: capitalize;
  color: white;
  text-align: center;
  font-size: 12px;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}
.grid-container {
  display: grid;
  grid-template-columns: 1fr 4fr 2fr;
  justify-content: center;
  align-items: center;
  gap: 1rem;

  padding: 10px;
  max-width: 1100px;
  margin: 0 auto;
}
.grid-container > div {
  /* text-align: center; */
  /* padding: 20px 0; */
  font-size: 30px;
}
.item-1 {
  grid-row: 2/ 4;
}
.item-2 {
  grid-row: 1/4;
}
.item-4 {
  grid-row: 1/4;
}
.gallery-content {
  padding-left: 3rem;
  padding: 1rem;

  width: 500px;
  background-color: #f97272;
}
.section-img-container {
  padding: 10rem;
  background: linear-gradient(to right, rgba(255, 255, 97, 0.33) 5%, #bc7fcd);
  height: 100vh;
}
.gallery-content a {
  text-transform: capitalize;
  color: black;
  text-align: start;

  font-size: 12px;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}
.gallery-content img {
  display: inline;
}
.gallery-content h1 {
  font-size: 3.2rem;
  padding-bottom: 2rem;
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
  letter-spacing: 5px;
  font-weight: bolder;
  text-transform: uppercase;
}
@media only screen and (max-width: 600px) {
  .hero-section {
  }
}

@media only screen and (min-width: 768px) {
}

@media only screen and (min-width: 992px) {
}
@media only screen and (min-width: 1200px) {
}
.icons {
  display: flex;
  align-items: center;
}
.icons img {
  margin-left: 0.5rem;
}

.footer {
  display: flex;
  background-color: white;
  align-items: center;
  height: 70px;
  justify-content: space-around;
}
.social-links a {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  color: black;
  text-transform: lowercase;
  border: 1px solid #ddd;
  padding: 0.6rem 1rem;
  transition: all 0.7s ease-out;
  border-radius: 4px;
}
.social-links a:hover {
  transform: translateY(-10px);
}
.footer-content marquee {
  display: flex;
  align-items: center;
  font-weight: 700;
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
}
```

