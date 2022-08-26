# htmlcssprojects1

1.(HTML)TOURISM :


<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div id="sectionHome">
      <div class="bg-container d-flex flex-column justify-content-end">
        <div class="tourism-card">
          <h1 class="main-heading">Tourism</h1>
          <p class="paragraph">Plan your trip.</p>
          <button class="button" onclick="display('sectionFavouritePlaces')">Get Started</button>
        </div>
      </div>
    </div>
    <div id="sectionFavouritePlaces">
      <div class="favourite-places-bg-container">
       <h1 class="favourite-places-heading">Favourite Places</h1>
       <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionTajMahalDetailedView')">
         <div>
           <h1 class="favourite-place-card-heading">Taj Mahal</h1>
           <p class="favourite-place-card-description">
             If there was just one symbol to represent all of India, it would be the
             Taj Mahal
           </p>
         </div>
         <img
           src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png"
           class="favourite-place-card-image"
         />
       </div>
       <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionGoldenTempleDetailedView')">
         <div>
           <h1 class="favourite-place-card-heading">Golden Temple</h1>
           <p class="favourite-place-card-description">
             Amritsar is world-famous for the beautiful and highly revered Golden
             Temple
           </p>
         </div>
         <img
           src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/golden-temple-img.png"
           class="favourite-place-card-image"
         />
       </div>
       <div class="favourite-place-card-container d-flex flex-row">
         <div>
           <h1 class="favourite-place-card-heading">Mysore Palace</h1>
           <p class="favourite-place-card-description">
             The Mysore Palace is a historical palace and the royal residence at
             Mysore .
           </p>
         </div>
         <img
           src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace-img.png"
           class="favourite-place-card-image"
         />
       </div>
       <div class="favourite-place-card-container d-flex flex-row">
         <div>
           <h1 class="favourite-place-card-heading">Varanasi Temple</h1>
           <p class="favourite-place-card-description">
             Varanasi Temple is most famous Hindu temples dedicated to Lord Shiva
           </p>
         </div>
         <img
           src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi-temple-img.png"
           class="favourite-place-card-image"
         />
       </div>
       <button class="btn btn-dark" onclick="display('sectionHome')">back</button>
      </div>
    </div>
    <div id="sectionTajMahalDetailedView">
      <div class="detailed-view-bg-container">
        <h1 class="detailed-view-heading">Detailed View</h1>
        <div class="detailed-view-card-container">
          <div id="carouselExampleIndicators1" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
              <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
              <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
              <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img
                  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c1-img.png"
                  class="d-block w-100"
                  alt="..."
                />
              </div>
              <div class="carousel-item">
                <img
                  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c2-img.png"
                  class="d-block w-100"
                  alt="..."
                />
              </div>
              <div class="carousel-item">
                <img
                  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c3-img.png"
                  class="d-block w-100"
                  alt="..."
                />
              </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleIndicators1" role="button" data-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleIndicators1" role="button" data-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="sr-only">Next</span>
            </a>
          </div>
          <div class="detailed-view-card-text-container">
            <h1 class="detailed-view-card-heading">Taj Mahal</h1>
            <p class="detailed-view-card-description">
              The Taj Mahal is considered to be the greatest architectural achievement
              in the whole range of Indo-Islamic architecture. Its recognised
              architectonic beauty has a rhythmic combination of solids and voids,
              concave and convex and light shadow; such as arches and domes further
              increases the aesthetic aspect. Not a piece of architecture, as other
              buildings are, but the proud passions of an emperor’s love wrought in
              living stones.
            </p>
          </div>
        </div>
        <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
          back
        </button>
      </div>
    </div>
    <div id="sectionGoldenTempleDetailedView">
      <div class="detailed-view-bg-container">
        <h1 class="detailed-view-heading">Detailed View</h1>
        <div class="detailed-view-card-container">
          <div id="goldenTempleCarousel" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
              <li data-target="#goldenTempleCarousel" data-slide-to="0" class="active"></li>
              <li data-target="#goldenTempleCarousel" data-slide-to="1"></li>
              <li data-target="#goldenTempleCarousel" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple1-img.png" class="d-block w-100" alt="..." />
              </div>
              <div class="carousel-item">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple2-img.png" class="d-block w-100" alt="..." />
              </div>
              <div class="carousel-item">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple3-img.png" class="d-block w-100" alt="..." />
              </div>
            </div>
            <a class="carousel-control-prev" href="#goldenTempleCarousel" role="button" data-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#goldenTempleCarousel" role="button" data-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="sr-only">Next</span>
            </a>
          </div>
          <div class="detailed-view-card-text-container">
            <h1 class="detailed-view-card-heading">Golden Temple</h1>
            <p class="detailed-view-card-description">
              The Golden Temple, also known as Harmandir Sahib is a gurdwara
              located in the city of Amritsar, Punjab, India. There are many
              places to visit Near Golden Temple.
            </p>
            <ol class="detailed-view-card-description">
              <li>Jallianwala Bagh</li>
              <li>Wagah Border</li>
              <li>Harike Wetland</li>
              <li>Bathinda Fort</li>
            </ol>
          </div>
        </div>
        <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
          back
        </button>
      </div>
    </div>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
  </body>
