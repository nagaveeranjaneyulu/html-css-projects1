html-css-project1

(HTML)COVID-19 Page-1
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div class="covid-container">
      <div class="covid-header d-flex flex-row">
        <div>
          <h1 class="covid-heading-text">All you need to know about COVID-19</h1>
          <button class="button">Know more</button>
        </div>
        <img
          src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/medicalcare-img.png"
        />
      </div>
      <div class="covid-card-container covid-test-bg d-flex flex-row">
        <img
          class="covid-card-image"
          src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/coronavirus-img.png"
        />
        <div class="covid-card-text-container">
          <h1 class="covid-card-heading">
            COVID-19 Test
          </h1>
          <p class="covid-card-description">
            If you think you have been exposed to novel coronavirus
            (COVID-19)...more
          </p>
        </div>
      </div>
      <h1 class="sub-heading">Symptoms</h1>
      <div class="d-flex flex-row">
        <div class="covid-card-container cough-symptom-bg">
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/cough-img.png"
          />
          <p class="symptom-text">Dry Cough</p>
        </div>
        <div class="covid-card-container fever-symptom-bg">
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/fever-img.png"
          />
          <p class="symptom-text">High Fever</p>
        </div>
        <div class="covid-card-container headache-symptom-bg">
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/headache-img.png"
          />
          <p class="symptom-text">Headache</p>
        </div>
      </div>
      <h1 class="sub-heading">Videos</h1>
      <div class="covid-card-container covid-video-bg d-flex flex-row">
        <img
          class="covid-card-image"
          src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/doctor-img.png"
        />
        <div class="covid-card-text-container">
          <h1 class="covid-card-heading">
            To prevent the spread of ..
          </h1>
          <p class="covid-card-description">
            If you think you have been exposed to novel corona virus
            (COVID-19)
          </p>
          <button class="button">
            Watch Video
          </button>
        </div>
      </div>
    </div>
  </body>
</html>

(CSS)COVID-19 Page-1

.covid-container {
  border-style: solid;
  border-width: 5px;
  border-color: #0967d219;
}

.covid-header {
  margin: 15px;
}

.covid-heading-text {
  color: #323f4b;
  font-family: "Roboto";
  font-size: 18px;
  font-weight: 500;
}

.button {
  color: #ffffff;
  background-color: #0967d2;
  font-family: "Roboto";
  font-size: 12px;
  font-weight: 500;
  width: 85px;
  height: 30px;
  border-width: 0;
  border-radius: 8px;
}

.covid-card-container {
  border-radius: 12px;
  padding: 10px;
  margin: 10px;
}

.covid-test-bg {
  background-color: #0967d219;
}

.covid-card-image {
  width: 48px;
  height: 48px;
  margin: 10px;
}

.covid-card-text-container {
  padding: 5px;
}

.covid-card-heading {
  color: #323f4b;
  font-family: "Roboto";
  font-size: 16px;
  font-weight: 500;
}

.covid-card-description {
  color: #707070;
  font-family: "Roboto";
  font-size: 12px;
}

.sub-heading {
  color: #323f4b;
  font-family: "Roboto";
  font-size: 16px;
  font-weight: 500;
  margin: 15px;
}

.cough-symptom-bg {
  background-color: #3ebd93;
}

.fever-symptom-bg {
  background-color: #e668a7;
}

.headache-symptom-bg {
  background-color: #a368fc;
}

.symptom-text {
  color: #ffffff;
  font-family: "Roboto";
  font-size: 12px;
  font-weight: 500;
  margin: 5px;
}

.covid-video-bg {
  background-color: #e12d3919;
}




(HTML)Book Store Page-2

