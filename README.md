`js-toolbox` is a set of components and methods to ease developments in JS and avoid duplication.

# Astiloader

In the `<head>` of your HTML, reference the location of both `.css` and `.js` files:

```html
<link rel="stylesheet" href="path/to/astiloader.css"/>
<script src="path/to/astiloader.js"></script>
```

Then call the `.init()` method:

```javascript
asticode.loader.init()
```

When you want to show the loader call the `.show()` method, when you want to hide it call the `.hide()` method:

```javascript
asticode.loader.show()
asticode.loader.hide()
```

It requires [fontAwesome](http://fontawesome.io).

# Astinotifier

In the `<head>` of your HTML, reference the location of both `.css` and `.js` files:

```html
<link rel="stylesheet" href="path/to/astinotifier.css"/>
<script src="path/to/astinotifier.js"></script>
```

Then call the `.init()` method:

```javascript
asticode.notifier.init()
```

When you want to notify the user call one of the following:

```javascript
asticode.notifier.error("this is an error");
asticode.notifier.info("this is an info");
asticode.notifier.success("this is a success");
asticode.notifier.warning("this is a warning");
```

It requires [fontAwesome](http://fontawesome.io).