# Hello-World
Let us start learning how to use Markdown.

Here we will learn the basic syntax at first.
## Header
* Use the character '#' to build a header.
* You can use one `#` all the way up to `######` six for different heading sizes.

e.g.

`#### THis is a header tag`

#### THis is a header tag
## Emphasis
* There are two ways to emphasize words:bold and italic.
  * italic: Wrap the sentence with a pair of * * or _ _
  * bold:Wrap the sentence with a pair of ** ** 
```
*italic* or _italic_
```

*italic* or _italic_

`**the text will be bold**`

**the text will be bold**

You can also use them in combination.

e.g.

`_A italic sentence with **bold word**_`

_A italic sentence with **bold word**_
## Lists
* Use any of the (* - +) symbols to create a list.
* Also can use 4 spaces or 'tab' to bulid a nested list.And the maximum number of level is 3.

Unordered list

```
+ This is a unordered list
  - this is a sublist  
    * this 
```

+ This is a unordered list
  - this is a sublist  
    * this 
 
Ordered list

```
1. Item 1
2. Item 2
   1. Item 2a
   2. Item 2b
```

1. Item 1
2. Item 2
   1. Item 2a
   2. Item 2b
   
## Images
`![Image Name](Image address)`

If you want to embed images, this is how you do it:

`![Image of Yaktocat](https://octodex.github.com/images/spidertocat.png)`

![Image of Yaktocat](https://octodex.github.com/images/spidertocat.png)
## Links
Similar to the Image

`[NAME](address) or just write the link address`

e.g.

```
[Homepage](https://github.com/conquer1the2world3/hello-world/blob/master/README.md)

or

https://github.com/conquer1the2world3/hello-world/blob/master/README.md
```

[Homepage](https://github.com/conquer1the2world3/hello-world/blob/master/README.md) 
or
https://github.com/conquer1the2world3/hello-world/blob/master/README.md

## Blockquotes
```
I like the words most from "The Little Prince":

>You know — one loves the sunset, when one is so sad…

>someone loves a flower, of which just one single blossom grows in all the millions and millions of stars, it is enough to make him happy just to look at the stars. He can say to himself, "Somewhere, my flower is there…" But if the sheep eats the flower, in one moment all his stars will be darkened… And you think that is not important!
```
I like the words most from "The Little Prince":

>You know — one loves the sunset, when one is so sad…

>meone loves a flower, of which just one single blossom grows in all the millions and millions of stars, it is enough to make him happy just to look at the stars. He can say to himself, "Somewhere, my flower is there…" But if the sheep eats the flower, in one moment all his stars will be darkened… And you think that is not important!

## Code
* inline code: Wrap them in backticks: 

\`var example = true`

`var example = true`

* code block: 
    1. indent with 4 spaces
    2. mulitiple lines code with \```code```
* highlighting: include the program lauguage such as java,C++ and so on.

e.g.

```java
public class Demo {

    public static void main(String[] args) {

        int [][] arr=new int[3][3];

        int sum=0;

        for(int i=0;i<arr.length;i++)

            for(int j=0;j<arr[i].length;j++)

                sum=sum+i+j;

        System.out.println(sum);

    }
}
```
## Dividing line

Use 3 or more `* - _` 

```
This is a dividng line 
*************** 
---------------
_______________
```

This is a dividng line 
*************** 
---------------
_______________

## Escape Character

Use `\` to transfer the specific charcter into ordinary character.

The specific character includes  (\  \`  *  _  {}  []  ()  #  +  -  .  !)

## Extended Syntax

1. strikethrough

- [ ] Eat
- [x] Code
  - [x] HTML
  - [x] CSS
  - [x] JavaScript
- [ ] Sleep

- --- ----- ------ --
