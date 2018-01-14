# Links

Links are another important component of most websites. Links can help you move between the different webpages on your site (sometimes in the form of a menu or navigation bar), or help you connect to other resources or information on other websites.

The `<a>` tag, or anchor tag, creates the link to another document. You can use the `<a>` tag to link to other documents or webpages you created for the same site or to documents or webpages created by other web users. 

## OPTION 1: Linking to your own documents

The following appears as a link to the `about.html` page on the same site: 

```
<a href="about.html">About</a>
```

On your webpage it will appear as:

[About](about.html)  

Note that by adding this to your `index.html` file, this pathway is asking the browser to look for a file titled `about.html` in the same folder. 

## OPTION 2: Linking to other pages/sites

```
<a href="http://www.google.com">Google</a>
```

On your webpage it will appears as:

<a href="http://www.google.com">Google </a>

This pathway is directing your browser to look online for this text document at the URL address provided.

Each example above also includes `href`. `href`, short for hypertext reference, is an "attribute" which offers secondary information to your browser. 

In other words, when your browser is reading the code above, the `<a>` tag first indicates that the following text will include a link (primary information), while the `href` tells the browser where the link can be found (secondary information).

There is another technical difference between the two options above. Option 1 is called a `relative` link because the link  describe the URL in relation to the page you're on. Option 2 is called an `absolute` link because it describes the URL as a separate entity, requiring that the the whole URL be included.

### Best Practice Tip: 
Use relative links when referring to pages on your own site. This will prevent links from breaking should you decide to move your site.

## Activity:
In your `index.html` file, add a relative link to your About page. Re-save that document and re-open it in your broswer - you can refresh the page if you still have it open, or re-open it from your desktop.

Also add a relative link from your About page to your `index.html` page. Call this page `Home`.

Lastly, include an absolute link to a page of your choosing.
<br/>
<br/>
<br/>
[<<<Previous<<<](p_and_h.md) | [>>>Next>>>](images.md)