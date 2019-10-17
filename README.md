# UTMDSC-Web-101
By Henry Tu

## Bread and Butter
There are 3 main components to a website (frontend).

HTML - The backbone / skeleton<br>
CSS - The style and formatting<br>
JS - The logic (and actual code)

## Creating an HTML Page

### Breakdown
####Comments
```
<!-- Comments go in here-->

<!-- 
Multiline comment
Line 1
Line 2
-->

```

####How tags work
Replace `X` with the name of the tag. Be sure to close any tags that you open! 
```$xslt
<X>  <!-- Open tag -->
     <!-- Stuff goes inside -->
</X> <!-- Close tag -->
```

####Sample Page
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

#### Basic text
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

#### Hyperlinks
You can use a-tags to direct users to another page. 
```$xslt
<a src="https://google.com">
    <!-- What you want to be clicked goes here -->
    
    Go to Google!
</a>
```