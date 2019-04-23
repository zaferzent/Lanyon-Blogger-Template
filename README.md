# Lanyon

Lanyon is an unassuming [Blogger](http://blogger.com) template that places content first by tucking away navigation in a hidden drawer. 

![Lanyon](https://f.cloud.github.com/assets/98681/1825266/be03f014-71b0-11e3-9539-876e61530e24.png)
![Lanyon with open sidebar](https://f.cloud.github.com/assets/98681/1825267/be04a914-71b0-11e3-966f-8afe9894c729.png)


## Contents

- [Usage](#usage)
- [Options](#options)
  - [Sidebar menu](#sidebar-menu)
  - [Themes](#themes)
  - [Reverse layout](#reverse-layout)
- [Author](#author)


## Usage

Only available on Blogger / Blogspot based blogs. Install `Blogger dashboard > Template > Edit HTML` or `Blogger dashboard > Template > Backup / Restore`

## Options

Lanyon includes some customizable options, typically applied via classes on the `<body>` element.


### Sidebar menu


```html
<!-- Toggleable sidebar -->
<div class='sidebar' id='sidebar'>
<div class='sidebar-item'>
<p>A reserved <a href='http://blogger.com' target='_blank'>Blogger</a> theme that places the utmost gravity on content with a hidden drawer. Made by <a href='https://twitter.com/zaferzent' target='_blank'>@zaferzent</a>.</p>
</div>
<nav class='sidebar-nav'>
<a class='sidebar-nav-item active' href='/'>Home</a>    
<a class='sidebar-nav-item' href='/p/about.html'>About</a>
<a class='sidebar-nav-item' href=''>Contact</a>
<a class='sidebar-nav-item' href='https://github.com/zaferzent'>GitHub project page</a>
<span class='sidebar-nav-item'>Lanyon Template v1.0.</span>
<span class='sidebar-nav-item'>Blogger Adapted by Zafer Zent</span>
</nav>
<div class='sidebar-item'>
<p>
&amp;copy; 2019. All rights reserved.
</p>
</div>
</div>
```


### Themes

Lanyon ships with eight optional themes based on the [base16 color scheme](https://github.com/chriskempson/base16). Apply a theme to change the color scheme (mostly applies to sidebar and links).

![Lanyon with red theme](https://f.cloud.github.com/assets/98681/1825270/be065110-71b0-11e3-9ed8-9b8de753a4af.png)
![Lanyon with red theme and open sidebar](https://f.cloud.github.com/assets/98681/1825269/be05ec20-71b0-11e3-91ea-a9138ef07186.png)

There are eight themes available at this time.

![Available theme classes](https://f.cloud.github.com/assets/98681/1817044/e5b0ec06-6f68-11e3-83d7-acd1942797a1.png)

To use a theme, add any one of the available theme classes to the `<body>` element in the `default.html` layout, like so:

```html
<body class="theme-base-08">
  ...
</body>
```

To create your own theme, look to the Themes section of [included CSS file](https://github.com/poole/lanyon/blob/master/public/css/lanyon.css). Copy any existing theme (they're only a few lines of CSS), rename it, and change the provided colors.


### Reverse layout

![Lanyon with reverse layout](https://f.cloud.github.com/assets/98681/1825265/be03f2e4-71b0-11e3-89f1-360705524495.png)
![Lanyon with reverse layout and open sidebar](https://f.cloud.github.com/assets/98681/1825268/be056174-71b0-11e3-88c8-5055bca4307f.png)

Reverse the page orientation with a single class.

```html
<body class="layout-reverse">
  ...
</body>
```


### Sidebar overlay instead of push

Make the sidebar overlap the viewport content with a single class:

```html
<body class="sidebar-overlay">
  ...
</body>
```

This will keep the content stationary and slide in the sidebar over the side content. It also adds a `box-shadow` based outline to the toggle for contrast against backgrounds, as well as a `box-shadow` on the sidebar for depth.

It's also available for a reversed layout when you add both classes:

```html
<body class="layout-reverse sidebar-overlay">
  ...
</body>
```

## Author

**Zafer Zent**
- <https://github.com/zaferzent>
- <https://twitter.com/zaferzent>
