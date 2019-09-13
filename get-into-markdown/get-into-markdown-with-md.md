---
description: Markdown is a plain text format markup language.
---

# Use MARKDOWN within \*.md

## **WITHIN the LINE**

### 1. Fonts

1.  Bold &lt;**text**>

    `<**text**> or <**text**>`

2.  Oblique &lt;_text_>

    `<*text*> or <_text_>`

3.  Bold &  Oblique &lt;_**text**_>

    `<**_text_**>or <***text***>or <___text___>`

4.  Line through text &lt;~~text~~>

    `<~~text~~>`

### 2. Header 1-6

\*Font can be apply to headers

```text
  ###### H6 6th Title
  ##### H5 5th Title
  #### H4 4th Title
  ### H3 3rd Title
  ## H2 2nd Title
  # H1 1st Title
```

### 3. Divider

Use **3** or more "**\***,**-**,**\_**" to create a divider. \*Symbol doesn't matter, the output turns out in same format.

### 4. Coding

#### **4.1 Code Highlight**

Use '`~Lowerkey`' at beginning & the end of the selected highlight area.

**4.2 Code Reference**

1.  Use "TabKey"^1 or "SpaceKey"^4
2.  **recommend** Use "`~Lowerkey x3`" at the beginning and end of the codes to complete the section. eg.:

    ```java
    public abstract class L2Character extends L2Object {
     public static final Short ABNORMAL_EFFECT_BLEEDING = 0x0_0_0_1; // not sure
     public void moveTo(int x, int y, int z) {
       _ai = null;
       _log.warning("Should not be called");
       if (1 > 5) {
         return;
       }
     }
     /** Task of AI notification */
     @SuppressWarnings( { "nls", "unqualified-field-access", "boxing" })
     public class NotifyAITask implements Runnable {
       private final CtrlEvent _evt;

       List mList = new ArrayList()

       public void run() {
         try {
           getAI().notifyEvent(_evt, _evt.class, null);
         } catch (Throwable t) {
           t.printStackTrace();
         }
       }
     }
    }
    ```

    ```javascript
    var s = "JavaScript syntax highlighting";
    alert(s);
    ```

    ```python
    s = "Python syntax highlighting"
    ```

## **INSERT**

### 1. Insert Blockquotes

1.1 Insert ">""+"quote".

> eg. 1. quote

1.2 Insert ">>""+"quote"

> > eg. 2. quote

\*\* _note: code reference can also be used in the Blockquote._

>     by using `quote`
>
> eg. 3. `quote`

### 2. Insert Lists

**2.1 Common lists**

list can be maked by **"+,\*,-"**+ **"space"**, thay all turns out the same output.

> eg.
>
> -   This line used '-'
> -   This line used '+'
> -   This line used '\*'

#### **2.2 Numbered Lists**

\* _no matter what number are used for input, the output will followed Algebra order._

eg.:

> `1.`+  `` +`Text`
>
> `9.`+ ``+`Text`
>
> `0.`+ ``+`Text`
>
> > Get :
> >
> > 1.  text
> > 2.  text
> > 3.  text

#### **2.3 Task Lists**

To create a task list, add dashes and brackets with a space, marked as " `-`+``+`[ ]` "in front of task list items.   

> eg.:
>
> > Insert:
> >
> >         - [ ] Write the press release
> >         - [ ] Update the website
> >         - [ ] Contact the media
> >
> > get:
> >
> > -   [ ] Write the press release
> > -   [ ] Update the website
> > -   [ ] Contact the media

To select a checkbox, add an x in between the brackets ([x]).

> eg.:
>
> > Insert
> >
> >         - [x] Write the press release
> >         - [ ] Update the website
> >         - [ ] Contact the media
> >
> > get:
> >
> > -   [x] Write the press release
> > -   [ ] Update the website
> > -   [ ] Contact the media

### 3. Insert Links

**3.1 Insert link to Texts**

There are two type of method to insert link in to text \*Font can be apply to link text

1.  format :**\[text]+(link**+**"Explain")** eg.:

> _**Insert**_
>
> ```text
>   [Markdown语法说明](https://markdown.tw/#link "悬停解释")
> ```
>
> _**Get**_
>
> > [Markdown语法说明](https://markdown.tw/#link)

2.  format :**\[text]+\[mark]**+ **{\[mark]: link** +**"Explanation** ~~**if capable**~~**"}**\* can be insert at anyplace within the file eg.:

> _**Insert**_:
>
> ```text
> [Markdown语法说明][Markdown]
> [Markdown]:https://markdown.tw/#link "悬停解释"
> ```
>
> > _**Get**_: [Markdown语法说明](https://markdown.tw/#link)

**3.2 Image Links**

To insert a image link we use "!" at beginning of the link formula

1.  Format : **!**+**\[name]**+**(link**+**“Explanation”)** eg.:

    > _**Insert**_:
    >
    > ```text
    > ![Image](https://sourceforge.net/images/icon_linux.gif “悬停解释”)
    > ```
    >
    > > _**Get**_: ![悬停解释](https://sourceforge.net/images/icon_linux.gif)

2.  Format : **!**+**\[name]+\[mark]**+**\[spaceline]**+**{\[mark]: @ anyplace**+**"Explanation"}**

    eg.:

    > _**Insert**_:
    >
    > ```text
    > ![Image]\[example]
    > (spaceline)
    > [example]:https://sourceforge.net/images/icon_linux.gif "悬停解释"
    > ```
    >
    > > _**Get**_: ![悬停解释](https://sourceforge.net/images/icon_linux.gif)

### 4. Insert Footnote

Use **texts**++ Insert **: Explanation** anyplace in the file eg.:

> **Insert**
>
> ```text
>     Lynne [1]
>     [1]:Huskyowner
> ```
>
> > **Get**: Lynne [1](Huskyowner)

### 5. Insert Tables

In general, 1st line is for Title, 2nd line is for separating Title & Body \*At second line, When Diving the columns, use ":-:" to set texts in the middle; "-:" to the right.

**5.1.1 Simple Method Tables**

**Insert**：

```text
left|middle|right
-|-|-
2|3|4
```

**Get**:

| left | middle | right |
| :--- | :----- | :---- |
| 2    | 3      | 4     |

**5.1.2 Regular Method Tables**

**Insert**

```text
|left|middle|right|
|-|-|-|
|2|3|4|
```

**Get**:

| lift | middle | right |
| :--- | :----- | :---- |
| 2    | 3      | 4     |

#### **5.2 Advanced Tables**

**Insert**

```text
|left|middle|right|
|-|:-:|-:|
|1|2|3|
|4|5|6|
|7|8|9|
```

**Get**:

| left | middle | right |
| :--- | :----: | ----: |
| 1    |    2   |     3 |
| 4    |    5   |     6 |
| 7    |    8   |     9 |

## **STUDY REFERENCE**

### _In English_:

[Markdown: Syntax](https://daringfireball.net/projects/markdown/syntax) \| [bramp/js-sequence-diagrams](https://bramp.github.io/js-sequence-diagrams/) \| [adrai/flowchart-js](https://github.com/adrai/flowchart.js)

### _In Chinese_:

[Demi的随笔和技术空间](https://yuhongjun.github.io/tech/2017/05/02/Markdown-语法手册-完整整理版.html) \| [Markdown 中文文档](https://markdown-zh.readthedocs.io/en/latest/) \| [Markdown使用笔记](https://frankbing.gitbooks.io/markdown/) \| [markdown-syntax-zhtw](https://github.com/othree/markdown-syntax-zhtw/blob/master/syntax.md)
