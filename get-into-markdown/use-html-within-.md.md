# Use HTML within \*.md

## **WITHIN the LINE**

### 1. Fonts

1.  Bold &lt;**text**>

    `<strong>text</strong> or <b>text</b>`

2.  Oblique &lt;_text_>

    `<em>text</em> or <i>text</i>`

3.  Bold &  Oblique  &lt;_**text**_>

    `<strong><em>text</em></strong> or <i><b>text</b></i>`

4.  Line through text &lt;~~text~~>

    `<striket>text</striket>`

### 2. Header 1-6

  Font can be apply to headers

```text
<h1>一级标题</h1>
<h2>二级标题</h2>
<h3>三级标题</h3>
<h4>四级标题</h4>
<h5>五级标题</h5>
<h6>六级标题</h6>
```

### 3. Divider

```text
<hr></hr> or <hr />
```

### 4. Coding

#### **4.1  Code Block**

```text
<code>Insert codes here</code>
```

**4.2 Teletype Style**

```text
<tt>text</tt>
```

## **INSERT**

### 1. Insert Quotes

`Format: <blockquote>This is a quote.</blockquote>`

> This is a quote.

### 2. Insert Lists

**2.1 Common lists**

\*use`<ul>`to start a list, `<li></li>`for each tab.

> eg.:
>
>  Insert:
>
> ```text
> <ul>
>     <li>Coffee</li>
>     <li>Milk</li>
> </ul>
> ```
>
> Get:
>
> -   Coffee
> -   Milk

#### **2.2 Numbered Lists**

use`<ol>`to start a list, `<li></li>`for each tab.

> eg.:
>
>  Insert:
>
> ```text
> <ol>
>     <li>Coffee</li>
>     <li>Milk</li>
> </ol>
> ```
>
> Get:
>
> 1.  Coffee
> 2.  Milk

#### 2.3 Custom Lists

use`<dl>`to start a list, `<dt></dt>`for each tab,`<dd></dd>`for descriptions.

> Insert:
>
> ````<dl>
>                           <dt>Coffee:</dt>
>                           <dd>Black hot drink</dd>
>                           <dt>Milk:</dt>
>                           <dd>White cold drink</dd>
>                     </dl>```
>
>             Get:
>
>             <dl>
>                   <dt>Coffee:</dt>
>                   <dd>Black hot drink</dd>
>                   <dt>Milk:</dt>
>                   <dd>White cold drink</dd>
>               </dl>
> ````

### 3. Insert Links

**3.1 Insert link to Texts**

format : `<a herf=` + "link address" +  `` +  `title=` "悬停解释"+ `>` + text + `</a>`

> _**eg.:**_
>
> _**Insert**_
>
> ```text
>   <a href="http://google.com/" title= >Google</a>
> ```
>
> _**Get:**_ [Google](http://google.com/)
>
> **\***Title & Alt address are optional.

**3.2 Image Links**

Format : `<img src=`+" image address"+  ``+ `alt=`"悬停解释"+`` +  `title=` "悬停解释"+`"/>`

> _**eg.:**_
>
> _**Insert**_:
>
> ```text
> <img src="https://sourceforge.net/images/icon_linux.gif" alt="name" title="悬停解释"/>
> !
> ```
>
> > _**Get**_: ![悬停解释](https://sourceforge.net/images/icon_linux.gif)
>
> **\***Title & Alt address are optional.

## **STUDY REFERENCE**

### _In English_:

[Markdown: Syntax](https://daringfireball.net/projects/markdown/syntax) \| [Markdown Guide](https://markdown-guide.readthedocs.io/en/latest/basics.html#lists-simple) \|

### _In Chinese_:

[Markdown 中文文档](https://markdown-zh.readthedocs.io/en/latest/) \|  [markdown-syntax-zhtw](https://github.com/othree/markdown-syntax-zhtw/blob/master/syntax.md) \|
