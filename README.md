
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Desire for wealth in the era of FinTech">
    <meta name="author" content="Ricardo Miranda Zuniga">

    <title>FinTech for the Precariat</title>

    <style>
      /* Slideshow CSS
      https://www.w3schools.com/howto/howto_js_slideshow.asp */
          .mySlides {
            display: none;
          }
          img {
            vertical-align: middle;
          }

          /* Slideshow container */
          .slideshow-container {
            /*width: 100%; play with scale to alter layout*/
            margin: auto; /*centers the content*/
            /* try playing with placement:
            float: left;
            float: right;
            */

          /* Vanilla JS Draggable Div
          https://www.w3schools.com/howto/howto_js_draggable.asp */
#mydiv {
  position: absolute;
  z-index: 9;
  background-color: #f1f1f1;
  text-align: center;
  border: 1px solid #d3d3d3;
}

#mydivheader {
  padding: 5px;
  cursor: move;
  z-index: 10;
  background-color: red;
  color: #000;
}
</style>

  </head>

  <body>
    <!-- article, section tags -->
    <h1>FinTech for the Precariat</h1>
<p>
  <div class="slideshow-container">
      <div class="mySlides fade">
  <img src="img/dreams01.jpg" alt="a capitalistic illusion" />
  </div>
  <div class="mySlides fade">
<img src="img/dreams02.jpg" alt="a capitalistic illusion" />
</div>
<div class="mySlides fade">
<img src="img/dreams03.jpg" alt="a capitalistic illusion" />
</div>
</div>
Welcome to the Age of Bezos.  COVID-19 has compounded existential insecurity; the pandemic of stress has been inseminated by the novel flu virus to birth a new reality – a chasm of uncertainty.  As unemployment soars, speculative futures drive a stock market that has rebounded from the initial shock.  Thanks to our brilliant leader President Trump and the Feds ability to print money at no cost and in abundance, you can walk away from labor and dive into the bliss of stock speculation and trading.  The virus will go away, the pandemic will end and those at the top will be the ones who lived without fear or masks.  The age of plutocrats, technocrats and authoritarianism will continue thriving.  The agenda of economic growth must be embraced perhaps a million or two will die, but those who embrace living for the economy and stay healthy shall reap the gains.  Stay healthy by employing yourself at home studying and trading stocks, living in the web, gathering data and moving around capital.  Embrace the FinTech revolution.
</p>
<div id="draggable">
  <video
        id="video" autoplay controls muted poster="https://rmz.github.io/finTech/video/thumbnails/fintechDreams.png" crossorigin="anonymous" width="600" >
        <source src="https://rmz.github.io/finTech/video/fintechDreams.mp4" />
    </video>
  </div>
  <p>
It has been projected that the 2020s will be the decade of the FinTech Revolution - the vehicle that democratizes wealth.  The bankers of the future are algorithms
<ul>
<li>AI, Big Data, Emerging Technologies bring us</li>
<li>Peer to Peer Lending</li>
<li>Autonomous Finance</li>
<li>Alternative Assets</li>
<li>Bitcoin</li>
<li>Digital Wallets</li>
<li>Distributed Ledger Technology</li>
<li>Emerging Market FinTech</li>
<li>Financialization of Everything</li>
<li>Financial Advisory</li>
<li>Payments</li>
<li>Underwriting Disruption</li>
</ul>
</p>
  <p>
Fintech “The Fourth Platform” after Internet Connectivity, Cloud Intelligence, and Mobile Ubiquity.
</p>
  <blockquote>
