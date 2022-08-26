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


CSS:



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
