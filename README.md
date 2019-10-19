# UTMDSC-Web-101
By Henry Tu

## Demo Pages

[Hello World!](https://henrytwo.github.io/UTMDSC-Web-101/step-1-helloworld) <br>
[HTML Tags](https://henrytwo.github.io/UTMDSC-Web-101/step-2-tags) <br>
[CSS](https://henrytwo.github.io/UTMDSC-Web-101/step-3-css) <br>
[Bootstrap](https://henrytwo.github.io/UTMDSC-Web-101/step-4-bootstrap) <br>

## Bread and Butter
There are 3 main components to a website (frontend).

HTML - The backbone / skeleton<br>
CSS - The style and formatting<br>
JS - The logic (and actual code)

## Creating an HTML Page

### Comments
```
<!-- Comments go in here-->

<!-- 
Multiline comment
Line 1
Line 2
-->

```

### How tags work
Replace `X` with the name of the tag. Be sure to close any tags that you open! 
```$xslt
<X>  <!-- Open tag -->
     <!-- Stuff goes inside -->
</X> <!-- Close tag -->
```

### Sample Page
```
<html lang="en">
<head>                           <!-- Contains meta data (stuff that isn't displayed) -->
    <meta charset="UTF-8">
    <title>Hello, world!</title> <!-- Title that will be displayed on top -->
</head>

<body>                           <!-- The actual content of the website -->
This is a cool website.
</body>
</html>
```

### Basic text
```$xslt
<p>
    This is a paragraph
</p>

<h1>
    BIG TEXT
</h1>

<h2>
    LESS BIG TEXT
</h2>

<h3>
    LESS BIG TEXT
</h3>

<h4>
    SMOL TEXT
</h4>

<h5>
    SMOLLER TEXT
</h5>
```

### Hyperlinks
You can use  `a` tags to direct users to another page. 
```$xslt
<a src="https://google.com">
    <!-- What you want to be clicked goes here -->
    
    Go to Google!
</a>
```

Add ``target="_blank"`` to the `a` tag to make it open in a new tab.
```$xslt
<a src="https://google.com" target="_blank">
    <!-- What you want to be clicked goes here -->
    
    Go to Google!
</a>
```

### Images
You can use `img` tags to add images to your website! Put the path to your desired image in `src=""`
```$xslt
<img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png">
</img>
```

### Linking CSS
It's good practice to put CSS in a different file so that your code doesn't become super cluttered. Put the path to your CSS file in `href=""`.


``    <link href="css/main.css" rel="stylesheet">
``

### Bootstrap
Bootstrap is a popular framework for frontend web projects. Why make something from scratch when it already exists?
<br>
<br>
To install bootstrap, add the following in your `<head>`.

```$xslt
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>

<script>

alert("Hello!")
</script>
```
Here's some documentation to help you get started: <br>

[Bootstrap Documentation](https://getbootstrap.com/docs/4.3/getting-started/introduction/)

### Scale on mobile properly
Add this to make sure your website scales on mobile properly.

```<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=0" />```