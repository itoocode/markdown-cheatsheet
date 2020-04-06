# markdown-cheatsheet

## Markdown Basics

### Headlines, Paragraphs, and Basic formatting
---
### Headlines

# headline one # level 1
## headline/header tag level 2
### headline/header tag level 3
#### headline/header tag level 4
##### headline/header tag level 5
###### headline/header tag level 6

```md
hash(#) space title i.e. # Title
# headline one # level 1
## headline/header tag level 2
### headline/header tag level 3
#### headline/header tag level 4
##### headline/header tag level 5
###### headline/header tag level 6
```

## Paragraphs and line breaks

line break/new line and any sentence is a paragraph & **two spaces** at end for newline

this is a second sentence or paragraph/ 

for next para like some poem two space at end    
Lorem ipsum dolor sit amet consectetur  
adipisicing elit.
Repellendus dolorem laborum,  
dignissimos quas error rerum ea minima in ipsa  

Normal para --------atque eos repellat corrupti itaque? Praesentium eveniet incidunt sequi aut quia! repellat corrupti itaque? Praesentium eveniet incidunt sequi aut quia!repellat corrupti itaque? Praesentium eveniet incidunt sequi aut quia!


### Emphasis and Bolding

### Italics 

This *works* and this _works_ too. But use  1 asterisk(*) to italize , its preferred but github uses only * so be consistant with asterist .

```md
use *lorem* or _lorem_

This *works* and this _works_ too. But use  1 asterisk(*) to italize , its preferred but github uses only * so be consistant with asterist .
```

### Bolding

This **works** and this __works__ too. But use two asterisks

```md
This **works** and this __works__ too. But use two asterisks
```



### Blockquotes (> quote)

> this is a quote
>
> this is continuation of quote sequi aut quia! repellat corrupti itaque? Praesentium eveniet incidunt sequi aut quia!repellat corrupti itaque. - by [Google](http://google.com "link to google")
>
>

```md
> this is a quote
>
> this is continuation of quote sequi aut quia! repellat corrupti itaque? Praesentium eveniet incidunt sequi aut quia!repellat corrupti itaque. - by [Google](http://google.com "link to google")
>
>
```

```md
```

> other quote -- by name

```md
> other quote -- by name
```

### Horizontal lines/rules(---)  
---
___
***

```md
---
___
***
```

### Lists

#### numbered list

1. one
2. two
3. three

```md
1. one
2. two
3. three
```

---

1. other list
   1. inner list
   2. inter
      1. more inner
      2. other  
   3. inter
2. inn

```md
1. other list
   1. inner list
   2. inter
      1. more inner
      2. other  
   3. inter
2. inn
```

---

### Bulleted lists

* one
* two
* three

```md
* one
* two
* three
```

* blue 
* green
  * other
  * abcd
  * iddf
* red
* yellow
* ***Bulleted, italic, bold***

```md
* blue 
* green
  * other
  * abcd
  * iddf
* red
* yellow
* ***Bulleted, italic, bold***
```

*Italicized text*
*Item with no formating
* Bulleted item1


1. Item 1
   * item
   * item
2. item 2
    * Bulleted item
        1. item 1
        2. item 2



---

### code using backtics``

To install the latest version of NPM, you can type, `npm install npm@latest -g`

for block of code use three backtics 


```
    let addNums = (a, b) => {
        return a + b;
    }
```

Code with syntax highlight use three backtics with lang

```javascript

    let addNums = (a, b) => {
        return a + b;
    }

```
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```


```css

 :root {
  --blue-color: #6D6AE8;
  --white-text: #ffffff;
  --black-text: #000000;
  }

```
four spaces for code like

    //html is awesome and cool
    let addNums = (a, b) => {
        return a + b;
    }

---
##### html {#html-link}

### Links

```md
[Google](http://google.com)
link with title by " "
[Google](http://google.com "link to google")
```

[Google](http://google.com)
link with title by " "
[Google](http://google.com "link to google")


### Images

```md
![kittens](http://placekitten.com/400/200 "img title")

[![kitten](http://placekitten.com/200/300 "img alt text") ](http://google.com "link to google")
```

![kittens](http://placekitten.com/400/200 "img title")

[![kitten](http://placekitten.com/200/300 "img alt text")](http://google.com "link to google")

---
### Extendend syntax

#### *Tables*

```md
| Syntax | Description |
| --- | ----------- |
| Header | Title |
| Paragraph | Text |
```

| Syntax | Description |
| --- | ----------- |
| Header | Title |
| Paragraph | Text |


```md
with alignment by :---(left), :---:(center), :---(right)
| name | age | address |
| :--- | :---: | ---: |
| mahesh | 20 | hyd |
| ram | 21 | hyd |
| john | 22 | hyd |
```

with alignment by :---(left), :---:(center), :---(right)
| name | age | address |
| :--- | :---: | ---: |
| mahesh | 20 | hyd |
| ram | 21 | hyd |
| john | 22 | hyd |


### *Heading ids*

Linking to Heading IDs
You can link to headings with custom IDs in the file by creating a standard link with a number sign (#) followed by the custom heading ID.

lorem ipsum doler set amet [html](#html-link)

```md
##### html {#html-link}

Goto [html](#html-link)
```

#### Definition Lists
Some Markdown processors allow you to create definition lists of terms and their corresponding definitions. To create a definition list, type the term on the first line. On the next line, type a colon followed by a space and the definition.

```md
First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.
```

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.


#### Task Lists
Task lists allow you to create a list of items with checkboxes. In Markdown applications that support task lists, checkboxes will be displayed next to the content. To create a task list, add dashes (-) and brackets with a space ([ ]) in front of task list items. To select a checkbox, add an x in between the brackets ([x]).

```md
- [x] learn md
- [ ] code 
- [x] learn html and css
```

- [x] learn md
- [ ] code 
- [x] learn html and css


---




