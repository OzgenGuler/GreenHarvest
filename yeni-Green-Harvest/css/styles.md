/*tolga*/

/*header*/
/* -----------desktop---------- */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
ul {
  list-style: none;
}
a {
  text-decoration: none;
}
.hamburger-icon {
  display: none;
}
header {
  display: flex;
  flex-direction: row;
}
.nav-bar {
  width: 100%;
  margin-top: 32px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 52px;
  gap: 20px;
  opacity: 0px;
  background-color: black;
}
.nav-menu {
  display: flex;
}
.nav-logo {
  display: flex;
  margin-left: 100px;
  width: 216px;
  height: 20px;
  padding: 0px 0.44px 0px 0px;
  gap: 0px;
  opacity: 0px;
}

.nav-ul {
  align-items: center;
  padding-left: 366px;
  padding-right: 20px;
  padding-top: 4px;
  padding-bottom: 4px;
  justify-content: space-between;
  flex-direction: row;
  display: flex;
  height: 44px;
  gap: 8px;
  opacity: 0px;
  background-color: transparent;
  color: #fbfbfb;
}

.nav-ul li {
  padding-top: 12px;
  padding-bottom: 12px;
  border-radius: 12px;
  opacity: 0px;
  border: 1px solid #fbfbfb;
}
.nav-ul li:hover {
  background-color: #d4bfc4;
  color: #7a3145;
}
.nav-ul li:active {
  background-color: #fbfbfb;
  color: #7a3145;
}
.nav-ul li a:hover {
  color: #7a3145;
}
.nav-ul li a:active {
  color: #7a3145;
}

