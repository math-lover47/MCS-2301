
[why we need `<!DOCTYPE html>`?](https://www.linkedin.com/advice/1/what-purpose-html-doctype-declaration-skills-web-applications-vt25c)

The `doctype` declaration is a way of telling the browser what version of HTML the web page is using. HTML stands for `HyperText Markup Language`, and it is the standard language for creating web pages. HTML has evolved over the years, and different versions have different features and syntax rules. The `doctype` declaration helps the browser to interpret the HTML code correctly and display the web page as intended.

[how does the internet work?](https://www.linkedin.com/advice/1/what-purpose-html-doctype-declaration-skills-web-applications-vt25c)

[what is a markup language](https://en.wikipedia.org/wiki/Markup_language)

[how `<tags></tags>` work in html work](https://clearlydecoded.com/anatomy-of-html-tag)

[how attributes work in html #1](https://www.geeksforgeeks.org/html-attributes-complete-reference/)

[how attributes work in html #2](https://www.geeksforgeeks.org/html-attributes/)

[# Регулярные выражения (regexp) — основы](https://habr.com/ru/articles/545150/)

# Similar attributes

```
Here are some attributes that can be used almost interchangeably or are considered legacy alternatives:

1. Color-Related
- `bgcolor` = `style="background-color"`
- `color` = `style="color"`

2. Alignment
- `align` = `style="text-align"`
- `valign` = `style="vertical-align"`

3. Width/Height
- `width` = `style="width"`
- `height` = `style="height"`

4. Border
- `border` = `style="border"`

5. Spacing
- `cellpadding` (in tables) = `style="padding"`
- `cellspacing` (in tables) = `style="border-spacing"`

6. Font
- `face` = `style="font-family"`
- `size` = `style="font-size"`

Examples:
<!-- These are equivalent -->
<div bgcolor="red">
<div style="background-color: red;">

<table cellpadding="10">
<table style="padding: 10px;">

Note: While these work, modern web development strongly recommends using CSS instead of these legacy HTML attributes for better separation of concerns and maintainability.
```

# Priorities

Inline CSS has the highest priority(even than Id), then comes Internal/Embedded followed by External CSS which has the least priority.

Class selector have higher priority than internal/external css. 

Id selector have higher priority than class.

If you want to [read about it](https://www.w3schools.com/css/css_specificity.asp)

Also last think to say that the least priority is universal selector then default.

# Layouts

In short, here are four different techniques to create multicolumn layouts. Each technique has its pros and cons:

- CSS framework(If you want to create your layout fast, you can use a CSS framework(smth like Bootstrap))

- CSS float property(It is common to do entire web layouts using the CSS `float` property. **Advantages**:Float is easy to learn - you just need to remember how the `float` and `clear` properties work. **Disadvantages**: Floating elements are tied to the document flow, which may harm the flexibility)

- CSS flexbox(Use of flexbox ensures that elements behave predictably when the page layout must accommodate different screen sizes and different display devices)

- CSS grid(The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.)

If you want to [read about it](https://www.w3schools.com/html/html_layout.asp)

# Difference between:

```html
1).container > div  

2)div.container

3).container div
```

1)Targets **only `<div>` elements that are direct children of an element with the class `.container`**

2)Targets **any `<div>` element that has the class `.container`, regardless of its location or children**

3)Targets **all descendant `<div>` elements** of an element with the class `.container`, regardless of their depth in the DOM hierarchy