<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div id="sectionBookStoreHome">
      <div class="book-store-home-page">
        <h1 class="home-page-heading">Popular Book</h1>
        <div class="popular-book-container d-flex flex-row">
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/book-apj-img.png"
            class="popular-book-image"
          />
          <div class="popular-book-short-details-container">
            <h1 class="popular-book-heading">Wings of Fire</h1>
            <p class="popular-book-text">
              An Autobiography of<br />Abdul Kalam
            </p>
            <p class="popular-book-author">by Arun Tiwari</p>
            <button
              class="button btn btn-primary"
              onclick="display('sectionWingsOfFireBookDetails')"
            >
              Read Now
            </button>
          </div>
        </div>
        <h1 class="recommended-books-heading">Recommended Books</h1>
        <div class="recommended-book-container d-flex flex-row">
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/book-chetan-bhagat-img.png"
            class="recommended-book-image"
          />
          <div class="recommended-book-short-details-container">
            <h1 class="recommended-book-name">The 3 mistakes of my life</h1>
            <p class="recommended-book-description">
              Indian author<br />by Chetan Bhagat
            </p>
            <button
              class="button btn btn-primary"
              onclick="display('sectionTheThreeMistakesOfMyLifeBookDetails')"
            >
              Read Now
            </button>
          </div>
        </div>
        <div class="recommended-book-container d-flex flex-row">
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/harrypotter-img.png"
            class="recommended-book-image"
          />
          <div class="recommended-book-short-details-container">
            <h1 class="recommended-book-name">Harry Potter</h1>
            <p class="recommended-book-description">
              and the Sorcerer's Stone<br />by J.K.Rowling
            </p>
            <button
              class="button btn btn-primary"
              onclick="display('sectionHarryPotterBookDetails')"
            >
              Read Now
            </button>
          </div>
        </div>
      </div>
    </div>
    <div id="sectionWingsOfFireBookDetails">
      <div class="book-details-page">
        <img
          src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/book-apj-img.png"
          class="book-details-page-image"
        />
        <h1 class="book-name">Wings of Fire</h1>
        <p class="author">by Arun Tiwari</p>
        <p class="book-description">
          Every common man who by his sheer grit and hard work achieves success
          should share his story with the rest for they may find inspiration and
          strength to go on, in his story. The 'Wings of Fire' is one such
          autobiography by visionary scientist Dr. APJ Abdul Kalam, who from
          very humble beginnings rose to be the President of India. The book is
          full of insights, personal moments and life experiences of Dr. Kalam.
          It gives us an understanding on his journey of success.
        </p>
        <button
          class="button btn btn-warning"
          onclick="display('sectionBookStoreHome')"
        >
          Back
        </button>
        <button class="button btn btn-primary">Buy Now</button>
      </div>
    </div>
    <div id="sectionTheThreeMistakesOfMyLifeBookDetails">
      <div class="book-details-page">
        <img
          src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/book-chetan-bhagat-img.png"
          class="book-details-page-image"
        />
        <h1 class="book-name">The 3 mistakes of my life</h1>
        <p class="author">by Chetan Bhagat</p>
        <p class="book-description">
          The 3 Mistakes of my life is the third novel written by eminent Indian
          Author Chetan Bhagat. Based on cricket, business and religion, the
          novel is set against the backdrop of beautiful city Ahmedabad.
          Revolving around three young Indian boys Omi, Ishaan and Govind, the
          book goes on to narrate how the three are trying their best to make
          ends meet in the city. Based on real events, the book starts with a
          dramatic twist, where Bhagat is reading an e-mail sent by some young
          person Govind.
        </p>
        <button
          class="button btn btn-warning"
          onclick="display('sectionBookStoreHome')"
        >
          Back
        </button>
        <button class="button btn btn-primary">Buy Now</button>
      </div>
    </div>
    <div id="sectionHarryPotterBookDetails">
      <div class="book-details-page">
        <img
          src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/harrypotter-img.png"
          class="book-details-page-image"
        />
        <h1 class="book-name">Harry Potter</h1>
        <p class="author">by J.K.Rowling</p>
        <p class="book-description">
          Harry Potter's life is miserable. His parents are dead and he's stuck
          with his heartless relatives, who force him to live in a tiny closet
          under the stairs. But his fortune changes when he receives a letter
          that tells him the truth about himself: he's a wizard. A mysterious
          visitor rescues him from his relatives and takes him to his new home,
          Hogwarts School of Witchcraft and Wizardry. After a lifetime of
          bottling up his magical powers, Harry finally feels like a normal kid.
        </p>
        <button
          class="button btn btn-warning"
          onclick="display('sectionBookStoreHome')"
        >
          Back
        </button>
        <button class="button btn btn-primary">Buy Now</button>
      </div>
    </div>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
  </body>
