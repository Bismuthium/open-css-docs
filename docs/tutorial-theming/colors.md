---
sidebar_position: 1
---

# Setting The Colors

Colors. Arguably the most important thing if you're designing a website. Choose the wrong ones and it looks crappy.<br />
Well, Open-CSS already has the colors. You just need to use them.<br />
<br />
First, here's our HTML. We want to give it a blue theme.<br />
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog</title>
</head>
<body>
    <div>
        <p>Blog</p>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </div>
    <div>
        <div>This is a blog post, check with my teacher if you don't believe me.</div>
    </div>
</body>
</html>
```
But before we do any theming, we need to import Open-CSS. Let's assume we're using 2.0 for this example, and the file is in the root directory next to our **index.html** file.<br />
First, add the appropriate class tags.
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
    <div class="menubar space flex">
        <p>Blog</p>
        <a href="#" class="white">Home</a>
        <a href="#" class="white">About</a>
        <a href="#" class="white">Contact</a>
    </div>
    <div class="content">
        <div class="container">This is a blog post, check with my teacher if you don't believe me.</div>
    </div>
</body>
</html>
```
When we open this site, we'll see it still isn't blue. It's time to apply the appropriate color classes.<br />
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
There wasn't much to do there, but if we had buttons we would've had to change those to use blue too. You might also notice that I've changed the **a** tags to use black instead of white. I did that for readability purposes.<br />