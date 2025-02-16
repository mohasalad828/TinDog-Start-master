body{
  font-family: "Montserrat";
}

#title{
  background-color: #ff4c68;
  color: #fff;
}
h1{
  font-family: 'Montserrat', sans-serif;
  font-weight: 900;
  font-size: 3.5rem;
  line-height: 1.5;
}



.container-fluid{
  padding: 3% 15% 7%;
}

/* Navigation bar */

.navbar{
  padding: 0 0 4.5rem;
}
.navbar-brand{
  font-family: "Ubuntu";
  font-size: 2.5rem;
}
.nav-item{
  padding: 0 18px;
}
.nav-link{
  font-family:'Montserrat', sans-serif;
  font-weight: 500;
  font-size: 1.2rem;
}
/* Download Buttons */
.download-button{
  margin: 5% 3% 5% 0;
}

/* Title Image */
/* #phone{
  -webkit-transform: rotate(30deg);
  -moz-transform: rotate(30deg);
  -o-transform: rotate(30deg);
  -ms-transform: rotate(30deg);
  transform: rotate(30deg);
} */
.title-image{
  width: 22%;
  transform: rotate(25deg);
  position: absolute;
  right: 20%;
}


/* Features */

h3{
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;
  font-size: 1.3rem;
}

#features{
  padding: 7% 15%;
  background-color: #fff;
  position: relative;
  z-index: 1;
}
.feature-box{
  text-align: center;
  padding: 5%;
}

/* .description{
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;
  font-size: 1.5rem;
} */
p{
  color: #8f8f8f;
}

.icon{
  color: #ef8172;
  margin-bottom: 1rem;
}
.icon:hover{
  color: #ff4c68;
}

/* Testimonials */

#testimonials{
  text-align: center;
  background-color: #ef8172;
  color: #fff;

}
h2{
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;
  font-size: 3rem;
  line-height: 1.5;
}
.testimonial-image{
  width: 10%;
  border-radius: 100%;
  margin: 20px;
}
/* Press */
#press{
  background-color: #ef8172;
  text-align: center;
  padding-bottom: 3%;
}
.press-logo{
  width: 15%;
  margin: 20px 20px 50px;
}
.carousel-item{
  padding: 7% 15%;
}

/* Pricing Section */

#pricing{
  padding: 6.25rem;
  text-align: center;
}
.pricing-column{
  padding: 3% 2%;

}

@media (max-width: 1028px){
  #title{
    text-align: center;
  }

  .title-image{
    position: static;
    transform: rotate(0);
    width: 60%;
  }
  
}


/* Custumizeed CSS style card sizes and price */
.card-size{
  height: 26rem;
  width: 22rem;
}
.price{
  font-family: 'Montserrat', sans-serif;
  font-weight: 500;
  font-size: 2rem;
  line-height: 1.5;
}
/* Custumizeed CSS style card sizes and price */


/* Call to Action Section */

#cta{
  background-color: #ff4c68;
  color: #fff;
  padding: 7% 15%;
  text-align: center;


}
.cta-headings{
  font-family: 'Montserrat', sans-serif;
font-weight: 900;
  font-size: 3.5rem;
  line-height: 1.5;
}

/* Footer Section */

#footer{
  background-color: #fff;
  text-align: center;
  padding: 7% 15%;
}

.social-icon{
  margin: 0 1% 2%;
}

#myBtn {
  display: flex; /* Hidden by default */
  position: fixed; /* Fixed/sticky position */
  bottom: 20px; /* Place the button at the bottom of the page */
  right: 30px; /* Place the button 30px from the right */
  z-index: 99; /* Make sure it does not overlap */
  border: #fff solid; /* Remove borders */
  outline: none; /* Remove outline */
  background-color: #ff4c68; /* Set a background color */
  color: white; /* Text color */
  cursor: pointer; /* Add a mouse pointer on hover */
  padding: 10px; /* Some padding */
  border-radius: 10px; /* Rounded corners */
  font-size: 18px; /* Increase font size */
}

#myBtn:hover {
  background-color: #16b1e5; /* Add a dark-grey background on hover */
}