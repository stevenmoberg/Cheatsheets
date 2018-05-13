# Html Cheatsheet

## Purpose
*Help as a reference while teaching kids through [FreeBootCamp.org](https://freebootcamp.org)*

## Table of Contents

1. [Links](#links)
1. [Element](#element)
1. [Nesting Elements](#nesting)
1. [Attributes](#attribute)
1. [Summary](#summary)



## [Links](#links)
* [TutorialsPoint.com](https://www.tutorialspoint.com/html/html_elements.htm)

## [Element](#element) (html tag)
An **HTML element** is defined by a starting tag. If the element contains other content, it ends with a closing tag, where the element name is preceded by a forward slash as shown below with few tags

| Start Tag	 | Content | End Tag
|-|-|-
|`<p>`       | This is paragraph content. |`</p>`
|`<h1>`	     | This is heading content.	  |`</h1>`
|`<div>`     | This is division content.  |`</div>`
|`<br />`    |                            |


## [Nesting Elements](#nesting)

Html elements can be nested and requires a closing tag.<br/>


```html
<!DOCTYPE html>
<html>
   <head>
      <title>Nested Elements Example</title>
   </head>
   <body>
      <h1>This is <i>italic</i> heading</h1>
      <p>This is <u>underlined</u> paragraph</p>
      <div>
         <div>
            <p>
              <span>blah</span>
              <img src="http://images/cats.jpg" />
            </p>
         </div>
      </div>
   </body>
</html>
```

## [Attributes](#attribute)

An attribute is used to define the characteristics of an HTML element and is placed inside the element's opening tag. All attributes are made up of two parts − a *property* and a *value*

```html
<input
    id="name"
    class="form-control big-text"
    name="name"
    type="text"
    placeholder="full name"
    value="Steven Moberg"
    onchange="alert(this.value)"
    style="color: blue"
    data-custom-attribute="custom property"
    required
    />
```

## [Summary](#summary)

Simple tag with ***content*** = "Hello World"
> `<h1>`**Hello World**`</h1>`

A self-closing ***input*** element
> `<`**input** ` id="name" type="text" value="Steve Moberg" ` **/**`>`

Attributes are written within the opening tag as ***attribute="value"***
> `<input ` **id**`="name" ` **type**`="text" ` **value**`="Steve Moberg" />`

The ***id*** attribute uniquely identifies an element and used for CSS styling and JavaScript
> `<input ` **id**`="name" type="text" value="Steve Moberg" />`

The ***name*** attribute on a form element identifies the value posted to the server
> `<input id="name" ` **name**`="name" type="text" value="Steve Moberg" />`

All non-closing html elements can be nested
> `<`**div** ` class="row">`<br/>
> &emsp;`<`**div** ` class="col-xs-4">`<br/>
> &emsp;&emsp;`<`**input** ` type="text" name="name" />`<br/>
> &emsp;`<`**/div**`>`<br/>
> `<`**/div**`>`



