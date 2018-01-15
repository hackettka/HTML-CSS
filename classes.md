
# Classes and Ids

Classes and IDs can also assist with more fine-grained styling by allowing you to define your own selectors. The difference between classes and IDs is that IDs are unique used to identify one specfic element whereas a class are used to identify more than one.

Incorporating classes and IDs into the styling of your document includes two steps: first, some CSS code must be added to your stylesheet; second, some HTML code that refers to the CSS must be added to your HTML document. 

The code for CSS and HTML is different for classes and IDs.

Class selectors look like this - the name of the selector preceeded by a full stop:

```
.navbar {
	font-family: arial;
	background-color: yellow;
	color: navy;
}
```

and in HTML they are incorporated into elements like this:

```
<p class="navbar">
		<h1> Main Menu </h1>
		<ul> Some green text</p>
			<li> Home </li>
			<li> About </li>
			<li> Contact </li>
		</ul>
</p>
```

Id selectors look like this in the CSS - the name of the selector preceeded by a hashmark:

```
#green-text {
	color: green;
}
```

And in the HTML they are incorporated into elements like this:

```
<p id="green-text">
	<p>This is a paragraph and I want the text to be green.
</p>
```
<br/>
Tip: If you run into an error, be sure to check your punctuation. Often times it is a mistype, or overlooking a semi-colon, etc.
<br/>
<br/>
<br/>
[Previous](filter.md) | [Next](selectors.md)