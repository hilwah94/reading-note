 
 
 
 
 #Read-04

**_HTML Links, JS Functions, and Intro to CSS Layout_**  

>**_Links :_** 

>Links are created using the (a) element. Users can click on anything  
>between the opening (a) tag and the closing (/a) tag.  
>You specify which page you want to link to using the href attribute
  
>Many people navigate websites by scanning the text for links, Clear link text can help visitors  
>find what they want, This will give them a more positive impression of your site and may  
>encourage them to visit it for longer  
>Relative URLs can be used when linking to pages within your own website, They provide a shorthand way of telling the browser where to find your files. 

>Email Links : (mailto)  
>To create a link that starts up the user's email program and addresses an email to a specified  
>email address, you use the (a)element, However, this time the value of the href attribute starts  
>with mailto: and is followed by the email address you want the email to be sent to.  

>Opening Links in a New Window : (target)  
>f you want a link to open in a new window, you can use the target attribute on the opening  
>(a) tag. The value of this attribute should be blank  
>One of the most common reasons a web page author might want a link to be opened in a new window is if it points to >another website. In such cases, they hope the user will return to the window containing their   
>site after finishing looking at the other one.

> You can use the id attribute to target elements within a page that can be linked to  
>Linking to a Specific Part of the Same Page : To link to an element that uses an id attribute  
>you use the (a) element again, but the value of the href attribute starts with the # symbol,  
>followed by the value of the id attribute of the element you want to link to.

### LAYOUTS :  

>**Building Blocks:** CSS treats each HTML element as if it is in its own box, This box will either be a block-level box or an inline box.  
>Block-level elements start on a new line like: (h1) (p)  
>Inline elements flow in between surrounding text like: (img) (b) (i)

>**Containing Elements**  
>If one block-level element sits inside another block-level element then the outer box is  
>known as the containing or parent element.  

>**Controlling the Position of Elements**

>CSS has the following positioning schemes that allow you to control the layout of a page:  
>normal flow, relative positioning, and absolute positioning.You specify the positioning scheme using the position property in CSS, You can also float elements using the float property.  
>1- Normal flow : Every block-level element appears on a new line, causing each item to appear lower down  
>the page than the previous one  
>2- Relative Positioning : This moves an element from the position it would be in normal  
>flow, shifting it to the top, right, bottom, or left of where it would have been placed, This  
>does not affect the position of surrounding elements.  
>3- Absolute positioning : This positions the element in relation to its containing element  
>It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements

### Functions, Methods , Objects  

>complex scripts can run to hundreds (even thousands) of lines, Programmers use functions, methods, and objects to organize their code.  

>1- : Functions let you group a series of statements together to perform a specific task,  
>If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).  
>Pieces of information passed to a function are known as parameters.  
>you need to give your function a name, That name should describe the task it is performing, When you ask it to  
>perform its task, it is known as calling.  
>when you write a function and you expect it to provide you with an answer, the response is known as a return value 

>**DECLEARING A FUNCTION** :  
>to create a function, you give otb a name and then write the statements needed to achive it's tasks  
>inside the curly braces , this is known as **function decleration**

>**CALLING A FUNCTION**  
>having declared thw function, you can then excute all of the statements between it's curly braces  
>with just one line of codes this is known as **Calling The Function**

>HOW MEMORY & VARIABLES WORK ? Global variables use more memory, The browser has to remember them for as long as >the web page using them is loaded, Local variables are only remembered during the period of time that a function >is being executed.

**_Resources_**

>**From the HTML book :**:  
>Chapter 4:  (74-93)  
>Chapter 15:  (358-404)  

>**From the JS book :**  
>Chapter 3: (86-99)  

>**Other Resources :**  
>[6-reasons-for-pair-programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)