</html>
(CSS)Book Store Page-2


.book-store-home-page {
  background-color: #1b1b1b;
  padding: 24px;
}

.home-page-heading {
  color: #ffffff;
  font-family: "Bree Serif";
  font-size: 28px;
}

.popular-book-container {
  background-color: #e6f6ff;
  border-radius: 8px;
}

.popular-book-image {
  width: 126px;
  height: 180px;
}

.popular-book-short-details-container {
  padding: 16px;
}

.popular-book-heading {
  color: #183b56;
  font-family: "Bree Serif";
  font-size: 16px;
}

.popular-book-text {
  color: #06070d;
  font-family: "Bree Serif";
  font-size: 12px;
}

.popular-book-author {
  color: #183b56;
  font-family: "Bree Serif";
  font-size: 10px;
}

.button {
  font-family: "Roboto";
  font-weight: 500;
  font-size: 12px;
}

.recommended-books-heading {
  color: #ffffff;
  font-family: "Bree Serif";
  font-size: 20px;
  margin-top: 10px;
}

.recommended-book-container {
  margin-bottom: 10px;
}

.recommended-book-image {
  width: 80px;
  height: 125px;
}

.recommended-book-short-details-container {
  margin-left: 10px;
}

.recommended-book-name {
  color: #ffffff;
  font-family: "Bree Serif";
  font-size: 16px;
}

.recommended-book-description {
  color: #e4e7eb;
  font-family: "Bree Serif";
  font-size: 12px;
}

.book-details-page {
  background-color: #1b1b1b;
  padding: 24px;
  text-align: center;
}

.book-details-page-image {
  width: 190px;
  height: 294px;
  margin-bottom: 20px;
}

.book-name {
  color: #ffffff;
  font-family: "Bree Serif";
  font-size: 28px;
}

.author {
  color: #9aa5b1;
  font-family: "Bree Serif";
  font-size: 12px;
}

.book-description {
  text-align: left;
  color: #e4e7eb;
  font-family: "Bree Serif";
  font-size: 12px;
  margin-top: 10px;
}


(HTML)Conference Page-3

<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div id="sectionConferenceHomePage">
      <img
        src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/conference-img.png"
        class="conference-image"
      />
      <div class="conference-text-container">
        <h1 class="conference-title">The Things Conference</h1>
        <p class="conference-description">
          Redefining the future of IoT with LoRaWAN
        </p>
        <button class="btn btn-primary" onclick="display('sectionConferenceDetailsPage')">Know more</button>
      </div>
    </div>
    <div id="sectionConferenceDetailsPage">
      <div class="embed-responsive embed-responsive-16by9">
        <iframe
          class="embed-responsive-item"
          src="https://www.youtube.com/embed/vKJ6nXE_6Hc?rel=0"
          allowfullscreen
        ></iframe>
      </div>
      <div class="conference-text-container">
        <h1 class="conference-details-title">The Things Conference</h1>
        <p class="conference-details-description">
          Join Asia’s Largest Conference on LoRaWAN
        </p>
        <div class="d-flex flex-row justify-content-center">
          <div class="conference-stats-container">
            <h1 class="conference-stats-count">1400+</h1>
            <p class="conference-stats-label">Attendees</p>
          </div>
          <div class="conference-stats-container">
            <h1 class="conference-stats-count">100+</h1>
            <p class="conference-stats-label">Workshops</p>
          </div>
        </div>
        <div class="d-flex flex-row justify-content-center">
          <div class="conference-stats-container">
            <h1 class="conference-stats-count">120+</h1>
            <p class="conference-stats-label">Speakers</p>
          </div>
          <div class="conference-stats-container">
            <h1 class="conference-stats-count">10+</h1>
            <p class="conference-stats-label">Countries</p>
          </div>
        </div>
        <button class="btn btn-primary" onclick="display('sectionConferenceHomePage')">Back</button>
      </div>
    </div>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
  </body>
