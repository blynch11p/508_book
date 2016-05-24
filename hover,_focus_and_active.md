# a:hover, a:focus and a:active

Where ever you have <strong>“hover”</strong> (a:hover) you should also have <strong>“focus”</strong> (a:focus), along with <strong>“active”</strong> for `older IE browsers`.

#####CSS Example
```css
#nav a { 
background: #ACC7FF;
text-decoration: none;
}

#nav a:hover, #nav a:focus, #nav a:active { 
background: #BEFF9E;
text-decoration: underline;
}
```