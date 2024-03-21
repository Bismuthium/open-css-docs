---
sidebar_position: 2
---

# Create a Navbar

A **navbar** is a part of a website that contains all of it's navigation components, or in simpler terms the top bar on most websites.<br />
You can easily create one in Open-CSS by making a div element with the class "menubar".
```html
<div class="menubar">

</div>
```
That's how you create a basic navbar! You can add text to it by appending a **p** tag to it with text.
```html
<div class="menubar">
  <p>Some text here</p>
</div>
```
If you try it out though, it appears purple, and is at the very left.<br />
Which is good! Although, the text is maybe a bit too far to the left. We can fix this by adding "space" to the class.
```html
<div class="menubar space">
  <p>Some text here</p>
</div>
```
Now, it looks better. There's one main issue though; if you try to append another **p** tag to the navbar, then it will not appear.<br />
Although, it is there! You can see it by pressing **Ctrl+A**. The problem is, it is under the menubar. The way you can fix this is by adding "flex" to the class.
```html
<div class="menubar space flex">
  <p>Some text here</p>
  <p>Even more text</p>
</div>
```
Now, it's perfect! It has space between each text, and it is on the same y level as the other text. But if you want to add a link to the menubar, you'll encounter an issue.<br />
If you try to add an **a** tag to make a link, like in normal HTML, it won't work!<br />
The issue lies in how youre making it. You can't just use an **a** tag by itself, you have to nest the **a** tag into a **p** tag, then it will work.<br />
With that out of the way, let's customize our navbar!<br />
You can also, like flex and space, use classes to customize the navbar.<br />
To change the color of the navbar, you can use these color values. (more will be coming soon)<br />
red, green, blue, brown, white<br />
To make the elements of the navbar go in the middle, you can use the center class.<br />
To finish this page off, A customized navbar example with a link. <br/>
```html
<div class="menubar red space flex">
  <p>My Website</p>
  <p><a href="https://www.ba4x.pro" class="white">Link</a></p>
</div>
```
If you're wondering about the **a** tag's class, it is the same as how you manage colors for the navbar.<br />
Up next: working with page content. Click the **next** button at the bottom to continue!