</html>
(CSS)Conference Page-3

.conference-image {
  width: 100vw;
}

.conference-text-container {
  text-align: center;
  padding: 20px;
}

.conference-title {
  color: #183b56;
  font-family: "Roboto";
  font-weight: bold;
  font-size: 32px;
}

.conference-description {
  color: #5a7184;
  font-family: "Roboto";
  font-size: 16px;
  padding: 10px;
}

.conference-details-title {
  color: #183b56;
  font-family: "Roboto";
  font-size: 24px;
  font-weight: bold;
}

.conference-details-description {
  color: #5a7184;
  font-family: "Roboto";
  font-size: 16px;
}

.conference-stats-container {
  margin-left: 30px;
  margin-right: 30px;
  margin-top: 10px;
  margin-bottom: 10px;
}

.conference-stats-count {
  color: #183b56;
  font-family: "Roboto";
  font-size: 24px;
  font-weight: bold;
}

.conference-stats-label {
  color: #5a7184;
  font-family: "Roboto";
  font-size: 16px;
}
(HTML)GOA PAGE

 (HTML)Advanced Technologies Cover Page-1
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div class="bg-container d-flex flex-column justify-content-end">
      <div class="advanced-technologies-card">
        <h1 class="advanced-technologies-title">Advanced Technologies</h1>
        <p class="advanced-technologies-description">
          Machinery and equipment developed from the application of scientific
          knowledge.
        </p>
        <button class="learn-more-button">Learn more</button>
        <button class="save-draft-button">Save Draft</button>
      </div>
    </div>
  </body>
</html>
(CSS)Advanced Technologies Cover Page-1

.bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/arvrbg.png");
  height: 100vh;
  background-size: cover;
}
.advanced-technologies-card {
  background-color: #ffffff;
  border-top-left-radius: 16px;
  border-top-right-radius: 16px;
  padding: 25px;
}
.advanced-technologies-title {
  color: #5752ab;
  font-family: "Bree Serif";
  font-size: 24px;
}
.advanced-technologies-description {
  color: #323f4b;
  font-family: "Roboto";
}
.learn-more-button {
  color: #171f46;
  background-color: #ffffff;
  font-family: "Roboto";
  font-size: 12px;
  font-weight: 500;
  width: 126px;
  height: 38px;
  border-style: solid;
  border-width: 1px;
  border-color: #d7dfe9;
  border-radius: 8px;
  margin-right: 5px;
}
.save-draft-button {
  color: #ffffff;
  background-color: #5752ab;
  font-family: "Roboto";
  font-size: 12px;
  font-weight: 500;
  width: 126px;
  height: 38px;
  border-width: 0px;
  border-radius: 8px;
  margin-left: 5px;
}



Celebrate Diwali Project HTML-2

<!DOCTYPE html>
<html>
  <head>
   <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBn+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div class="diwali-top-section">
      <h1 class="diwali-top-section-heading">
        Celebrate Diwali with your friends
      </h1>
    </div>
    <div class="diwali-bottom-section">
      <div class="d-flex flex-row justify-content-center">
        <div class="diwali-card-item">
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/lamp-img.png"
            class="diwali-card-image"
          />
          <h1 class="diwali-card-name">Diwali Air Balloon</h1>
          <p class="diwali-card-price">Rs 369</p>
        </div>

        <div class="diwali-card-item">
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/diya-img.png"
            class="diwali-card-image"
          />
          <h1 class="diwali-card-name">Diwali - Lamp</h1>
          <p class="diwali-card-price">Rs 50</p>
        </div>
      </div>
      <div class="d-flex flex-row justify-content-center">
        <div class="diwali-card-item">
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/firework-img.png"
            class="diwali-card-image"
          />
          <h1 class="diwali-card-name">Sparklers</h1>
          <p class="diwali-card-price">Rs 150</p>
        </div>

        <div class="diwali-card-item">
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/firecracker-img.png"
            class="diwali-card-image"
          />
          <h1 class="diwali-card-name">Fire Cracker</h1>
          <p class="diwali-card-price">Rs 560</p>
        </div>
      </div>
      <button class="btn btn-primary">View More</button>
    </div>
  </body>
