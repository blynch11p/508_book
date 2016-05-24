# Skip Nav

Reasons for skip nav:

* Main content is not usually the first thing on the page<br>

* People using screen readers are forced to listen to a long list of navigation links, sub-lists of links, and other elements before arriving at the main content.<br>

* Keyboard users are forced to tab through all of the top links in order to reach the main content.<br>

#####HTML
```HTML
<body> 
<div class="hide"> <a href="#MAINcontent">Skip to Main Content</a> </div> 
<ul> 
<li>First Link</li> 
… 
</ul> 
<a name="MAINcontent"></a> 
<h2>Heading - H2</h2> 
<p>This is the first paragraph</p>
```

#####CSS
```CSS
.hide a, .hide a:hover, .hide a:visited { 
display: block; 
position: absolute; 
left:-10000px; 
top:auto; 
width: 100%; 
height: 3em; 
font-weight: bold; 
text-align: center; 
} 
.hide a:active, .hide a:focus { 
background: #BEFF9E;
position: static; 
width: auto; 
height: auto; 
padding: 1em; 
margin: auto; 
}
```