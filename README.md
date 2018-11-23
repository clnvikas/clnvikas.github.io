body {
    font-family: Helvetica sans-serif;
    padding: 0;
    margin: 0;
    background-color: #222;
    overflow: hidden;
    -webkit-user-select: none;
       -moz-user-select: none;
         -o-user-select: none;
        -ms-user-select: none;
            user-select: none;
}

canvas {
    position: absolute;
    top: 0;
    left: 0;
}

.info {
    position: absolute;
    top: 0;
    left: 0;
    padding: 5px 15px;
    color: #eee;
    font-size: 13px;
    background-color: rgba(0, 0, 0, .5);
}


h1, .h1, h2, .h2, h3, .h3, h4, .h4, h5, .h5, h6, .h6, p, .navbar, .brand, a, .td-name, td, button, input, select, textarea {
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  font-family: "Montserrat", "Helvetica", Arial, sans-serif;
  font-weight: 300;
}

h1, .h1, h2, .h2, h3, .h3, h4, .h4 {
  margin: 30px 0 0;
}

h1, .h1 {
  font-size: 3.6em;
}

h2, .h2 {
  font-size: 2.8em;
}

h3, .h3 {
  font-size: 1.825em;
  line-height: 1.4;
  margin: 20px 0 0px;
}

h4, .h4 {
  font-size: 1.6em;
  line-height: 1.2em;
}

h5, .h5 {
  font-size: 1.35em;
  line-height: 1.4em;
}

h6, .h6 {
  font-size: 0.9em;
  font-weight: 600;
  text-transform: uppercase;
  line-height: 1.5em;
}

p {
  font-size: 15px;
  line-height: 1.5em;
  margin-bottom: 5px;
}

h1 small, h2 small, h3 small, h4 small, h5 small, h6 small, .h1 small, .h2 small, .h3 small, .h4 small, .h5 small, .h6 small, h1 .small, h2 .small, h3 .small, h4 .small, h5 .small, h6 .small, .h1 .small, .h2 .small, .h3 .small, .h4 .small, .h5 .small, .h6 .small {
  color: #9A9A9A;
  line-height: 1.5em;
}

h1 small, h2 small, h3 small, h1 .small, h2 .small, h3 .small {
  font-size: 60%;
}

.title,
.card-title,
.info-title,
.footer-brand,
.footer-big h5,
.footer-big h4,
.media .media-heading {
  font-family: "Montserrat", "Helvetica", Arial, sans-serif;
}
.title,
.title a,
.card-title,
.card-title a,
.info-title,
.info-title a,
.footer-brand,
.footer-brand a,
.footer-big h5,
.footer-big h5 a,
.footer-big h4,
.footer-big h4 a,
.media .media-heading,
.media .media-heading a {
  color: #333333;
  text-decoration: none;
}

.title-uppercase {
  text-transform: uppercase;
}

.description {
  color: #9A9A9A;
}

blockquote small {
  font-style: normal;
}

.text-muted {
  color: #DDDDDD;
}

.text-primary, .text-primary:hover {
  color: #51cbce !important;
}

.text-info, .text-info:hover {
  color: #51bcda !important;
}

.text-success, .text-success:hover {
  color: #6bd098 !important;
}

.text-warning, .text-warning:hover {
  color: #fbc658 !important;
}

.text-danger, .text-danger:hover {
  color: #f5593d !important;
}

.glyphicon {
  line-height: 1;
}

.heart {
  color: #EB5E28;
  animation: heathing 1s ease infinite;
}

@keyframes heathing {
  0% {
    transform: scale(0.75);
  }
  20% {
    transform: scale(1);
  }
  40% {
    transform: scale(0.75);
  }
  60% {
    transform: scale(1);
  }
  80% {
    transform: scale(0.75);
  }
  100% {
    transform: scale(0.75);
  }
}
.footer .credits,
.footer-nav {
  line-height: 85px;
}

.footer .btn {
  margin-bottom: 0;
}

.blockquote {
  border-left: 0 none;
  border-bottom: 1px solid #CCC5B9;
  border-top: 1px solid #CCC5B9;
  font-weight: 300;
  margin: 15px 0 10px;
  text-align: center;
}

.title {
  margin-top: 30px;
  margin-bottom: 25px;
  min-height: 32px;
}

.title.text-center {
  margin-bottom: 50px;
}

/*     General overwrite     */
body {
  color: #66615b;
  font-size: 14px;
  font-weight: 300;
  font-family: 'Montserrat', "Helvetica", Arial, sans-serif;
}