</html>

Celebrate Diwali Project CSS-2

.diwali-top-section {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/diwali-bg.png");
  height: 30vh;
  background-size: cover;
}
.diwali-top-section-heading {
  color: white;
  font-family: "Caveat";
  font-size: 36px;
  width: 200px;
  padding: 20px;
}
.diwali-bottom-section {
  text-align:center;
  background-color: #e6f6ff;
  padding:15px;
}
.diwali-card-item {
  text-align: center;
  background-color: white;
  width:140px;
  border-radius: 9px;
  padding: 16px;
  margin: 15px;
}
.diwali-card-image {
  height: 64px;
  width: 64px;
}
.diwali-card-name {
  color: #616e7c;
  font-family: "Roboto";
  font-size: 12px;
  font-weight: normal;
}
.diwali-card-price {
  color: #323f4b;
  font-family: "Roboto";
  font-size: 16px;
  font-weight: 500;
}
(HTML)News Page-3
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div class="bg-container d-flex flex-column justify-content-end">
      <div class="news-card">
        <p class="news-category">NEWS OF THE DAY</p>
        <h1 class="news-title">
          iB Cricket announces world's first Virtual Reality Cricket League
        </h1>
        <p class="news-description">
          iB Cricket and Viu together have announced the World's first virtual
          reality cricket league featuring 12 international cricketers, who will
          be competing against each other for the iB Cricket Super Over League
          title in Mumbai. Iconic cricketers like Virender Sehwag, Suresh Raina,
          Brendon McCullum will be competing in the league.
        </p>
        <button class="button">Read more</button>
      </div>
    </div>
  </body>
</html>
(CSS)News Page-3
.bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/newsbg.png");
  height: 100vh;
  background-size: cover;
}
.news-card {
  background-color: #ffffff;
  border-top-left-radius: 16px;
  border-top-right-radius: 16px;
  padding: 25px;
}
.news-category {
  color: #7b8794;
  font-family: "Roboto";
  font-size: 12px;
}
.news-title {
  color: #323f4b;
  font-family: "Roboto";
  font-size: 18px;
  font-weight: 500;
  margin-bottom: 15px;
}
.news-description {
  color: #7b8794;
  font-family: "Roboto";
  font-size: 12px;
}
.button {
  color: #ffffff;
  background-color: #323f4b;
  font-family: "Roboto";
  font-size: 12px;
  font-weight: 500;
  width: 109px;
  height: 38px;
  border-width: 0px;
  border-radius: 8px;
}


(HTML)My Project -1 (CSS)

