<template>
    <!--<v-parallax src="https://cdn.vuetifyjs.com/images/parallax/material.jpg">-->
    <v-parallax>

      <video autoplay muted loop id="myVideo">
        <source src="../assets/intro.mp4" type="video/mp4">
      </video>

      <div class="content">

        <h1 class="intro">I am <span>Abiodun Adedapo </span><br>
          <a href="" class="typewrite" data-period="2000" data-type='[ "Hi, Im Abeyjoe.", "I am Creative.", "I Love Design.", "I Love to Develop." ]'>
            <span class="wrap"></span>
          </a>

        </h1>
      </div>


    </v-parallax> 
      

    <!-- <v-banner>Marquee Slide Here</v-banner> -->

</template>


<script>
var TxtType = function(el, toRotate, period) {
        this.toRotate = toRotate;
        this.el = el;
        this.loopNum = 0;
        this.period = parseInt(period, 10) || 2000;
        this.txt = '';
        this.tick();
        this.isDeleting = false;
    };

    TxtType.prototype.tick = function() {
        var i = this.loopNum % this.toRotate.length;
        var fullTxt = this.toRotate[i];

        if (this.isDeleting) {
        this.txt = fullTxt.substring(0, this.txt.length - 1);
        } else {
        this.txt = fullTxt.substring(0, this.txt.length + 1);
        }

        this.el.innerHTML = '<span class="wrap">'+this.txt+'</span>';

        var that = this;
        var delta = 200 - Math.random() * 100;

        if (this.isDeleting) { delta /= 2; }

        if (!this.isDeleting && this.txt === fullTxt) {
        delta = this.period;
        this.isDeleting = true;
        } else if (this.isDeleting && this.txt === '') {
        this.isDeleting = false;
        this.loopNum++;
        delta = 500;
        }

        setTimeout(function() {
        that.tick();
        }, delta);
    };

    window.onload = function() {
        var elements = document.getElementsByClassName('typewrite');
        for (var i=0; i<elements.length; i++) {
            var toRotate = elements[i].getAttribute('data-type');
            var period = elements[i].getAttribute('data-period');
            if (toRotate) {
              new TxtType(elements[i], JSON.parse(toRotate), period);
            }
        }
        // INJECT CSS
        var css = document.createElement("style");
        css.type = "text/css";
        css.innerHTML = ".typewrite > .wrap { border-right: 0.08em solid #fff}";
        document.body.appendChild(css);
    };
</script>


<style scoped>
h1 {
    margin: auto;
    text-align: center;
    padding-top: 35px;
}
     CSS JS 

    Result
    Skip Results Iframe

EDIT ON

body {
  /*background-color:#ce3635;*/
  text-align: center;
  /*color:#fff;*/
  padding-top:10em;
}

/* * { color:#fff; text-decoration: none;} */
* { colortext-decoration: none;}

#myVideo {
  /* position: fixed; */
  /* right:0; */
  /* buttom:0; */
  min-width:100%;
  min-height:100%;
  max-width:100%;
  max-height:100%;
}
.content {
/*   position: fixed; */
/*   top:0; */
/*   margin-top:150px; */

     margin-top:-330px;  
     margin-bottom:150px;

/*   left:0; */
/*   right:0; */
/*   background: rgb(0, 0, 0, 0.5); */
/*   color: #f1f1f1; */
/*   width:100%; */
   padding:20px; 
}

h1.intro { color: #fff; }
span { color: orange; }

a {
   text-decoration:none;
   color: skyblue; 
}
</style>
