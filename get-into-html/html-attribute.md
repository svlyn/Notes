## 2.2.HTML Attribute

> -   **A tag could contain many attribute inside.**  
> -   Always use **quotation mark** to wrap up the _**value**_ content in HTML Attribute.
> Format: `<tagname`**`name="value">`**`content</tagname>`
>
> eg.: Attributes are applied to the tag `<p>`, where the`align`is name, and `”left”, “center”,”right”`are values.
> 
>  ```html
> <!DOCTYPE html> 
> <html>
>    <head> 
>       <title>Align Attribute  Example</title> 
>    </head>
>    <body> 
>       <p align = “left”>This is left aligned</p> 
>       <p align = “center”>This is center aligned</p> 
>       <p align = “right”>This is right aligned</p> 
>    </body>
> </html>
> ```

#### 2.2.1 The `lang` Attribute

The **language** of the document can be declared in the `<html>` tag. The language is declared with the `lang` attribute.

```html
    <html lang=en_us> </html>
```

Value options are using the **Language Codes: ISO 639, Microsoft**


#### 2.2.2 The `title` Attribute

Here, a `title` attribute is added to the `<p>` element. The value of the title attribute will be displayed as a tooltip when you mouse over the paragraph:

```HTML
<!DOCTYPE html>
    <html>
        <body>
            <h2 title=“I’m a header”>The title Attribute</h2>
            <p title=“I’m a tooltip”>Mouse over this paragraph, to display the title attribute as a tooltip.
            </p>
        </body>
    </html>
```

#### 2.3.3 The `style` Attribute

The `style` attribute is used to specify the styling of an element, like color, font, size etc.

```HTML
    <body style=“background-color:yellow”>
        <h2 style=“background-color:red”>This is a heading</h2>
        <p style=“background-color:green”>This is a paragraph.</p>
    </body>
```

#### 2.3.4 The `href` Attribute

HTML links are defined with the `<a>` tag. The link address is specified in the `href` attribute:


```HTML 
    <a href=“url”>Link text</a>
```

#### 2.3.5 The `src` Attribute

HTML images are defined with the `<img>` tag. The filename of the image source is specified in the `src` attribute:

 
```   HTML
    <img src=“url” />
```

#### 2.3.6 The width and height Attributes

Images in HTML have a set of **size** attributes, which specifies the width and height of the image:


```HTML
    <img src=“url” width=“500” height=“600” />
```
#### 2.3.7 The alt Attribute

The `alt` attribute specifies an alternative text to be used, when an image cannot be displayed.
