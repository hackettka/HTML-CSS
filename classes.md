
# Classes and ids

Classes and IDs can also assist with more fine-grained styling by allowing you to define your own selectors. The difference between classes and IDs is that IDs are used to identify one element whereas a class are used to identify more than one.

Incorporating classes and IDs into the styling of your document includes two steps: first, some CSS code must be added to your stylesheet; second, some HTML code that refers to the CSS must be added to your HTML document. 

The code for CSS and HTML is different for classes and IDs.

Class selectors look like this - the name of the selector preceeded by a full stop:

```
.green-text {
	color: green;
}
```

and in HTML they are incorporated into the `<div>` element like this:

```
<div class="green-text">
	<p>Some green text</p>
</div>
```

Id selectors look like this in the CSS - the name of the selector preceeded by a hashmark:

```
#green-text {
	color: green;
}
```

And in the HTML they are also incorporated into the `<div>` element like this:

```
<div id="green-text">
	<p>Some green text</p>
</div>
```
<br/>
<br/>
<br/>
[<<<Previous<<<](filter.md) | [>>>Next>>>](selectors.md)