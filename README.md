# what-makes-a-website
What do you need to do to actually build a website?

- Inspect Element
![Inspect Element](https://raw.githubusercontent.com/ceec/what-makes-a-website/master/inspectelement.png)


#HTML

- The structure of a website.
- HTML elements organize a page into smaller pieces.
- [Example](http://www.christineastone.com/example/html)
```HTML
<html>
  <body>
    <h1>Hello!</h1>
    <a href="http://www.google.com">Click here to look for things!</a>
  </body>
</html>
```


#CSS

- Takes the HTML structure and manipulates it visually.
- Can use ids and classes to target specific pieces of HTML
- [Example](http://www.christineastone.com/example/css)
```HTML
<html>
<head>
  <style>
    body { background-color: lightgray; }
    p { font-family: Verdana; }
    #id { color: blue; }
    .class {color: red; }
  </style>
</head>
  <body>
    <h1>Hello!</h1>
    <a href="http://www.google.com">Click here to look for things!</a>
    <p>This text will be in Verdana.</p>
    <p id="id">This text will be in Verdana and blue.</p>
    <p class="class">This text will be Verdana and red.</p>
  </body>
</html>
```

#Javascript

- Lets you manipulate the HTML and CSS.
- [Example](http://www.christineastone.com/example/js)
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

- allows for dynamic content, it can also create HTML.
- [Example](http://www.christineastone.com/example/php)
```PHP
<?php

  print '<h1>Hello from PHP!</h1>';
  
  print date('Y');

?>
```
