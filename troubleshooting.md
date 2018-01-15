# Trobuleshooting

It is common - especially in the beginning - that you'll add or amend something to/in your text editor, but it won't present when rendered by your browser. 

The first inclination is to scan the text in your editor for errors. Nesting will help tremendously with this task. Often times it is as little as forgetting a semi-colon, or closing tag. 

<p>
Another investigative tactic is to <strong> `View Page Source`</strong>. 
<ul>
	<li> If you think its an error with the HTML, you'll be able to see it there. </li>
	<li> If you think its an error with the CSS, then from the `Page Source` you'll need to click on the link for the `style.css` page. The link to this page should be found in the head of your page (if its not, that may be the problem!). By opening that link, you'll be able to the code that broswer is applying to your HTML. It should match what you have in your text editor. If it looks like an earlier version of your style sheet, then maybe you need to re-save the document.</li>
</ul>
</p>

<br/>
<br/>
<br/>
[<<<Previous<<<](creating_stylesheet.md) | [>>>Next>>>](resource.md)