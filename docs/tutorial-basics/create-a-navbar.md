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
Now, it's perfect! It has space between each text, and it is on the same y level as the other text. Although, if you wish to center your text, you have to remove the **flex** class and add the **center** class.<br />
```html
<div class="menubar space center">
  <p>Centered text!</p>
</div>
```
This is due to a bug that is *IMPOSSIBLE* to solve. As a side effect of losing the **flex** class, you will not be able to have multiple **p** tags.<br />
**a** tags can also be appended to the menu bar, like **p** tags.<br />
In an earlier version of Open-CSS, you needed to wrap the **a** tag inside a **p** tag, but in 2.0, the **a** tags are treated the same as **p** tags.<br />
If you wrote HTML using an older version of Open-CSS, it should still work as the **a** and **p** tags are treated the same.<br />
With that out of the way, let's customize our navbar!<br />
You can also, like flex and space, use classes to customize the navbar.<br />
To change the color of the navbar, you can use these color values. (more will be coming soon)<br />
`red, green, blue, brown, white`<br />
To make the elements of the navbar go in the middle, you can use the center class.<br />
To finish this page off, A customized navbar example with a link. <br/>
```html
<div class="menubar red space flex">
  <p>My Website</p>
  <a href="https://www.ba4x.pro" class="white">Link</a>
</div>
```
If you're wondering about the **a** tag's class, it is the same as how you manage colors for the navbar.<br />
Up next: working with page content. Click the **next** button at the bottom to continue!