a {
  color: #51bcda;
}
a:hover, a:focus {
  color: #2ba9cd;
  text-decoration: none;
}

hr {
  border-color: #F1EAE0;
}

.icon {
  fill: #66615b;
}

.fa-base {
  font-size: 1.25em !important;
}

a:focus, a:active,
button::-moz-focus-inner,
input[type="reset"]::-moz-focus-inner,
input[type="button"]::-moz-focus-inner,
input[type="submit"]::-moz-focus-inner,
select::-moz-focus-inner,
input[type="file"] > input[type="button"]::-moz-focus-inner {
  outline: 0;
}

.ui-slider-handle:focus,
.navbar-toggle {
  outline: 0 !important;
}

/*           Animations              */
.form-control,
.input-group-addon,
.tagsinput,
.navbar,
.navbar .alert,
.carousel-control.right,
.carousel-control.left {
  -webkit-transition: all 300ms linear;
  -moz-transition: all 300ms linear;
  -o-transition: all 300ms linear;
  -ms-transition: all 300ms linear;
  transition: all 300ms linear;
}

.tagsinput .tag,
.tagsinput-remove-link,
.filter,
.btn-hover,
[data-toggle="collapse"] i,
.animation-transition-fast,
.dropdown-menu .dropdown-item {
  -webkit-transition: all 150ms linear;
  -moz-transition: all 150ms linear;
  -o-transition: all 150ms linear;
  -ms-transition: all 150ms linear;
  transition: all 150ms linear;
}

.btn-morphing .fa,
.btn-morphing .circle,
.gsdk-collapse {
  -webkit-transition: all 300ms linear;
  -moz-transition: all 300ms linear;
  -o-transition: all 300ms linear;
  -ms-transition: all 300ms linear;
  transition: all 300ms linear;
}

.fa {
  width: 18px;
  text-align: center;
}

.margin-top {
  margin-top: 50px;
}

.iframe-container iframe {
  box-shadow: 0 16px 38px -12px rgba(0, 0, 0, 0.56), 0 4px 25px 0 rgba(0, 0, 0, 0.12), 0 8px 10px -5px rgba(0, 0, 0, 0.2);
}

/*       CT colors          */
.ct-blue {
  color: #51cbce;
}

.ct-azure {
  color: #51bcda;
}

.ct-green {
  color: #6bd098;
}

.ct-orange {
  color: #fbc658;
}

.ct-red {
  color: #f5593d;
}

.pagination .page-item .page-link .fa {
  width: auto;
  font-weight: 600;
}

.bg-primary {
  background-color: #6dd3d6 !important;
}

.bg-info {
  background-color: #6ec7e0 !important;
}

.bg-success {
  background-color: #86d9ab !important;
}

.bg-warning {
  background-color: #fcd27b !important;
}

.bg-danger {
  background-color: #f7765f !important;
}

.navbar-transparent {
  background-color: transparent !important;
  border-bottom: 1px solid transparent;
}

.btn {
  box-sizing: border-box;
  border-width: 2px;
  font-size: 12px;
  font-weight: 600;
  padding: 0.5rem 18px;
  line-height: 1.75;
  cursor: pointer;
  text-transform: uppercase;
  background-color: #66615B;
  border-color: #66615B;
  color: #FFFFFF;
  opacity: 1;
  filter: alpha(opacity=100);
  -webkit-transition: all 150ms linear;
  -moz-transition: all 150ms linear;
  -o-transition: all 150ms linear;
  -ms-transition: all 150ms linear;
  transition: all 150ms linear;
}
.btn.btn-border, .btn.btn-link {
  background-color: transparent;
}
.btn:hover, .btn:focus, .btn:active, .btn.active, .show > .btn.dropdown-toggle {
  background-color: #403D39;
  color: #FFFFFF;
  border-color: #403D39;
}
.btn .caret {
  border-top-color: #FFFFFF;
}
.btn.btn-link {
  color: #66615B;
}
.btn.btn-link:hover, .btn.btn-link:focus, .btn.btn-link:active, .btn.btn-link.active, .open > .btn.btn-link.dropdown-toggle {
  background-color: transparent;
  color: #403D39;
}
.btn.btn-link .caret {
  border-top-color: #66615B;
}
.btn .caret {
  border-top-color: #FFFFFF;
}
.btn:hover, .btn:focus {
  outline: 0 !important;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn:active, .btn.active, .open > .btn.dropdown-toggle {
  -webkit-box-shadow: none;
  box-shadow: none;
  outline: 0 !important;
}
.btn[class*="btn-outline-"] {
  background-image: none;
  background-color: transparent;
}

.btn-just-icon {
  border-radius: 50px;
  height: 40px;
  width: 40px;
  min-width: 40px;
  padding: 8px;
}
.btn-just-icon.btn-sm {
  padding: 4px !important;
}
.btn-just-icon i {
  font-size: 16px;
  padding: 2px 0px;
}

.upgrade-pro .btn {
  margin-top: 30px;
}

.btn-link.btn-just-icon {
  padding: 8px;
}

.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -2px;
}