<html>
  <head>	
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div id="sectionMyProjectsHome">
      <div class="my-projects-home-page">
        <img
          src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/software-developer-img.png"
          class="software-developer-image"
        />
        <h1 class="my-projects-heading">My Projects</h1>
        <p class="my-projects-description">
          These are a few of my Static Website projects that I have developed
          using HTML, CSS and Bootstrap
        </p>
        <div class="d-flex flex-row justify-content-center">
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/advanced-technologies-img.png"
            class="my-project-image"
            onclick="display('sectionAdvancedTechnologies')"
          />
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/diwali-img.png"
            class="my-project-image"
            onclick="display('sectionDiwali')"
          />
        </div>
        <div class="d-flex flex-row justify-content-center">
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/food-img.png"
            class="my-project-image"
            onclick="display('sectionFoodOrder')"
          />
          <img
            src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/news-paper-img.png"
            class="my-project-image"
            onclick="display('sectionNews')"
          />
        </div>
      </div>
    </div>
    <div id="sectionAdvancedTechnologies">
      <div
        class="advanced-technologies-bg-container d-flex flex-column justify-content-end"
      >
        <div class="advanced-technologies-card">
          <h1 class="advanced-technologies-title">Advanced Technologies</h1>
          <p class="advanced-technologies-description">
            Machinery and equipment developed from the application of scientific
            knowledge.
          </p>
          <button class="advanced-technologies-learn-more-button">
            Learn more
          </button>
          <button
            class="btn btn-primary"
            onclick="display('sectionMyProjectsHome')"
          >
            Back
          </button>
        </div>
      </div>
    </div>
    <div id="sectionDiwali">
      <div class="diwali-top-section">
        <h1 class="diwali-top-section-heading">
          Celebrate Diwali with your friends
        </h1>
      </div>
      <div class="diwali-bottom-section">
        <div class="d-flex flex-row justify-content-center">
          <div class="diwali-card-item">
            <img
              src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/lamp-img.png"
              class="diwali-card-image"
            />
            <h1 class="diwali-card-name">Diwali Air Balloon</h1>
            <p class="diwali-card-price">Rs 369</p>
          </div>
          <div class="diwali-card-item">
            <img
              src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/diya-img.png"
              class="diwali-card-image"
            />
            <h1 class="diwali-card-name">Diwali - Lamp</h1>
            <p class="diwali-card-price">Rs 50</p>
          </div>
        </div>
        <div class="d-flex flex-row justify-content-center">
          <div class="diwali-card-item">
            <img
              src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/firework-img.png"
              class="diwali-card-image"
            />
            <h1 class="diwali-card-name">Sparklers</h1>
            <p class="diwali-card-price">Rs 150</p>
          </div>
          <div class="diwali-card-item">
            <img
              src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/firecracker-img.png"
              class="diwali-card-image"
            />
            <h1 class="diwali-card-name">Fire Cracker</h1>
            <p class="diwali-card-price">Rs 560</p>
          </div>
        </div>
        <div class="d-flex flex-row justify-content-center">
          <button
            class="btn btn-primary"
            onclick="display('sectionMyProjectsHome')"
          >
            Back
          </button>
        </div>
      </div>
    </div>
    <div id="sectionFoodOrder">
      <div
        class="food-order-bg-container d-flex flex-column justify-content-end"
      >
        <div class="order-card">
          <h1 class="order-card-heading">Happy Meals</h1>
          <p class="order-card-paragraph">
            Discover the best foods over the 1,000 restaurants
          </p>
          <button class="order-card-button">Book Now</button>
          <button
            class="btn btn-primary"
            onclick="display('sectionMyProjectsHome')"
          >
            Back
          </button>
        </div>
      </div>
    </div>
    <div id="sectionNews">
      <div class="news-bg-container d-flex flex-column justify-content-end">
        <div class="news-card">
          <p class="news-category">NEWS OF THE DAY</p>
          <h1 class="news-title">
            All educational institutions in Assam to reopen from November 2
          </h1>
          <p class="news-description">
            Uttar Pradesh's Gautam Buddh Nagar recorded 107 new Covid-19 cases
            on Saturday, pushing the district's infection tally to 15,803,
            official data showed. The number of active cases came down further
            to 1,384 from 1,477 on Friday and 1,523 on Thursday, according to
            the data released by the UP Health Department for a 24-hour period.
          </p>
          <button class="news-button">Read more</button>
          <button
            class="btn btn-primary"
            onclick="display('sectionMyProjectsHome')"
          >
            Back
          </button>
        </div>
      </div>
    </div>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
  </body>
</html>
MY Project-1
.my-projects-home-page {
  text-align: center;
  padding: 15px;
}

