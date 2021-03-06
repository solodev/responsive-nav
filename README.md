# responsive-nav
With an increasingly mobile world, making sure your website's navigation is responsive is crucial to the success of your website. Navigation is paramount to the ease-of-use your website provides and responsive navigation is essential to allowing website visitors to view and navigate your website on all devices with ease.

## Tutorial

For detailed instructions, view Solodev's [Adding Responsive Navigation to your Website](https://www.solodev.com/blog/web-design/adding-responsive-navigation-to-your-website.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/2e8z1mpz/).

## HTML

The responsive navigation contains the following basic HTML markup.

```
<div class="parallax" id="parallax-cta" style="background-image:url(images/company-hero-1.jpg);"></div>
<nav class="ct-nav">
   <div class="navbar">
      <div class="container-fluid">
         <div class="navbar-header">
            <a class="navbar-brand" href="/index.stml"><img alt="WebCorpCo" src="images/logo.png"></a>
         </div>
         <div class="navbar-content text-right">
            <div class="inner clearfix">
               <ul class="topbar">
                  <li class="topbar__socials">
                     <a href="" target="_blank"><i class="fa fa-youtube"></i></a>
                  </li>
                  <li class="topbar__socials">
                     <a href="//www.linkedin.com/in/WebCorpCo" target="_blank"><i class="fa fa-linkedin"></i></a>
                  </li>
                  <li class="topbar__socials">
                     <a href="//twitter.com/WebCorpCo" target="_blank"><i class="fa fa-twitter"></i></a>
                  </li>
                  <li class="topbar__socials">
                     <a href="//www.facebook.com/WebCorpCo" target="_blank"><i class="fa fa-facebook"></i></a>
                  </li>
                  <li class="topbar__phone">
                     <a href="tel:5555555555">555-555-5555</a>
                  </li>
                  <li class="topbar__item">
                     <a href="">Contact Us</a>
                  </li>
                  <li class="topbar__item">
                     <a href="">Careers</a>
                  </li>
               </ul>
               <ul class="nav navbar-nav navbar-right">
                  <li class="dropdown orange-drop motive" role="presentation">
                     <a aria-expanded="false" aria-haspopup="true" class="dropdown-toggle" href="" role="button"><span>Who we are</span></a>
                     <ul class="dropdown-menu">
                        <li>
                           <a href="">Executive Team</a>
                        </li>
                        <li>
                           <a href="">Staff</a>
                        </li>
                        <li>
                           <a href="">Board Members</a>
                        </li>
                     </ul>
                  </li>
                  <li class="dropdown accent" role="presentation">
                     <a aria-expanded="false" aria-haspopup="true" class="dropdown-toggle" href="" role="button"><span>What we do</span></a>
                     <ul class="dropdown-menu">
                        <li>
                           <a href="">Services</a>
                        </li>
                        <li>
                           <a href="">Start-Up Funding </a>
                        </li>
                        <li>
                           <a href="">Product Development</a>
                        </li>
                        <li>
                           <a href="">Blog</a>
                        </li>
                     </ul>
                  </li>
                  <li class="dropdown gray grey-drop" role="presentation">
                     <a aria-expanded="false" aria-haspopup="true" class="dropdown-toggle" href="" role="button"><span>WebCorpCo</span></a>
                     <ul class="dropdown-menu dropdown-menu--right">
                        <li>
                           <a href="">Explore WebCorpCo</a>
                        </li>
                        <li>
                           <a href="">Economic Impact</a>
                        </li>
                     </ul>
                  </li>
                  <li class="dropdown yellow gold-drop" role="presentation">
                     <a aria-expanded="false" aria-haspopup="true" class="dropdown-toggle" href="" role="button"><span>News &amp; info</span></a>
                     <ul class="dropdown-menu dropdown-menu--right">
                        <li>
                           <a href="">Media</a>
                        </li>
                        <li>
                           <a href="">Public Relations</a>
                        </li>
                        <li>
                           <a href="">Conferences</a>
                        </li>
                     </ul>
                  </li>
               </ul>
            </div>
         </div>
      </div>
      <div class="navbar-mobile navbar-fixed">
         <a class="navbar-mobile__logo" href="/#"><img alt="WebCorpCo" src="https://www.solodev.com/assets/side-nav/logo.png"></a> <button id="sidenav-toggle" class="ct-menu-mobile__toggle navbar-toggle" type="button"><span class="sr-only">Menu</span> <span class="icon-bar">&nbsp;</span> <span class="icon-bar">&nbsp;</span> <span class="icon-bar">&nbsp;</span></button>
      </div>
   </div>
</nav>
<div class="ct-sidenav">
   <button class="close">x</button><img alt="Logo" class="ct-sidenav-logo" src="https://www.solodev.com/assets/side-nav/logo.png">
   <ul class="list-unstyled ct-sidenav-list">
      <li>
         <a href="#">Who We Are</a>
      </li>
      <li>
         <a href="#">What We Do</a>
      </li>
      <li>
         <a href="#">WebCorpCo</a>
      </li>
      <li>
         <a href="#">News & Info</a>
      </li>
   </ul>
   <div class="inner">
      <div class="separator"></div>
      <ul class="list-inline list-unstyled">
      <li><a href="">Careers</a></li>
      <li><a href="">Contact Us</a></li>
      <li><a href="">555-555-5555</a></li>
      <ul>
      <ul class="ct-socials list-inline list-unstyled">
         <li class="topbar__socials">
            <a href="" target="_blank"><i class="fa fa-youtube"></i></a>
         </li>
         <li class="topbar__socials">
            <a href="//www.linkedin.com/in/WebCorpCo" target="_blank"><i class="fa fa-linkedin"></i></a>
         </li>
         <li class="topbar__socials">
            <a href="//twitter.com/WebCorpCo" target="_blank"><i class="fa fa-twitter"></i></a>
         </li>
         <li class="topbar__socials">
            <a href="//www.facebook.com/WebCorpCo" target="_blank"><i class="fa fa-facebook"></i></a>
         </li>
      </ul>
      <div class="ct-u-paddingTop60"></div>
   </div>
</div>

```
## CSS

All necessary CSS is in nav.css

## External Includes
```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css" rel="stylesheet">
<link href="nav.css" rel="stylesheet">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
<script src="nav.js"></script>
```