.btn-primary {
  background-color: #51cbce;
  border-color: #51cbce;
  color: #FFFFFF;
  opacity: 1;
  filter: alpha(opacity=100);
}
.btn-primary:hover, .btn-primary:focus, .btn-primary:active, .btn-primary.active, .show > .btn-primary.dropdown-toggle {
  background-color: #34b5b8;
  color: #FFFFFF;
  border-color: #34b5b8;
}
.btn-primary .caret {
  border-top-color: #FFFFFF;
}
.btn-primary.btn-link {
  color: #51cbce;
}
.btn-primary.btn-link:hover, .btn-primary.btn-link:focus, .btn-primary.btn-link:active, .btn-primary.btn-link.active, .open > .btn-primary.btn-link.dropdown-toggle {
  background-color: transparent;
  color: #34b5b8;
}
.btn-primary.btn-link .caret {
  border-top-color: #51cbce;
}
.btn-primary .caret {
  border-top-color: #FFFFFF;
}

.btn-success {
  background-color: #6bd098;
  border-color: #6bd098;
  color: #FFFFFF;
  opacity: 1;
  filter: alpha(opacity=100);
}
.btn-success:hover, .btn-success:focus, .btn-success:active, .btn-success.active, .show > .btn-success.dropdown-toggle {
  background-color: #44c47d;
  color: #FFFFFF;
  border-color: #44c47d;
}
.btn-success .caret {
  border-top-color: #FFFFFF;
}
.btn-success.btn-link {
  color: #6bd098;
}
.btn-success.btn-link:hover, .btn-success.btn-link:focus, .btn-success.btn-link:active, .btn-success.btn-link.active, .open > .btn-success.btn-link.dropdown-toggle {
  background-color: transparent;
  color: #44c47d;
}
.btn-success.btn-link .caret {
  border-top-color: #6bd098;
}
.btn-success .caret {
  border-top-color: #FFFFFF;
}

.btn-info {
  background-color: #51bcda;
  border-color: #51bcda;
  color: #FFFFFF;
  opacity: 1;
  filter: alpha(opacity=100);
}
.btn-info:hover, .btn-info:focus, .btn-info:active, .btn-info.active, .show > .btn-info.dropdown-toggle {
  background-color: #2ba9cd;
  color: #FFFFFF;
  border-color: #2ba9cd;
}
.btn-info .caret {
  border-top-color: #FFFFFF;
}
.btn-info.btn-link {
  color: #51bcda;
}
.btn-info.btn-link:hover, .btn-info.btn-link:focus, .btn-info.btn-link:active, .btn-info.btn-link.active, .open > .btn-info.btn-link.dropdown-toggle {
  background-color: transparent;
  color: #2ba9cd;
}
.btn-info.btn-link .caret {
  border-top-color: #51bcda;
}
.btn-info .caret {
  border-top-color: #FFFFFF;
}

.btn-warning {
  background-color: #fbc658;
  border-color: #fbc658;
  color: #FFFFFF;
  opacity: 1;
  filter: alpha(opacity=100);
}
.btn-warning:hover, .btn-warning:focus, .btn-warning:active, .btn-warning.active, .show > .btn-warning.dropdown-toggle {
  background-color: #fab526;
  color: #FFFFFF;
  border-color: #fab526;
}
.btn-warning .caret {
  border-top-color: #FFFFFF;
}
.btn-warning.btn-link {
  color: #fbc658;
}
.btn-warning.btn-link:hover, .btn-warning.btn-link:focus, .btn-warning.btn-link:active, .btn-warning.btn-link.active, .open > .btn-warning.btn-link.dropdown-toggle {
  background-color: transparent;
  color: #fab526;
}
.btn-warning.btn-link .caret {
  border-top-color: #fbc658;
}
.btn-warning .caret {
  border-top-color: #FFFFFF;
}