.software-developer-image {
  width: 80vw;
}

.my-projects-heading {
  color: #183b56;
  font-family: "Bree Serif";
  font-size: 24px;
}

.my-projects-description {
  color: #616e7c;
  font-family: "Bree Serif";
  font-size: 12px;
}

.my-project-image {
  width: 160px;
  height: 90px;
  margin: 5px;
}

.advanced-technologies-bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/arvrbg.png");
  height: 100vh;
  background-size: cover;
}

.advanced-technologies-card {
  background-color: #ffffff;
  border-top-left-radius: 16px;
  border-top-right-radius: 16px;
  padding: 25px;
}

.advanced-technologies-title {
  color: #5752ab;
  font-family: "Bree Serif";
  font-size: 24px;
}

.advanced-technologies-description {
  color: #323f4b;
  font-family: "Roboto";
}

.advanced-technologies-learn-more-button {
  color: #171f46;
  background-color: #ffffff;
  font-family: "Roboto";
  font-size: 12px;
  font-weight: 500;
  width: 126px;
  height: 38px;
  border-style: solid;
  border-width: 1px;
  border-color: #d7dfe9;
  border-radius: 8px;
  margin-right: 5px;
}

.advanced-technologies-save-draft-button {
  color: #ffffff;
  background-color: #5752ab;
  font-family: "Roboto";
  font-size: 12px;
  font-weight: 500;
  width: 126px;
  height: 38px;
  border-width: 0px;
  border-radius: 8px;
  margin-left: 5px;
}

.diwali-top-section {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/diwali-bg.png");
  height: 30vh;
  background-size: cover;
}

.diwali-top-section-heading {
  color: #ffffff;
  font-family: "Caveat";
  font-size: 36px;
  width: 200px;
  padding: 20px;
}

.diwali-bottom-section {
  text-align: center;
  background-color: #e6f6ff;
  padding: 15px;
}

.diwali-card-item {
  text-align: center;
  background-color: #ffffff;
  width: 140px;
  border-radius: 9px;
  padding: 16px;
  margin: 15px;
}

.diwali-card-image {
  height: 64px;
  width: 64px;
}

.diwali-card-name {
  color: #616e7c;
  font-family: "Roboto";
  font-size: 12px;
  font-weight: normal;
}

.diwali-card-price {
  color: #323f4b;
  font-family: "Roboto";
  font-size: 16px;
  font-weight: 500;
}

.food-order-bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/foodbg.png");
  height: 100vh;
  background-size: cover;
}

.order-card {
  background-color: #f6c56e;
  border-top-left-radius: 16px;
  border-top-right-radius: 16px;
  padding: 24px;
}

.order-card-heading {
  color: #323f4b;
  font-family: "Bree Serif";
  font-size: 30px;
}

.order-card-paragraph {
  color: #323f4b;
  font-family: "Roboto";
  font-size: 16px;
  font-weight: bold;
}

.order-card-button {
  background-color: #ffffff;
  font-family: "Roboto";
  font-size: 12px;
  font-weight: 500;
  width: 120px;
  height: 38px;
  border-width: 0px;
  border-radius: 8px;
}

.news-bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/newsbg.png");
  height: 100vh;
  background-size: cover;
}

.news-card {
  background-color: #ffffff;
  border-top-left-radius: 16px;
  border-top-right-radius: 16px;
  padding: 25px;
}

.news-category {
  color: #7b8794;
  font-family: "Roboto";
  font-size: 12px;
}

.news-title {
  color: #323f4b;
  font-family: "Roboto";
  font-size: 18px;
  font-weight: 500;
  margin-bottom: 15px;
}

.news-description {
  color: #7b8794;
  font-family: "Roboto";
  font-size: 12px;
}

.news-button {
  color: #ffffff;
  background-color: #323f4b;
  font-family: "Roboto";
  font-size: 12px;
  font-weight: 500;
  width: 109px;
  height: 38px;
  border-width: 0px;
  border-radius: 8px;
}
