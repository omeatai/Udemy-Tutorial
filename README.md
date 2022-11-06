# Mern-Tutorial
Learn MERN by Ifeanyi Omeata

## Tutorial

---

### [1-THE COMPLETE BOOTCAMP - THE APP BREWERY](#)

+INTRODUCTION TO HTML

<details>
  <summary>1. The HTML Headers</summary>

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

```html
<!-- This is a Comment -->
<center>
    <hr size="3" noshade>
    <h1>THE ADVENTURES OF <br> SHERLOCK HOLMES</h1>
    <br>
    <h3>by</h3>
    <br>
    <h2>SIR ARTHUR CONAN DOYLE</h2>
    <hr size="3" noshade>
</center>
<!-- This is the end of the HTML code -->
```

</details>

<details>
  <summary>2. The HTML Meta Tags</summary>

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="description" content="My Personal Page">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Site</title>
  </head>
  <body>
    <h1>This is a Html Page</h1>
  </body>
</html>
```

The HTML Meta Tag

```html
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```

```html
<head lang="en">
  <meta http-equiv="content-language" content="en">
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="keywords" content="website, blog, foo, bar">
  <meta name="author" content="John Doe">
  <meta name="publisher" content="John Doe">
  <meta name="copyright" content="John Doe">
  <meta name="description" content="This short description describes my website.">
  <meta name="page-topic" content="Media">
  <meta name="page-type" content="Blogging">
  <meta name="audience" content="Everyone">
  <meta name="robots" content="index, follow">
  <title>My website title</title>
</head>
```

</details>

<details>
  <summary>3. HTML Example</summary>

```html
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>Angela's Personal Site</title>
</head>

<body>
  <h1>Angela Yu</h1>
  <p><em>Founder and CTO of <strong>The App Brewery</strong>.</em></p>
  <p>I am an iOS and Web Developer. I love coffee and brew my own beers.</p>
  <hr>
</body>

</html>
```

</details>

<details>
  <summary>4. HTML Lists</summary>

```html
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>Angela's Personal Site</title>
</head>

<body>
  <h1>Angela Yu</h1>
  <p><em>Founder and CTO of <strong>The App Brewery</strong>.</em></p>
  <p>I am an iOS and Web Developer. I love coffee and brew my own beers.</p>
  <hr>
  <h3>Books and Teaching</h3>
  <ul>
    <li>The Complete iOS App Development Bootcamp</li>
    <li>The Complete Web Development Bootcamp</li>
  </ul>
  <h3>My Hobbies</h3>
  <ol>
    <li>Beer brewing</li>
    <li>Martial arts</li>
    <li>Motorcycles</li>
  </ol>
</body>

</html>

```

```html
<ol type="i">
    <li>foo</li>
    <li>bar</li>
    <li>span</li>
</ol>
```

```html
<ol start="7">
    <li>first item</li>
    <li>second item</li>
    <li>third item</LI>
</ol>
```

</details>

<details>
  <summary>5. HTML Images</summary>

```html
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>Angela's Personal Site</title>
</head>

<body>
  <img src="https://pbs.twimg.com/profile_images/1523987597751726081/XuQeo7gC_400x400.jpg" width="80px" height="80px" alt="Angela's Photo"></img>
  <!-- <img src="images/myimage.png" width="80px" height="80px" alt="Angela's Photo"></img> -->
  <h1>Angela Yu</h1>
  <p><em>Founder and CTO of <strong>The App Brewery</strong>.</em></p>
  <p>I am an iOS and Web Developer. I love coffee and brew my own beers.</p>
  <hr>
  <h3>Books and Teaching</h3>
  <ul>
    <li>The Complete iOS App Development Bootcamp</li>
    <li>The Complete Web Development Bootcamp</li>
  </ul>
  <h3>My Hobbies</h3>
  <ol>
    <li>Beer brewing</li>
    <li>Martial arts</li>
    <li>Motorcycles</li>
  </ol>
</body>

</html>
```

</details>

<details>
  <summary>6. HTML Anchors</summary>

Index.html:

```html
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>Angela's Personal Site</title>
</head>

<body>
  <img src="https://pbs.twimg.com/profile_images/1523987597751726081/XuQeo7gC_400x400.jpg" width="80px" height="80px" alt="Angela's Photo"></img>
  <h1>Angela Yu</h1>
  <p><em>Founder and CTO of <strong><a href="https://www.appbrewery.co/"> The App Brewery </a></strong>.</em></p>
  <p>I am an iOS and Web Developer. I love coffee and brew my own beers.</p>
  <hr>
  <h3>Books and Teaching</h3>
  <ul>
    <li>The Complete iOS App Development Bootcamp</li>
    <li>The Complete Web Development Bootcamp</li>
  </ul>
  <a href="hobbies.html">My Hobbies</a>
  <a href="contact.html">Contact Me</a>
</body>

</html>
```

Hobbies.html:

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>My Hobbies</title>
  </head>
  <body>
    <h3>My Hobbies</h3>
    <ol>
      <li><a href="#">Beer brewing</a></li>
      <li>Martial arts</li>
      <li><a href="#">Motorcycles</a></li>
    </ol>
  </body>
</html>

```

Contact.html:

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>My Contact</title>
  </head>
  <body>
    <h1>My Contact Details</h1>
    <p>My Fictional Address</p>
    <p>077263718463</p>
    <p>myemail@gmail.com</p>
  </body>
</html>

```

</details>

<details>
  <summary>7. HTML Tables </summary>

Index.html:

```html
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>Angela's Personal Site</title>
</head>

<body>
  <img src="https://pbs.twimg.com/profile_images/1523987597751726081/XuQeo7gC_400x400.jpg" width="80px" height="80px" alt="Angela's Photo"></img>
  <h1>Angela Yu</h1>
  <p><em>Founder and CTO of <strong><a href="https://www.appbrewery.co/"> The App Brewery </a></strong>.</em></p>
  <p>I am an iOS and Web Developer. I love coffee and brew my own beers.</p>
  <hr>
  <h3>Books and Teaching</h3>
  <ul>
    <li>The Complete iOS App Development Bootcamp</li>
    <li>The Complete Web Development Bootcamp</li>
  </ul>
  <hr />
  <h3>Work Experience</h3>
  <table cellspacing="10">
    <thead>
      <tr>
        <th>Dates</th>
        <th>Work</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>2010-2013</td>
        <td>Lead Developer at Tempo App</td>
      </tr>
      <tr>
        <td>2010</td>
        <td>Researcher at The Institute of Cognitive Neurosciences</td>
      </tr>
    </tbody>
    <tfoot>
      <tr>
        <td>Copyright &copy; the App Brewery</td>
        <td>👍🏻</td>
      </tr>
    </tfoot>
  </table>
  <hr>
  <a href="hobbies.html">My Hobbies</a>
  <a href="contact.html">Contact Me</a>
</body>

</html>

```

</details>

<details>
  <summary>8. sample</summary>

```html

```

```html

```

```html

```

```bash

```

</details>

<details>
  <summary>9. sample</summary>

```html

```

```html

```

```html

```

```bash

```

</details>

<details>
  <summary>10. sample</summary>

```html

```

```html

```

```html

```

```bash

```

</details>