"Welcome to the world of state-approved insider trading where us peasants have to accept that in a democracy with supposed law and order, insiders can leverage public markets to make millions, even billions, in a few days by creating hype about a stock and using retail investors to bid up the price — who then get caught holding the bag...  Deception prevails even at the highest level while anyone who tries to spoil the fun pays the price...  scanning markets for dodgy activity, trying to identify the next pump-and-dump stock. This investment strategy is super risky, but with the rise of the Robinhood investor, ultra-risky investing has not only become the norm but profitable."<br>
from <a href="https://medium.com/concoda/the-easiest-way-to-profit-in-our-crony-capitalist-system-fee699f60d9c" target="_blank">The Easiest Way to Profit In Our Crony Capitalist System</a>
</blockquote>
<p>
Join the FinTech Revolution and put your money in Robinhood.  Then pick your stocks.  Are some of the stocks you desire too pricey?  No worries, just buy a fraction.  It's all merely numbers in the machine, jump in!
</p>
<div id="mydiv">
        <div id="mydivheader"><h2>Three Big Tech Companies</h2></div>
        <table border="1">
          <tr>
            <th>Company</th>
            <th>Ticker Symbol</th>
            <th>Value 2015</th>
            <th>Value 2020</th>
          </tr>
          <tr>
            <td>Apple</td>
            <td>APPL</td>
            <td>$112</td>
            <td>$500</td>
          </tr>
          <tr>
            <td>Amazon</td>
            <td>AMZN</td>
            <td>$536</td>
            <td>$3,400</td>
          </tr>
          <tr>
            <td>Google</td>
            <td>GOOG</td>
            <td>$626</td>
            <td>$1,640</td>
          </tr>
        </table>
        </div>

      <script>
        //Image auto slideshow
      // create variable to index the slides - to track the slides
      var slideIndex = 0;
      // call a function that does something with the slides
      showSlides();

      function showSlides() {
        // a variable to be used in the for loop - i for "index"
        var i;
        // target the slides in the DOM as slides
        var slides = document.getElementsByClassName("mySlides");
        // loop through the slides showing them one at a time (display)
        for (i = 0; i < slides.length; i++) {
          slides[i].style.display = "none"; //none hides the slides
        }
        // increment the slides from 0 to the total number of slides (for loop)
        slideIndex++;
        // loop back to the beginning
        if (slideIndex > slides.length) {
          slideIndex = 1;
        }
        slides[slideIndex - 1].style.display = "block"; //show the slide
        setTimeout(showSlides, 2000); // Change image every 2 seconds
      }
    </script>

        <script>
//Make the DIV element draggagle, vanilla js:
//https://www.w3schools.com/howto/howto_js_draggable.asp
dragElement(document.getElementById("mydiv"));

function dragElement(elmnt) {
  var pos1 = 0, pos2 = 0, pos3 = 0, pos4 = 0;
  if (document.getElementById(elmnt.id + "header")) {
    /* if present, the header is where you move the DIV from:*/
    document.getElementById(elmnt.id + "header").onmousedown = dragMouseDown;
  } else {
    /* otherwise, move the DIV from anywhere inside the DIV:*/
    elmnt.onmousedown = dragMouseDown;
  }

  function dragMouseDown(e) {
    e = e || window.event;
    e.preventDefault();
    // get the mouse cursor position at startup:
    pos3 = e.clientX;
    pos4 = e.clientY;
    document.onmouseup = closeDragElement;
    // call a function whenever the cursor moves:
    document.onmousemove = elementDrag;
  }

  function elementDrag(e) {
    e = e || window.event;
    e.preventDefault();
    // calculate the new cursor position:
    pos1 = pos3 - e.clientX;
    pos2 = pos4 - e.clientY;
    pos3 = e.clientX;
    pos4 = e.clientY;
    // set the element's new position:
    elmnt.style.top = (elmnt.offsetTop - pos2) + "px";
    elmnt.style.left = (elmnt.offsetLeft - pos1) + "px";
  }

  function closeDragElement() {
    /* stop moving when mouse button is released:*/
    document.onmouseup = null;
    document.onmousemove = null;
  }
}
</script>

<!-- draggable with jquery
  https://jqueryui.com/draggable/ -->
<script src="https://code.jquery.com/jquery-1.12.4.js"></script>
<script src="https://code.jquery.com/ui/1.12.1/jquery-ui.js"></script>
<script>
$( function() {
$( "#draggable" ).draggable();
} );
</script>
</body>
</html>
