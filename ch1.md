# First level header
## Second level header
### Third level header
#### Fourth level header
##### Fifth level header
###### Sixth level header
```
Above code get converted in to HTML
<h1> First level header </h1>
<h2> Second level header </h2> 
 ....
```

We can also define first level header using ===
====

There one more way to define second level header using ----. For rest of the heading we need to use # like above example
-----

How we can define paragraph in Markdown language easily? To answerer to this question is very simple and here while talking we have crated a paragraph in Markdown language see how simple this is.

Its super easy let me define one more paragraph. Created a paragraph. I am in love with Markdown its super easy can't be other languages become super easy.

```
Output will be:
<p> How we can define paragraph ...</p>
<p>Its super easy let me define one ...</p>
```

> How we can define blockquote hmm its also seems easy.

> Let me create one more blockquote. Really its super easy. Can we define heading in blockquote? Lets try.

```
<blockquote>
    <p> How we can define blockquote...</p>
</blockquote>
<blockquote>
    <p> Let me create one more blockquote...</p>
</blockquote>
```
> ## Second level heading 
> Yes we can define all level heading with in blockquote wow its really amazing like amazing spider man...wait a minute what the hell are you talking.

```
<blockquote>
    <h2> Second level heading</h2>
    <p> Yes we can define all level heading...</p>
</blockquote>
```

How we can **emphasized** text ? Is *there* any way to do _this_. Yes its __seems__ that we can do this and its very simple. Have is said simple? 
```
How we can <strong>emphasized</strong> text ? Is <em>there</em> any way to do <em>this</em>. Yes its <strong>seems</strong> that we can do this...
```
How we can create list is there any way to do so. Yes there are three way to do so we can use + - and * to create list.
+ first list item
+ list item 2
+ list item 3

- first list item
- list item 2
- list item 3

* first list item 
* list item 2
* list item 3
```
All above code will produce same output.
<ul>
    <li>first list item</li>
    <li>list item 2</li>
    <li>list item 3</li>
</ul>
```
Wow unordered list creation is amazing. Is there any way to create ordered list? Yes we can also create ordered list in similar way.

1. first list item
2. list item 2
3. list item 3

```
Above code output wll be:
<ol>
    <li>first list item</li>
    <li>list item 2</li>
    <li>list item 2</li>
</ol> 
```

Wow learned to many things heading, paragraph, blockquote, strong, ordered list, unordered list etc. Is there any way to define link. Like wanted to add hyperlink to [google](https://www.google.com/ "google link title").   Title tag is optional here. You can also use [Google][1], [MSN][3] and [Yahoo][2]

[1]: https://www.google.com "Google title"
[2]: https://www.yahoo.com
[3]: https://msn.com

Is there any other way to refer links. Yes see the [Google][test] example again.

[test]:https://www.google.com

```
<p>Wow learned to many things ....to add hyperlink to <a href="https://www.google.com/" title="google link title">google</a> Title tag is optional here.  
```

Lets add image here ![alt text](https://madskristensen.gallerycdn.vsassets.io/extensions/madskristensen/markdowneditor/1.12.233/1522879595588/Microsoft.VisualStudio.Services.Icons.Default) we can also use references to add image like we did for anchor tag. ![alt text goes here][reference]

[reference]: https://madskristensen.gallerycdn.vsassets.io/extensions/madskristensen/markdowneditor/1.12.233/1522879595588/Microsoft.VisualStudio.Services.Icons.Default "title goes here"