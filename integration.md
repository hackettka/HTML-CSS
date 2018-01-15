# Integrating CSS and HTML

CSS can be integrated into your HTML in three ways. 

## Option 1: Inline

Inline styling adds CSS directly into the HTML of a page to adjust the style of particular parts of a page. For example, if you want your first paragraph to be red, but your second paragraph to be blue: 

```
<!DOCTYPE html>
<html lang="en">
<head>
	<title>About</title>
</head>
<body>
	<p style="color: red">
	Content of paragraph
	</p>
    <p style="color: blue">
    Content of paragraph
    </p>
</body>
</html>
```

## Option 2: Internal

Internal styling also adds the CSS into the HTML, but keeps it separate from the content code of the page by adding it into the head using the `<style>` tag. When using internal styling you are providing styling rules for the entire page. For example, if you want all headings to be blue:

```
<!DOCTYPE html>
<html lang="en">
<head>
	<title>About</title>
    <style>
    h1 {
        color: blue;
    }
    </style>
</head>
<body>
    <h1>
    Heading 
    </h1>
	<p>
	Content of paragraph
	</p>
</body>
</html>
```

## Option 3: External

External styling creates a separate stylesheet for your CSS that will be linked to your html in the head section of your html document using the code below. The CSS file should be named stlye.css and must be stored in the same file as the html document it is linked to.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>CSS Example</title>
    <link rel="stylesheet" href="style.css">
```

## Important
With CSS, and without additonal code, the the more specific rules always take precedent. This applies to integrating CSS too. If you link to an external stylesheet, and you add inline or internal CSS into your HTML, the inline or internal CSS will override the rules set in the external stylesheet. 

## Best Practices:
Option 3, external styling, is preferred by most web developers because it is considered best practice to keep your HTML document 'presentation' free. 

## Activity
Open up a new document in your Sublime Text editor. Save the document to the same folder as your HTML documents and title it `style.css`. In your `index.html` document, add in the link to our style sheet and re-save the file. Be sure to add it in the correct place in the code. 
<br/>
<br/>
<br/>
[<<<Previous<<<](css_basic.md) | [>>>Next>>>](rules.md)