# what-makes-a-website
What do you need to do to actually build a website?

- Inspect Element
![Inspect Element](https://raw.githubusercontent.com/ceec/what-makes-a-website/master/inspectelement.png)


#HTML

- The structure of a website.
```HTML
<html>
  <body>
    <h1>Hello!</h1>
    <a href="http://www.google.com">Click here to look for things!</a>
  </body>
</html>
```
- HTML elements organize a page into smaller pieces.

#CSS

- Takes the HTML structure and manipulates it visually.
- Can use ids and classes to target specific pieces of HTML
```HTML
<html>
<head>
  <style>
    body { background-color: gray; }
    p { font-family: "Times New Roman", Times, serif; }
    #id { color: blue; }
    .class {color: red; }
  </style>
</head>
  <body>
    <h1>Hello!</h1>
    <a href="http://www.google.com">Click here to look for things!</a>
    <p>This text will be in Times New Roman.</p>
    <p id="id">This text will be in Times New Roman and red.</p>
    <p class="class">This text will be Times New Roman and blue.</p>
  </body>
</html>
```

#Javascript

- Lets you manipulate the HTML and CSS.

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

```PHP
<?php

  print '<h1>Hello!</h1>';
  
  print date('Y');

?>
```