.nav-ul a {
  width: 94px;
  height: 20px;
  text-align: center;
  gap: 0px;
  opacity: 0px;
  font-family: Inter Tight;
  font-size: 16px;
  font-weight: 500;
  line-height: 20px;
  color: #fbfbfb;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}

.nav-button {
  padding: 16px 32px;
  margin-right: 100px;
  justify-content: space-between;
  gap: 10px;
  border-radius: 30px;
  opacity: 0px;
  background: #7a3145;
  color: #fbfbfb;
  font-family: Inter Tight;
  font-size: 18px;
  font-weight: 600;
  line-height: 20px;
  letter-spacing: -0.015em;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
  text-transform: uppercase;
}
.nav-button:hover {
  background: #d4bfc4;
  color: #7a3145;
}
.nav-button:active {
  background: #fbfbfb;
  color: #7a3145;
}
@media (min-width: 320px) and (max-width: 767px) {
  .nav-ul,
  .nav-button {
    display: none;
  }
  .hamburger-icon {
    display: block;
    margin-right: 20px;
    padding: 8px 5.33px 8px 5.33px;
    gap: 0px;
    opacity: 0px;
  }
  .nav-logo {
    width: 168px;
    height: 16px;
    gap: 4px;
    opacity: 0px;
    margin-left: 20px;
    display: flex;
    padding: 0px 0.44px 0px 0px;
  }
  .nav-ul {
    background: #576f35;
  }
}
@media (min-width: 768px) and (max-width: 1279px) {
  .nav-ul,
  .nav-button {
    display: none;
  }
  .hamburger-icon {
    display: block;
    margin-right: 20px;
    padding: 8px 5.33px 8px 5.33px;
    gap: 0px;
    opacity: 0px;
  }
  .nav-logo {
    display: flex;
    margin-left: 32px;
    width: 216px;
    height: 20px;
    padding: 0px 0.44px 0px 0px;
    gap: 0px;
    opacity: 0px;
  }
}
/*hero*/
.hero {
  display: flex;
  justify-content: space-between;
  width: 1280;
  height: 796;
}
.hero-container {
  padding-left: 100px;
  background-color: #576f35;
  height: 796px;
  width: 100%;
  text-align: center;
  gap: 128px;
  padding-top: 148px;
  padding-right: 36px;
}
.hero-baslik {
  width: 502px;
  height: 304px;
  gap: 0px;
  opacity: 0px;
  gap: 0px;
  opacity: 0px;
  font-family: "Inter Tight";
  font-size: 76px;
  font-weight: 600;
  line-height: 76px;
  letter-spacing: -0.015em;
  text-align: left;
  text-underline-position: "from-font";
  text-decoration-skip-ink: none;
  text-transform: uppercase;
  color: #fbfbfb;
}
.hero-text {
  padding-top: 52px;
  padding-right: 32px;
  width: 472px;
  height: 80px;
  gap: 0px;
  opacity: 0px;
  font-family: Inter Tight;
  font-size: 16px;
  font-weight: 500;
  line-height: 20px;
  text-align: left;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
  color: #fbfbfb;
}
.hero-image {
  background-image: linear-gradient(
      rgba(20, 20, 20, 0.2),
      rgba(20, 20, 20, 0.2)
    ),
    url(../images/hero-image.jpg);

  width: 100%;
  height: 796px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

@media (min-width: 320px) and (max-width: 767px) {
  .hero {
    width: 375px;
    height: 840px;
    flex-direction: column;
    display: flex;
  }
  .hero-container {
    background-color: #576f35;
    width: 375px;
    height: 468px;
    gap: 48px;
    opacity: 0px;
  }
  .hero-baslik {
    padding: 48px 20px 40px 20px;
    width: 335px;
    height: 208px;
    gap: 0px;
    opacity: 0px;
    font-family: "Inter Tight";
    font-size: 52px;
    font-weight: 600;
    line-height: 52px;
    letter-spacing: -0.015em;
    text-align: left;
    text-underline-position: "from-font";
    text-decoration-skip-ink: none;
  }

  .hero-text {
    padding: 20px 20px 40px 20px;
    width: 335px;
    height: 100px;
    gap: 0px;
    opacity: 0px;
    font-family: "Inter Tight";
    font-size: 14px;
    font-weight: 500;
    line-height: 20px;
    text-align: left;
    text-underline-position: "from-font";
    text-decoration-skip-ink: none;
  }
  .hero-image {
    background-image: linear-gradient(
        rgba(20, 20, 20, 0.2),
        rgba(20, 20, 20, 0.2)
      ),
      url(../images/hero-image@2x.jpg);

    width: 375px;
    height: 372px;

    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
  }
}
@media (min-width: 768px) and (max-width: 1279px) {
  .hero {
    flex-direction: column;
    display: flex;
    width: 768px;
    height: 1020px;
    background-color: #576f35;
  }
  .hero-container {
    width: 704px;
    height: 312px;
  }
  .hero-baslik {
    padding-top: 40px;
    padding-left: 32px;
    padding-right: 32px;
    width: 704px;
    height: 228px;
    opacity: 0px;
    font-family: "Inter Tight";
    font-size: 76px;
    font-weight: 600;
    line-height: 76px;
    letter-spacing: -0.015em;
    text-align: left;
    text-underline-position: "from-font";
    text-decoration-skip-ink: none;
  }
  .hero-text {
    padding-left: 32px;
    width: 603px;
    height: 60px;
    font-family: "Inter Tight";
    font-size: 16px;
    font-weight: 500;
    line-height: 20px;
    text-align: left;
    text-underline-position: "from-font";
    text-decoration-skip-ink: none;
  }
  .hero-image {
    background-image: linear-gradient(
        rgba(20, 20, 20, 0.2),
        rgba(20, 20, 20, 0.2)
      ),
      url(../images/hero-image@3x.jpg);
    width: 768;
    height: 536px;
  }
}

/*okan*/

/*howitworks*/
.section-two {
  display: flex;
  align-items: center;
  text-align: center;
  justify-content: center;
  margin-left: auto;
  margin-right: auto;
}
.div-images {
  display: flex;
  align-items: center;
  padding: 100px;
  background-color: #7a3145;
  width: 640px;
  height: 760px;
}
.div-images img {
  width: 440px;
  object-fit: cover;
  border-radius: 30px;
  height: 560px;
}
.section-two-h {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.howitworks-div {
  display: flex;
  flex-direction: column;
  background-color: #576f35;
  padding: 100px;
  gap: 105px;
  width: 640px;
  height: 760px;
}
.section-two-h {
  color: white;
  gap: 24px;
}
.span-h {
  color: #d4bfc4;
}
.text-1 {
  width: 440px;
  height: 96px;
  font-family: "Inter Tight";
  font-weight: 600;
  font-size: 32px;
  letter-spacing: -0.015em;
  line-height: 32px;
  text-transform: uppercase;
  text-align: left;
  text-underline-position: "from-font";
  text-decoration-skip-ink: none;
  padding: 0;
}
h2.text-1 {
  margin: 0;
}
.text-2 {
  width: 440px;
  height: 60px;
  font-family: "Inter Tight";
  font-weight: 500;
  font-size: 16px;
  line-height: 20px;
  text-align: left;
  text-underline-position: "from-font";
  text-decoration-skip-ink: none;
}
p.text-2 {
  margin: 0;
}
.section-ol {
  width: 440px;
  color: grey;
  list-style-type: none;
  padding: 0;
  display: flex;
  flex-direction: column;
  gap: 24px;
  margin: 0;
}
.section-ol p {
  font-family: "Inter Tight";
  font-size: 16px;
  font-weight: 500;
  line-height: 20px;
  text-align: left;
  text-underline-position: "from-font";
  text-decoration-skip-ink: none;
  margin: 0;
}
.item {
  display: flex;
  align-items: center;
  background-color: white;
  border-radius: 15px;
  padding-top: 12px;
  padding-right: 25px;
  padding-bottom: 12px;
  padding-left: 24px;
  gap: 10px;
}
.item-number {
  padding: 11px 17px;
  background-color: #7a3145;
  color: #fbfbfb;
  font-family: "Inter Tight";
  font-size: 18px;
  font-weight: 600;
  line-height: 20px;
  letter-spacing: -0.015em;
  border: 5px solid #d4bfc4;
  border-radius: 50%;
}
.span-list {
  color: black;
  font-family: "Inter Tight";
  font-size: 16px;
  font-weight: 700;
  line-height: 20px;
  text-align: left;
  text-underline-position: "from-font";
  text-decoration-skip-ink: none;
}

/*TABLET TASARIM*/
@media (min-width: 768px) and (max-width: 1157px) {
  .section-two {
    width: 768px;
    flex-direction: column;
  }
  .div-images {
    padding: 100px 64px;
    width: 768px;
    height: 840px;
  }
  .div-images img {
    width: 640px;
    height: 640px;
  }
  .howitworks-div {
    width: 768px;
  }
  .section-ol {
    margin: auto;
    width: 440px;
  }
  .span-list {
    font-family: "Inter Tight";
    font-size: 16px;
    font-weight: 700;
    line-height: 20px;
    text-align: left;
    text-underline-position: "from-font";
    text-decoration-skip-ink: none;
  }
}

/*MOBIL*/
@media (min-width: 320px) and (max-width: 767px) {
  .section-two {
    flex-direction: column;
  }
  .div-images {
    margin: auto;
    width: 375px;
    height: 532px;
    padding: 40px 20px;
  }
  .div-images img {
    width: 335px;
    height: 452px;
  }
  .howitworks-div {
    gap: 40px;
    padding: 80px 20px 80px 20px;
    width: 375px;
    height: 676px;
  }
  .section-two-h {
    width: 335px;
    height: 192px;
  }
  .text-1 {
    width: 335px;
    height: 112px;
    gap: 20px;
    line-height: 28px;
    font-size: 28px;
  }
  .text-2 {
    width: 335px;
    height: 60px;
    font-size: 14px;
    line-height: 20px;
  }
  .section-ol {
    width: 335px;
    height: 284px;
  }
  .section-ol .item {
    width: 335px;
    height: 84px;
  }
}
/*fatmanur*/

/*ADVERTİSEMENT*/
.section-white h2 {
  display: none;
}
.container {
  width: 1054px;
  height: 228px;
  gap: 10px;
  margin: 100px;
}

.advertisement-discount {
  background-color: #576f35;
  color: #fbfbfb;
  font-family: "Inter Tight";
  font-size: 76px;
  font-weight: 600;
  line-height: 76px;
  letter-spacing: -1.5%;
  text-align: left;
  text-underline-position: "from-font";
  text-decoration-skip-ink: none;
  text-transform: uppercase;
  border-radius: 12px;
  padding-left: 16px;
  padding-right: 16px;
  width: 808px;
  height: 84px;
  top: -4px;
}

.three-second {
  font-family: "Inter Tight";
  font-size: 76px;
  font-weight: 600;
  line-height: 76px;
  letter-spacing: -0.015em;
  text-align: left;
  text-underline-position: "from-font";
  text-decoration-skip-ink: none;
  text-transform: uppercase;
}
.advertisement-description {
  width: 100%;
  --pseudo-heigth: calc(1em * 1.08 * 2);
}

.advertisement-description {
  display: inline-block;
  position: relative;
  z-index: 1;
}

.advertisement-discount .three-second .discount .three-second-white {
  width: 675px;
  height: 86px;
  border-radius: 12px;
  background-color: #576f35;
  color: #fbfbfb;
}

.advertisement-discount.three-second::before {
  content: "";
  width: 100%;
  height: var(--pseudo-heigth);
  left: 0px;
  top: 0;
  position: absolute;
  background-color: var(--green);
  border-radius: 25px;
  display: inline-block;
  z-index: -1;
}

@media (min-width: 768px) and (max-width: 1157px) {
  .advertisement-description {
    --pseudo-heigth: calc(1em + 11px * 2);
    width: 704px;
    height: 288px;
    font-size: 64px;
    line-height: 64px;
  }

  .advertisement-discount {
    margin-top: 20px;
    width: 708px;
    height: 256px;
    font-size: 64px;
    line-height: 64px;
  }

  .advertisement-discount.three-second::before {
    top: -20px;
    position: absolute;
  }
  .section-white {
    width: 768px;
    height: 488px;
  }
}

@media (min-width: 320px) {
  .container {
    width: 375px;
    height: 472px;
    top: 2048px;
    padding: 80px 20px 80px 20px;
    gap: 10px;
    opacity: 0px;
  }

  .advertisement-description {
    width: 375px;
    height: 472px;
    font-size: 48px;
    line-height: 52px;
    letter-spacing: -1.5%;
  }

  .advertisement-discount {
    margin-top: 20px;
    width: 335px;
    height: 102px;
    font-size: 48px;
    line-height: 52px;
    padding-right: 142px;
  }

  .advertisement-discount.three-second::before {
    top: -20px;
    position: absolute;
  }
  .section-white {
    width: 335px;
    height: 312px;
  }
}
/*vegetables*/

.four-section-vegetables {
  background-color: #7a3145;
  display: flex;
  flex-direction: column;
}
.organic-vegetables {
  display: flex;
  flex-direction: column;
  margin-right: 454px;
  width: 626px;
  height: 192px;
  gap: 24px;
  opacity: 0px;
}

.organic-vegetables .title-vegetables {
  font-family: "Inter Tight";
  font-size: 64px;
  font-weight: 600;
  line-height: 64px;
  letter-spacing: -0.015em;
  text-transform: uppercase;
  margin: 0;
  margin-right: 118px;
  width: 508px;
  height: 128px;
}

.container {
  padding: 100px;
}

.four-second {
  color: #fbfbfb;
}

.vegetables-accent {
  color: #d4bfc4;
}

.organic-vegetables p {
  font-family: "Inter Tight";
  color: #fbfbfb;
  font-size: 16px;
  font-weight: 500;
  line-height: 20px;
  width: 626px;
  padding-bottom: 24px;
  margin-top: auto;
  height: 40px;
}

.vegetables-item {
  row-gap: 28px;
}

.vegetables-cards {
  color: #7a3145;
  font-family: "Inter Tight";
  font-size: 32px;
  font-weight: 400;
  line-height: 0;
  letter-spacing: -0.015em;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  padding-bottom: 60px;
  width: 1080px;
  height: 788px;
  gap: 24px;
  margin-left: -30px;
  margin-top: -10px;
  column-gap: 20px;
  row-gap: 28px;
}

.vegetables-fiyat {
  display: none;
}

/*özkan*/

/*REVİEWS*/

/* General Reset */

ul {
  list-style: none;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Arial", sans-serif;
  background-color: #fff;
  color: #333;
  line-height: 1.6;
}

/* Reviews Section */
.reviews {
  text-align: left;
  padding: 100px;
  display: flex;
  flex-direction: column;
  gap: 52px;
}

.reviews-header {
  max-width: 553px;
  display: flex;
  flex-direction: column;
  gap: 24px;
}

.reviews-title {
  font-family: "Inter Tight", sans-serif;
  font-weight: 600; /* Semi Bold */
  font-size: 3rem;
  color: #000;
  line-height: 1.2;
}

.reviews-title span {
  display: block;
}

.reviews-description {
  font-family: "Inter Tight", sans-serif;
  font-weight: 500; /* Medium */
  font-size: 1rem;
  color: #555;
  line-height: 1.5;
}

.highlight {
  color: #576f35; /* Green Highlight */
}

.reviews-list {
  display: flex;
  flex-wrap: nowrap;
  gap: 24px;
  overflow: hidden;
}

/* Review Item */
.review-item {
  background-color: #f8f8f8;
  border: 1px solid #d4bfc4; /* Color: Blush */
  border-radius: 10px;
  padding: 20px;
  text-align: center;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease-in-out;
  flex: 1 1 100%;
}

.review-card {
  padding: 20px;
}

.review-item:hover {
  transform: scale(1.05);
}

.review-img {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin-bottom: 10px;
}

.review-name {
  font-weight: bold;
  color: #000;
  margin-bottom: 10px;
}

.review-text {
  font-size: 0.9rem;
  color: #666;
}

/* Desktop View: Show all reviews */
@media (min-width: 1280px) {
  .reviews-list {
    flex-wrap: wrap;
  }

  .review-item {
    flex: 1 1 calc(33.3333% - 16px);
    max-width: calc(33.3333% - 16px);
  }
}

/* Tablet View: Show 2 reviews at a time */
@media (min-width: 768px) and (max-width: 1279px) {
  .review-item:nth-child(1n + 3) {
    display: none;
  }

  .reviews-list {
    justify-content: space-between;
  }

  .review-item {
    flex: 1 1 calc(50% - 16px);
    max-width: calc(50% - 16px);
  }
}

/* Mobile View: Adjust padding and spacing */
@media (max-width: 767px) {
  .reviews {
    padding: 80px 20px;
  }

  .review-item {
    margin: 0 auto;
    flex: 1 1 100%;
    max-width: 100%;
  }

  .reviews-list {
    justify-content: center;
  }

  .review-item:nth-child(1n + 2) {
    display: none;
  }
}

/* Retina Display Optimization */
.review-img {
  background-size: cover;
  image-rendering: -webkit-optimize-contrast;
}
/* SVG Sprite */
svg {
  display: none;
}
/* Loading Optimization */
img[loading="lazy"] {
  opacity: 0;
  transition: opacity 0.3s ease-in-out;
}
img[loading="lazy"].loaded {
  opacity: 1;
}
/* Accessibility Enhancements */
.review-item:focus-within {
  outline: 2px solid #6e8b3d;
}
.review-item:hover {
  transform: scale(1.02);
  transition: transform 0.2s ease-in-out;
}

/*özgen*/

/*YOUR ORDER*/

.your-order {
  background: rgba(87, 111, 53, 1);
  padding-inline: 100px;
  gap: 52px;
  display: flex;
  flex-direction: column;
  width: 1280px;
  height: 1036px;
}

.text-fresh {
  text-align: left;
}

.your-order .text-fresh_title {
  font-family: "Inter Tight";
  font-size: 64px;
  font-weight: 600;
  line-height: 64px;
  letter-spacing: -0.015em;
  text-align: left;
  color: rgba(251, 251, 251, 1);
  width: 751px;
  height: 128px;
  gap: 24px;
}

.text-fresh_title .harvest-span {
  color: rgba(212, 191, 196, 1);
}

.text-fresh_text {
  font-family: "Inter Tight" sans-serif;
  font-size: 16px;
  font-weight: 500;
  line-height: 20px;
  text-align: left;
  color: rgba(251, 251, 251, 1);
  width: 742px;
  height: 40px;
}

.group-div {
  display: flex;
  width: 1080px;
  height: 592px;
  gap: 32px;
}

.form {
  border-radius: 30px;
  background: rgba(251, 251, 251, 1);
  width: 524px;
  height: 592px;
  padding: 52px 48px 52px 48px;
  gap: 10px;
  border-radius: 30px;
}

.form-text {
  font-family: "Inter Tight" sans-serif;
  font-size: 32px;
  font-weight: 600;
  line-height: 32px;
  letter-spacing: -0.015em;
  text-align: left;
  text-transform: uppercase;
}

.form-us {
  color: rgba(122, 49, 69, 1);
}

.the-form {
  color: rgba(87, 111, 53, 1);
}

.form-modal .input-btn {
  width: 100%;
  padding: 16px;
  column-gap: 16px;
  border-radius: 30px;
  border: 1px;
  flex-direction: column;
  display: flex;
  align-items: center;
  border: 1px solid rgba(133, 133, 133, 1);
  color: rgba(20, 20, 20, 1);
  margin-bottom: 16px;
  outline: none;
}

.form-modal .input-btn p {
  margin: 0;
}

.input-btn::placeholder {
  color: black;
}

.input-btn:focus {
  border-color: brown;
}

.input-btn:not(:placeholder-shown):invalid {
  border-color: red;
}

.input-btn:not(:placeholder-shown):valid {
  border-color: green;
}

.text-valid,
.text-invalid {
  font-size: 14px;
  padding-left: 20px;
  margin-top: 4px;
  display: none;
}

.text-valid {
  color: green;
}

.text-invalid {
  color: red;
}

.input-btn:not(:placeholder-shown):valid ~ .text-valid {
  display: block;
}

.input-btn:not(:placeholder-shown):invalid ~ .text-invalid {
  display: block;
}

.form-modal_btn {
  /* width: 428px;
height:52px; */
  padding: 16px 191px 16px 191px;
  gap: 10px;
  border-radius: 30px;
  background: rgba(122, 49, 69, 1);
  color: rgba(251, 251, 251, 1);
  font-family: "Inter Tight" sans-serif;
  font-size: 18px;
  font-weight: 600;
  line-height: 20px;
  letter-spacing: -0.015em;
  text-align: left;
  text-transform: uppercase;
}

.form-modal_btn:hover {
  background-color: #fbfbfb;
  color: #7a3145;
}

.image-social {
  background: rgba(122, 49, 69, 1);
  width: 524px;

  padding: 52px 48px 52px 48px;
  gap: 80px;
  border-radius: 30px;
  text-align: left;
}

.image-social img {
  width: 428px;
  height: 352px;
  border-radius: 15px;
  margin-bottom: 80px;
}

.image-social p {
  font-family: "Inter Tight";
  font-size: 16px;
  font-weight: 700;
  line-height: 20px;
  color: rgba(212, 191, 196, 1);
  text-align: left;
  height: 20px;
  /* padding-top: 80px;
  padding-bottom: 16px; */
  display: flex;
}

.social-link {
  gap: 12px;
  display: flex;
  flex-wrap: wrap;
  font-family: "Inter Tight";
  font-size: 18px;
  font-weight: 600;
  line-height: 20px;
  letter-spacing: -0.015em;
  color: white;
  list-style: none;
  padding: 0;
}

.social-link .text-link a {
  text-decoration: none;
  color: white;
}

/* Tablet*/

@media (min-width: 768px) and (max-width: 1158px) {
  .your-order {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 100px 0px 100px 0px;
    width: 768px;
    height: 1720px;
  }

  .text-fresh {
    width: 768px;
    padding: 0px 96px 0px 32px;
    column-gap: 52px;
    display: flex;
    flex-direction: column;
  }

  .your-order .text-fresh_title {
    width: 640px;
    height: 192px;
    opacity: 0px;
  }

  .text-fresh_text {
    width: 640px;
    height: 60px;
    column-gap: 52px;
  }

  .group-div {
    width: 768px;
    height: 1192px;
    padding: 0px 64px 0px 64px;
    display: flex;
    flex-direction: column;
  }

  .form {
    width: 640px;
    height: 632px;
    padding: 72px 100px 72px 100px;
    gap: 10px;
    border-radius: 30px;
    column-gap: 32px;
  }

  .image-social {
    width: 640px;
    height: 528px;
    border-radius: 30px;
    gap: 52px;
  }

  .image-social img {
    width: 536px;
    height: 316px;
    color: #14141433;
    margin-bottom: 52px;
  }

  .image-social p {
    width: 243px;
    gap: 50px;
  }

  .social-link .text-link {
    width: 81px;
    height: 20px;
  }
}

/* Mobil*/

@media (max-width: 767px) {
  .your-order {
    padding: 0px 20px 0px 20px;
    width: 375px;
    height: 1536px;
    gap: 40px;
  }

  .text-fresh {
    width: 335px;
    column-gap: 40px;
    display: block;
  }

  .your-order .text-fresh_title {
    width: 335px;
    height: 208px;
    line-height: 52px;
    font-size: 48px;
    display: block;
  }

  .text-fresh_text {
    font-size: 14px;
    column-gap: 40px;
    width: 335px;
    height: 80;
    display: block;
    line-height: 20px;
  }

  .group-div {
    width: 335px;
    height: 1028px;
    display: flex;
    flex-direction: column;
    padding: 40px 0px 40px 0px;
  }

  .form {
    width: 335px;
    height: 552px;
    padding: 40px 20px 40px 20px;
  }

  .form-text {
    font-size: 28px;
    width: 295px;
    height: 140px;
    column-gap: 40px;
    line-height: 28px;
  }

  .form-modal_btn {
    width: 295px;
    padding: 16px 129px 16px 129px;
    gap: 10px;
  }

  .image-social {
    width: 335px;
    padding: 40px 20px 20px 20px;
    height: 456;
  }

  .image-social img {
    width: 295px;
    height: 272px;
    margin-bottom: 20px;
  }

  .image-social p {
    width: 213px;
    height: 20;
    line-height: 20px;
    font-size: 14px;
  }

  .social-link .text-link {
    width: 100px;
    height: 20px;
  }
}

/* The End :) */

/*beyza*/

/*FOOTER*/

.fote-r {
  background-color: rgba(122, 49, 69, 1);
  height: 392px;
  top: 4944px;
  padding: 20px 20px 2px 20px;
  gap: 124px;
  background-position: center;
  width: 1280px;
  display: inline-block;
}
.container {
  background-color: rgba(122, 49, 69, 1);
  background-position: center;
  display: flex;
  width: auto;
  margin: 0 auto;
  padding-left: 60px;
  border-top: none;
  align-items: baseline;
  flex-wrap: wrap;
  justify-content: space-between;
}
.span-a {
  color: white;
  width: 216px;
  height: 20px;
  gap: 0px;
  font-weight: 700;
  padding-left: 10px;
}
.yazi-i {
  font-family: "Inter Tight";
  font-size: 16px;
  font-weight: 500;
  line-height: 20px;
  text-align: left;
  text-decoration: none;
  color: white;
  margin-left: auto;
  justify-content: flex-start;
  gap: 0px;
  width: 265px;
  height: 60px;
  display: flex;
}
.one-li {
  font-family: "Inter Tight";
  font-size: 32px;
  font-weight: 600;
  line-height: 32px;
  letter-spacing: -0.015em;
  text-align: left;
  text-decoration: none;
  color: white;
  position: relative;
  margin-bottom: 16px;
  justify-content: space-between;
  display: flex;
  gap: 24px;
  font-style: normal;
}
.tel-no {
  font-family: "Inter Tight";
  font-size: 16px;
  font-weight: 700;
  line-height: 60px;
  text-align: left;
  text-underline-position: from-font;
  text-decoration: none;
  color: white;
  justify-content: end;
  font-style: normal;
}
.adr-ess {
  color: white;
  font-family: "Inter Tight";
  font-size: 16px;
  font-weight: 700;
  line-height: 20px;
  text-align: left;
  text-underline-position: from-font;
  text-decoration: none;
  font-style: normal;
  padding-right: 0px;
  width: 215px;
  height: 40px;
}
.priv-acy {
  color: rgba(212, 191, 196, 1);
}
.green-h {
  color: rgba(212, 191, 196, 1);
  justify-content: flex-end;
}
.green-harvest {
  justify-content: flex-end;
  flex-direction: row;
}
.div-two {
  display: flex;
  justify-content: space-between;
}
.div-one {
  display: flex;
  justify-content: flex-start;
  width: 186.67px;
  height: 16.67px;
  gap: 0px;
  top: 2.22px;
  left: 28.89px;
  padding-top: 10px;
}
.one-ul {
  list-style-type: none;
  gap: 24px;
  padding-left: 200px;
}
.two-ul {
  list-style-type: none;
}
.section-second {
  padding-bottom: 110px;
  padding-left: 0px;
  padding-right: 60px;
}
.adre-s {
  width: 215px;
}
@media (min-width: 768px) and (max-width: 1158px) {
  .fote-r {
    width: 768px;
    height: 476px;
    padding-top: 10px;
    padding-bottom: 5px;
  }
  .one-ul {
    width: 310px;
    height: 120px;
    gap: 24px;
    padding-left: 80px;
  }
  .section-second {
    width: 704px;
    padding-left: 15px;
    padding-right: 10px;
    padding-bottom: 160px;
  }
  .container {
    width: 704px;
    padding-left: 5px;
  }
  .adre-s {
    width: 735px;
    height: 84px;
    padding-left: 430px;
  }
  .tel-no {
    line-height: 50px;
    width: 163px;
    height: 20px;
  }
  .adr-ess {
    width: 215px;
    height: 40px;
  }
}
@media (min-width: 320px) and (max-width: 767px) {
  .fote-r {
    width: 375px;
    height: 584px;
  }
  .container {
    width: 335px;
    padding-left: 0px;
  }
  .div-one {
    width: 168px;
    height: 16px;
  }
  .div-two {
    width: 335px;
    height: 60px;
  }
  .yazi-i {
    width: 335px;
    line-height: 20px;
    height: 90px;
    padding-top: 20px;
  }
  .one-ul {
    width: 227px;
    height: 124px;
    padding-left: 0px;
    padding-top: 60px;
    letter-spacing: 0.07em;
    gap: 14px;
  }
  .tel-no {
    width: 143px;
    height: 20px;
  }
  .adr-ess {
    width: 178px;
    height: 40px;
  }
  .two-ul {
    width: 215px;
    height: 74px;
    padding-left: 0px;
    padding-top: 50px;
  }
  .section-third {
    width: 335px;
    height: 56px;
    padding-top: 40px;
  }
  .priv-acy {
    line-height: 50px;
  }
  .span-a {
    width: 146px;
    height: 19px;
    font-size: 18px;
    padding-left: 5px;
  }
  .adre-s {
    width: 215px;
    height: 74px;
    font-size: 14px;
    letter-spacing: 0.05em;
  }
}
