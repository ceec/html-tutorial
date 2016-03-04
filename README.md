# what-makes-a-website
What do you need to do to actually build a website?

*HTML
*CSS
*Javascript
*PHP

#HTML

HTML is the structure of a website.
```HTML
<html>
  <body>
    <h1>Hello!</h1>
    <a href="http://www.google.com">Click here to look for things!</a>
  </body>
</html>
```

#CSS

CSS takes the structure and manipulates it visually.
```HTML
<html>
<head>
  <style>
body {
    background-color: blue;
     }  
</style>
</head>
  <body>
    <h1>Hello!</h1>
    <a href="http://www.google.com">Click here to look for things!</a>
  </body>
</html>
```

#Javascript

Javacsript takes the webpage and lets you manipulate it.

```HTML
    <button id="button">Click Me!</button>
    <script type="text/javascript">
      var button = document.getElementById('button');
      button.addEventListener('click', function() {
          alert('You clicked the button!');
      }, false);
    </script>
```

#PHP