</html>


1. (CSS)TOURISM :

  
.bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
  height: 100vh;
  background-size: cover;
}
.tourism-card {
  text-align: center;
  background-color: white;
  border-top-left-radius: 25px;
  border-top-right-radius: 25px;
  padding: 5px;
}
.button {
  color: white;
  background-color: #25b1cc;
  width: 138px;
  height: 36px;
  border-width: 0px;
  border-radius: 20px;
}
.main-heading {
  font-family: "Roboto";
}
.paragraph {
  font-family: "Roboto";
}
.favourite-places-bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/towerbg.png");
  height: 100vh;
  background-size: cover;
  padding: 24px;
}
.favourite-places-heading {
  color: white;
  font-family: "Roboto";
  font-size: 28px;
  font-weight: bold;
}
.favourite-place-card-container {
  background-color: white;
  border-radius: 8px;
  padding: 16px;
  margin-bottom: 15px;
}
.favourite-place-card-heading {
  color: #0f0e46;
  font-family: "Roboto";
  font-size: 23px;
  font-weight: bold;
}
.favourite-place-card-description {
  color: #6c6b70;
  font-family: "Roboto";
  font-size: 13px;
}
.favourite-place-card-image {
  width: 80px;
  height: 100px;
}
.favourite-place-card-text-container {
  margin-right: 15px;
}
.detailed-view-bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/seabg.png");
  height: 100vh;
  background-size: cover;
}
.detailed-view-heading {
  color: white;
  font-family: "Roboto";
  font-size: 28px;
  font-weight: bold;
  padding: 24px;
}
.detailed-view-card-container {
  background-color: white;
  border-bottom-right-radius: 8px;
  border-bottom-left-radius: 8px;
  margin: 24px;
}
.detailed-view-card-heading {
  color: #0f0e46;
  font-family: "Roboto";
  font-size: 23px;
  font-weight: bold;
}
.detailed-view-card-description {
  color: #6c6b70;
  font-family: "Roboto";
  font-size: 13px;
}
.detailed-view-card-text-container {
  padding: 16px;
}
 

 
2. (HTML) Advance techology, Diwali and news page :


<html>
 <head>
 <link rel="stylesheet" 
href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" 
integrity="sha384-
JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" 
crossorigin="anonymous">
 <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-
DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" 
crossorigin="anonymous"></script>
 <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" 
integrity="sha384-
9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" 
crossorigin="anonymous"></script>
 <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" 
integrity="sha384-
B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" 
crossorigin="anonymous"></script>
 </head>
 <body>
 <div id="sectionMyProjectsHome">
 <div class="my-projects-home-page">
 <img
 src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/software-developerimg.png"
 class="software-developer-image"
 />
 <h1 class="my-projects-heading">My Projects</h1>
 <p class="my-projects-description">
 These are a few of my Static Website projects that I have developed
 using HTML, CSS and Bootstrap
 </p>
 <div class="d-flex flex-row justify-content-center">
 <img
 src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/advancedtechnologies-img.png"
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
 src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/firecrackerimg.png"
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
 <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-staticwebsite/js/ccbp-ui-kit.js"></script>
 </body>
</html>
 

2. (CSS) Advance techology, Diwali and news page :
