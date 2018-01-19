
# Classes and Ids

Classes and IDs can also assist with more fine-grained styling by allowing you to define your own selectors. The difference between classes and IDs is that IDs are unique used to identify one specfic element whereas a class are used to identify more than one.

Incorporating classes and IDs into the styling of your document includes two steps: first, some CSS code must be added to your stylesheet; second, some HTML code that refers to the CSS must be added to your HTML document. 

The code for CSS and HTML is different for classes and IDs.

Class selectors look like this - the name of the selector preceeded by a full stop:

```
.intro {
	font-family: arial;
	background-color: grey;
	color: dark grey;
}
```

...and in HTML they are incorporated into elements like this:

```
<p class="intro">
		This is my introduction to my paragraph and I want to be distinguished from the rest of my content so I will add it as a class and note where the intros are found in my HTML.
</p>
```

Id selectors look like this in the CSS - the name of the selector preceeded by a hashmark:

```
#navbar {
	background-color: yellow;
	passing: 80px
}
```

...and in the HTML they are incorporated into elements like this:

```
<ul id="navbar">
	<li> Home </li>
	<li> About </li>
</ul>
```
<br/>
Tip: If you run into an error, be sure to check your punctuation. Often times it is a mistype, or overlooking a semi-colon, etc.
<br/>
<br/>
<br/>
[<<<Previous<<<](filter.md) | [>>>Next>>>](selectors.md)