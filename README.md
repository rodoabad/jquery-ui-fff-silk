jQuery UI FAMFAMFAM Silk
========================

FAMFAMFAM Silk icons for jQuery UI buttons.

Documentation
=============

Assuming you already have jQuery and jQuery UI installed and working properly.

1. Copy `fff-silk.png` to your image folder.
2. Copy `fff-silk.min.css` to your CSS folder. Remember to change the image URL to suit your needs (it defaults to ../img/fff-silk.png).
3. Add `fff-silk.min.css` after your jQUery UI CSS.

Usage
=====

Your element must have the `fff` class in order for the icons to show up. Then you can just use jQuery UI's button function.

Icon + No Text
-------

```html
<button id="icon-notext" class="fff">icon-notext</button>
```

```javascript
$('#icon-notext').button({
	text: false,
	icons: {
		primary: 'silk-icon-accept'
	}
});
```

Icon + Text
-----------

```html
<button id="icon-text" class="fff">icon-text</button>
```

```javascript
$('#icon-text').button({
	icons: {
		primary: 'silk-icon-application-home'
	}
});
```

Icon + Text + Icon
------------------

```html
<button id="icon-text-icon" class="fff">icon-text-icon</button>
```

```javascript
$('#icon-text-icon').button({
	icons: {
		primary: 'silk-icon-user-orange',
		secondary: 'silk-icon-asterisk-orange'
	}
});
```

Text + Icon
-----------

```html
<button id="text-icon" class="fff">text-icon</button>
```

```javascript
$('#text-icon').button({
	icons: {
		secondary: 'silk-icon-wrench-orange'
	}
});
```

Icon + Icon
-----------

```html
<button id="icon-icon" class="fff">icon-icon</button>
```

```javascript
$('#icon-icon').button({
	text: false,
	icons: {
		primary: 'silk-icon-cog',
		secondary: 'silk-icon-bullet-arrow-bottom'
	}
})
```

Thanks
======

* Mark James - Creator of the awesome FAMFAMFAM Silk icons!
* Dan Ryan - For inspiring me to make my own jQuery UI and FAMFAMFAM integration.