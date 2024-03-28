---
sidebar_position: 2
---

# Shadows and Dark Theming

Assuming we left off from the last tutorial, here's our HTML.<br />
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="open-css.css">
    <title>Blog</title>
</head>
<body>
    <div class="menubar space flex blue">
        <p>Blog</p>
        <a href="#" class="black">Home</a>
        <a href="#" class="black">About</a>
        <a href="#" class="black">Contact</a>
    </div>
    <div class="content">
        <div class="container">This is a blog post, check with my teacher if you don't believe me.</div>
    </div>
</body>
</html>
```
It doesn't really **pop** yet, so we can add shadows to it!<br />
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="open-css.css">
    <title>Blog</title>
</head>
<body>
    <div class="menubar space flex blue">
        <p>Blog</p>
        <a href="#" class="black">Home</a>
        <a href="#" class="black">About</a>
        <a href="#" class="black">Contact</a>
    </div>
    <div class="content">
        <div class="container shadow">This is a blog post, check with my teacher if you don't believe me.</div>
    </div>
</body>
</html>
```
Of course, this is very boring, and still doesn't **POP** that well. We can change this to dark mode to counteract this.<br />
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="open-css.css">
    <title>Blog</title>
</head>
<body class="background dark">
    <div class="menubar space flex dark">
        <p>Blog</p>
        <a href="#" class="white">Home</a>
        <a href="#" class="white">About</a>
        <a href="#" class="white">Contact</a>
    </div>
    <div class="content">
        <div class="container shadow dark">This is a blog post, check with my teacher if you don't believe me.</div>
    </div>
</body>
</html>
```
At first you may not see much out of the ordinary. But the new "background dark" class in the **body** tag is definitely not ordinary. It's there because uhh css is dumb lol im tired of writing this BYEBYE<br />