.btn-danger {
  background-color: #f5593d;
  border-color: #f5593d;
  color: #FFFFFF;
  opacity: 1;
  filter: alpha(opacity=100);
}
.btn-danger:hover, .btn-danger:focus, .btn-danger:active, .btn-danger.active, .show > .btn-danger.dropdown-toggle {
  background-color: #f33816;
  color: #FFFFFF;
  border-color: #f33816;
}
.btn-danger .caret {
  border-top-color: #FFFFFF;
}
.btn-danger.btn-link {
  color: #f5593d;
}
.btn-danger.btn-link:hover, .btn-danger.btn-link:focus, .btn-danger.btn-link:active, .btn-danger.btn-link.active, .open > .btn-danger.btn-link.dropdown-toggle {
  background-color: transparent;
  color: #f33816;
}
.btn-danger.btn-link .caret {
  border-top-color: #f5593d;
}
.btn-danger .caret {
  border-top-color: #FFFFFF;
}

.btn-neutral {
  background-color: #FFFFFF;
  border-color: #FFFFFF;
  color: #FFFFFF;
  opacity: 1;
  filter: alpha(opacity=100);
}
.btn-neutral:hover, .btn-neutral:focus, .btn-neutral:active, .btn-neutral.active, .show > .btn-neutral.dropdown-toggle {
  background-color: #403D39;
  color: #FFFFFF;
  border-color: #403D39;
}
.btn-neutral .caret {
  border-top-color: #FFFFFF;
}
.btn-neutral.btn-link {
  color: #FFFFFF;
}
.btn-neutral.btn-link:hover, .btn-neutral.btn-link:focus, .btn-neutral.btn-link:active, .btn-neutral.btn-link.active, .open > .btn-neutral.btn-link.dropdown-toggle {
  background-color: transparent;
  color: #403D39;
}
.btn-neutral.btn-link .caret {
  border-top-color: #FFFFFF;
}
.btn-neutral .caret {
  border-top-color: #FFFFFF;
}



<!DOCTYPE html>
<html lang="en" >

<head>
  <meta charset="UTF-8">
  <title>HomePage</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="viewport" content="width=device-width" />
  
  <link rel='stylesheet prefetch' href='https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css'>
<link rel='stylesheet prefetch' href='https://fonts.googleapis.com/css?family=Montserrat:400,300,700'>
<link rel='stylesheet prefetch' href='https://maxcdn.bootstrapcdn.com/font-awesome/latest/css/font-awesome.min.css'>

      <link rel="stylesheet" href="css/style.css">

  
</head>

<body>

  <body>
    <nav class="navbar navbar-toggleable-md fixed-top navbar-transparent" color-on-scroll="500">
        <div class="container">
            <div class="navbar-translate">
                <button class="navbar-toggler navbar-toggler-right navbar-burger" type="button" data-toggle="collapse" data-target="#navbarToggler" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-bar"></span>
                    <span class="navbar-toggler-bar"></span>
                    <span class="navbar-toggler-bar"></span>
                </button>
                
            </div>
            <div class="collapse navbar-collapse" id="navbarToggler">
                <ul class="navbar-nav ml-auto">
                   
                   
                    <li class="nav-item">
						
		</li>
                </ul>
            </div>
        </div>
    </nav>
    <div class="wrapper">
        <div class="page-header section-dark" style="background-image: url('http://demos.creative-tim.com/paper-kit-2/assets/img/antoine-barres.jpg')">
            <div class="filter"></div>
    		<div class="content-center">
    			<div class="container">
    				<div class="title-brand">
    					<h1 class="presentation-title">C.L.N.VIKAS</h1>
    					<div class="fog-low">
    						<img src="http://demos.creative-tim.com/paper-kit-2/assets/img/fog-low.png" alt="">
    					</div>
    					<div class="fog-low right">
    						<img src="http://demos.creative-tim.com/paper-kit-2/assets/img/fog-low.png" alt="">
    					</div>
    				</div>
                     <h2 class="presentation-subtitle text-center">student</h2>
    				<h3 class="presentation-subtitle text-center">amrita school of engineering </h3>
    				<h3 class="presentation-subtitle text-center">bengaluru </h3>
    			</div>
    		</div>
            <div class="moving-clouds" style="background-image: url('http://demos.creative-tim.com/paper-kit-2/assets/img/clouds.png'); ">

            </div>
    	</div>
  </div>
</body>
  <script src='https://code.jquery.com/jquery-3.1.1.slim.min.js'></script>
<script src='https://cdnjs.cloudflare.com/ajax/libs/tether/1.4.0/js/tether.min.js'></script>
<script src='https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js'></script>

  

    <script  src="js/index.js"></script>




</body>

</html>
