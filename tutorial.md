# BCSS

> A modern __simplified__ CSS library

__Statement:__ who cares about node packages or postcss?

### Tutorial
---

> Padding, Margin, Font, and Border Radius size

What do they have in common?

1. The Size options
2. The Selector name

to add padding ->

```css
p  (padding:6px;)
p-m (padding:16px;)
p-l (padding:32px;)
p-xl (padding:50px;)
```

Margin works the same, just swap out __p__ for __m__

to add font sizes ->

```css
f  (font-size:16px;)
f-m (font-size:20px;)
f-l (font-size:25px;)
f-xl (font-size:40px;)
```

to add radius to border ->

```css
r  (border-radius:5px;)
r-m (border-radius:10px;)
r-l (border-radius:20px;)
r-full (border-radius:100px;)
```

### What if you want to change something only on hover?

For every* class there is an accompanying hover class.<br/>
Just add `hover-` to the start of the class name.

For example
```html
<p class="hover-p-xl">
	I Expand Padding on Hover
</p>
```

### Colors

BCSS offers a fine tuned color palate with 8 colors

1. White*
2. Black*
3. Calm ~ *lightgreen*
4. Alert ~ *red*
5. Info ~ *darkred*
6. Null ~ *brown*
7. Slate ~ *dark oceangreen*
8. Silence ~ *lightpurple*

For background color -> `bg-(color)` or `hover-bg-(color)`<br/>
For text color -> `(color)`<br/>

```html
<!-- 
A Black Background with purple* text
-->
<div class="bg-black silence f-xl">
	I am a colored box!
</div>
```
