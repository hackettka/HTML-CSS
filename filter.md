
# Filtering

CSS has an automatic filtering function where the most specific rule in CSS always takes precedence. 

So if your stylesheet contained the following rule sets, then the text of your paragraph would be green, but where the strong tag is found in the paragrach, the text would be red. This would occur regardless of the order these rule sets appear in the stylesheet.

```
p {
	color: green;
}
```
```
p strong {
	color: red;
}
```
<br/>
<br/>
<br/>
[<<<Previous<<<](rules.md) | [>>>Next>>>](classes.md)