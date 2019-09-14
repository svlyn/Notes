# 2. **HTML ELEMENTS**

## 2.1. HTML TAG

-   Browsers do not display the HTML tags, But Tags labled content for page structure such as "heading", "paragraph", "table", etc.
-   Tags normally come in pair, they have same name, but the end tag always start with a extra "/".

![tagsample](../.gitbook/assets/simple-p-tag.png)

-   Tags should be closed properly, before you start work on next tag, you have to close the current one. (There is some exceptions, see [Open Tags](<>).)

![tagformat](../.gitbook/assets/close-opened-tags-first.png "tags")

> HTML elements is everything from the _**start tag**_ to the _**end tag**_. They used for group and labelling the context, define and render the content to text.
>
>  Format: **`<starttag>`**`content`**`</endtag>`**
>
> > eg:
> >
> > ```HTML
> > <body>......</body>
> > <p>......</p>
> > <div>......</div>
> > <b>......</b>
> > ```

Tags normally come in pair, they have same name, but the end tag always start with a extra "/".

> Format: **`<tagname attribute>`**`content`**`</tagname>`**
> Open Tag Format: **`<tagename....../>`**
>
> > eg:
> >
> > ```HTML
> > <br />
> > <img src="..." />
> > <input type="..." />
> > ```

#### 2.1.1.

## 2.2.HTML Attribute

> -   **A tag could contain many attribute inside.**  
> -   Always use **quotation mark** to wrap up the _**value**_ content in HTML Attribute.
>     > Format: `<tagname`**`name="value">`**`content</tagname>`
>
> #### 2.2.1 The `lang` Attribute

The **language** of the document can be declared in the `<html>` tag. The language is declared with the `lang` attribute.

```text
<html lang=en_us> </html>
```

#### 2.2.2 The `title` Attribute

Here, a `title` attribute is added to the `<p>` element. The value of the title attribute will be displayed as a tooltip when you mouse over the paragraph:

    <!DOCTYPE html>
    <html>
        <body>
            <h2 title="I'm a header">The title Attribute</h2>
            <p title="I'm a tooltip">Mouse over this paragraph, to display the title attribute as a tooltip.
            </p>
        </body>
    </html>

#### 2.3.3 The `style` Attribute

The `style` attribute is used to specify the styling of an element, like color, font, size etc.

    <html>
    <body style="background-color:yellow">
        <h2 style="background-color:red">This is a heading</h2>
        <p style="background-color:green">This is a paragraph.</p>
    </body>
    </html>

#### 2.3.4 The `href` Attribute

HTML links are defined with the `<a>` tag. The link address is specified in the `href` attribute:

    <a href="url">Link text</a>

#### 2.3.5 The `src` Attribute

HTML images are defined with the `<img>` tag. The filename of the image source is specified in the `src` attribute:

    <img src="url" />

#### 2.3.6 The width and height Attributes

Images in HTML have a set of **size** attributes, which specifies the width and height of the image:

    <img src="url" width="500" height="600" />

#### 2.3.7 The alt Attribute

The `alt` attribute specifies an alternative text to be used, when an image cannot be displayed.
