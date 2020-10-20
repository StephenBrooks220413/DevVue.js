<template>
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <div id="carouselExampleIndicators" class="carousel slide content-1" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
      </ol>
      <div class="carousel-inner text-center">
        <div class="carousel-item active">
          <h1>Collaborative Work</h1>
          <p>
            Jaira Integrations <br>
            Github Repositories <br>
            Microsoft Teams
          </p>
        </div>
        <div class="carousel-item">
          <h1>Site Layouts</h1>
          <p>
            Vue.js and Sass <br>
            Bootstrap libraries <br>
            JavaScript for Logic
          </p>
        </div>
        <div class="carousel-item">
          <h1>Ready Templates</h1>
          <p>
            Scalable Designs <br>
            Fast Load Times <br>
            Friendly and Secure
          </p>
        </div>
      </div>
      <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  <div class="container nav-wrapper">
    <div class="row">
      <div class="col-md-4 text-center" style="margin-top:20px;">
        <h3><span>F</span>ront End</h3>
        Using Vue.js and Bootstrap CDN to style and deliver content
      </div>
      <div class="col-md-4 text-center" style="margin-top:20px;">
        <h3><span>B</span>ack End</h3>
        Using Node.js and JSON files for data calls and changes
      </div>
      <div class="col-md-4 text-center" style="margin-top:20px;">
        <h3><span>F</span>ull Stack</h3>
        Full stack javascript developer with React, Vue, Angular
      </div>
    </div>
  </div>

  <article itemprop="article-section">
     <div class="jumbotron" style="margin-top:110px; margin-bottom:110px;">
        <div class="container">
          <p style="float:right; color:#cea135;">
            total: <i class="fas fa-shopping-cart" onclick="shop();" id="cart">$0</i>
          </p>
            <h1 class="text-center display-4">Pricing Cards</h1>
            <div class="row">
                <div class="col-md-4 text-center" style="margin-top:30px;">
                    <div class="card">
                        <img src="https://images.unsplash.com/photo-1496171367470-9ed9a91ea931?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" alt="Denim Jeans" style="width:100%">
                        <h1>Static</h1>
                        <p class="price">$549.99</p>
                        <p>Beautiful layouts and logic content for all devices</p>
                        <p><button class="btn btn-info" id="static">Add to Cart</button></p>
                    </div>
                </div>
                <div class="col-md-4 text-center" style="margin-top:30px;">
                    <div class="card">
                        <img src="https://images.unsplash.com/photo-1483058712412-4245e9b90334?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" alt="Denim Jeans" style="width:100%">
                        <h1>Interactive</h1>
                        <p class="price">$1099.99</p>
                        <p>Responsive content and form submissions</p>
                        <p><button class="btn btn-info" id="interactive">Add to Cart</button></p>
                    </div>
                </div>
                <div class="col-md-4 text-center" style="margin-top:30px;">
                    <div class="card">
                        <img src="https://images.unsplash.com/photo-1499951360447-b19be8fe80f5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" alt="Denim Jeans" style="width:100%">
                        <h1>Full-load</h1>
                        <p class="price">$1359.99</p>
                        <p>Including images, calendar and selling tools</p>
                        <p><button class="btn btn-info" id="full">Add to Cart</button></p>
                      </div>
                </div>
            </div>
        </div>
    </div>
  </article>
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <!-- image carousel -->
          <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel" style="margin-top:90px; margin-bottom:90px;">
          <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
          </ol>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="https://images.unsplash.com/photo-1550751827-4bd374c3f58b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" class="d-block w-100" alt="...">
          
            </div>
            <div class="carousel-item">
              <img src="https://images.unsplash.com/photo-1548092372-0d1bd40894a3?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" class="d-block w-100" alt="...">
              
            </div>
            <div class="carousel-item">
              <img src="https://images.unsplash.com/photo-1558002038-1055907df827?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" class="d-block w-100" alt="...">
              
            </div>
          </div>
          <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
    </div>
  </div>
  <!-- Recent Projects -->
  <div class="container" style="margin-top:180px; margin-bottom:180px;">
    <h1 class="display-4 text-center">Recent Projects</h1> 
    <br> <br>
    <div class="row">
      <div class="col-sm-4">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Dramacide Kennel</h5>
            <img src="https://images.unsplash.com/photo-1518717758536-85ae29035b6d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" width="100%" alt="dog">
            <a href="https://dramacide.net" target="_blank" class="btn btn-primary">See Preview</a>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Hair Clinic</h5>
            <img src="https://images.unsplash.com/photo-1546060432-b90a6441048f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" width="100%" alt="dog">
            <a href="https://innovation-hair-clinic.net" target="_blank" class="btn btn-primary">See Preview</a>
          </div>
        </div>
      </div>
      <div class="col-sm-4">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Brooks Insurance</h5>
            <img src="https://images.unsplash.com/photo-1450101499163-c8848c66ca85?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80" width="100%" alt="dog">
            <a href="https://brookslifeagency.net" target="_blank" class="btn btn-primary">See Preview</a>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- contact form -->
  <div class="container">
    <div class="row">
      <div class="col-md-6 text-center" style="margin-top:90px;">
        <h4>"Let's Build Something Together."</h4>
        <br>  
        <img src="https://images.unsplash.com/photo-1487014679447-9f8336841d58?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1466&q=80" width="100%" alt="">
      </div>
      <div class="col-md-6 text-center message-content">
        <hr>
        <h2>Send A Message</h2>
        <form action="">
          <label for="name">Full Name</label> <br> <input type="text" required> <br>
          <label for="email">Your Email</label> <br> <input type="email" required> <br>
          <label for="message">Message</label> <br> <textarea name="message" id="" cols="20" rows="3" required></textarea> <br>
          <button type="submit" class="btn btn-outline-success">send</button> <button type="submit" class="btn btn-outline-danger">reset</button>
        </form>
        <hr>
      </div>
    </div>
  </div>
  <!-- footer -->
  <footer>
    <hr style="border:1px bevel grey;">
    <div class="container">
      <div class="row text-center">
        <div class="col-md-4" style="margin-top:10px;">
          <p>
            WebDevelopers Inc. <br>
            1131 Main St
            Phoenix Arizona <br>
            555-555-5555 <br>
            www.developing4life.com
          </p>
        </div>
        <div class="col-md-4" style="margin-top:30px;">
          <h3>Menu</h3>
          <nav>
            <a href="#">home</a> | <a href="#">about</a> | <a href="#">contact</a>
          </nav>
        </div>
        <div class="col-md-4">
          <h3>Developer Contact</h3>
          <img src="https://images.unsplash.com/photo-1550439062-609e1531270e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60" width="70px" height="60px" alt="developer"> <br>
          <p>
            Call: <a href="tel:580-309-0236"><i class="fas fa-phone"></i></a> 
            | 
            Message: <a href="mailto:stephen.brooks220413@gmail.com"><i class="fas fa-envelope"></i></a> 
          </p>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0;
  width: 100%;
}
.nav-wrapper {
  margin-top: 130px;
  margin-bottom: 130px;
}
.nav-wrapper h3 {
  font-weight: bold;
}
.nav-wrapper h3 span {
  color:red;
}
.content-block {
    background: url(https://images.unsplash.com/photo-1451187580459-43490279c0fa?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1052&q=80) no-repeat center center; 
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    height: 90vh;
    margin-top:20px;
    margin-bottom: 20px;
    width: 100%;
}

/* top carousel */
.content-1 {
    background: url(https://images.unsplash.com/photo-1451187580459-43490279c0fa?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1052&q=80) no-repeat center center; 
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    height: 60vh;
    margin-top:0;
    margin-bottom: 60px;
    width: 100%;
    color: white;
    padding-top:90px;
}
/* end of carousel */
.content-box {
    background: url(https://images.unsplash.com/photo-1472289065668-ce650ac443d2?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80) no-repeat center center; 
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    height: 60vh;
    margin-top:0;
    margin-bottom: 60px;
    width: 100%;
}
.message-content {
    margin-top:60px;
    margin-bottom:60px;
  }
/* Projects Section */
/* End Projects section */
footer {
  margin-top:30px;
  line-height: 30px;
  margin-bottom:30px;
}
</style>

