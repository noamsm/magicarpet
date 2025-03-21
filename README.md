# Magicarpet
An all in one css stylesheet library for transfroming simple HTML layouts into responsive websites

## The Vision
Let's say you have the following html body:
```html
<header>
    <img src="logo.png" />
    <a href="about.html">About</a>
    <a href="download.html">Download</a>
    <a href="contact.html">Contact Us</a>
</header>

<h1>Magicarpet</h1>
<p>Welcome to our website! Here you will find the best CSS style sheets ever!</p>

<footer>
    All rights reserved to Magicarpet corp!
</footer>
```

Adding no additional CSS - this page will be pretty bland. Using libraries like bootstrap or tailwind 
requires learning about their ins and outs and knowing the names of hundreds of classes.
Though looking at our simple page - you could imagine how it would look like if it was in the style of
other modren websites like twitter, youtube or github - just by the types of tags and their positioning
inside the document. The cool thing is - modren CSS can query those same "hints" you are picking up on
when you imagine how each component should look - so why add additional classes?

What we are aiming for with this library is exactly that - you write up a basic HTML layout, add a link 
to a magicarpet theme and your website's design is complete!

## Axioms
If you choose to contribute to the project - please follow these axioms when making choices and reviewing code:
1. **Code Developers** don't know graphical design
2. **Graphical Designers** don't know how to develop code
3. You don't want to give your users freedom if they don't know how to properly use it
4. UX development should be guided by user intuition and not by the developer's logic
