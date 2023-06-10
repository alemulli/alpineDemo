# alpineDemo

A basic app made with the purpose of showing off Alpine.js, a lightweight JavaScript framework. 

This app was made using HTML, Alpine.js and Tailwind CSS.

It is a journal/blog type app where a user can write posts, submit them, and they will persist in local storage between refreshes. 

It demos the use of Alpines x-data, x-show, x-on, x-text, x-for, and x-transition, directives, as well as their persist plugin.

There is a lot more that you can potentially do with Alpine.js and I recommend checking it out. With what I've shown you alone, I think its great for small apps or for within components that have state that's not needed across your entire site and can result in very clean consise code. Something I haven't explored yet is building larger componentized apps using Alpine.js by storing global state using their Alpine.store()API and @store Magics.

# Don't Forget!

To include the following scripts in your `<head>` element.

 ```
 <script src="https://cdn.tailwindcss.com"></script>
 ```
 If you intend to use Tailwind CSS to style your document.

```
<script defer src="https://cdn.jsdelivr.net/npm/@alpinejs/persist@3.x.x/dist/cdn.min.js"></script>
```
If you intend to use the persist plugin to have state stored in local storage between refreshes.

```
<script defer src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js"></script>
```
If you intend to use Alpine.js at all. 

# Definition Zone:

x-data - for storing local state like useState in React.js

x-show - for showing and hiding elements easily without having to write scripts that change their classes from display:hidden to display:block. Useful for things like modal menus or accordions or popups.

x-on - for adding functionality to elements on click or on other triggers. 

x-text - for defining what should be the innertext of an element by refering to key values stored in x-data state.

x-for - for looping.

x-transition - smooth transitions when showing and hidding elements with x-show without having to write css animations. Tailwind CSS's transition-all classname works similarly to transition between colors or opacities.

Directives not defined here or not talked about in the video are covered very well in Alpine.js documentation linked below.


# Useful links:
- [Alpine.js](https://alpinejs.dev/)
- [The first project I did using Alpine.js. Feel free to try it yourself and compare it to how I accomplished the task described in the readme.](https://github.com/alemulli/leadpointDigitalInterviewProject)
- [Tailwind CSS Cheat Sheet](https://nerdcave.com/tailwind-cheat-sheet)