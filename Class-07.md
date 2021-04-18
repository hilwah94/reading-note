



# Read-07

**_Object-Oriented Programming, HTML Tables_**

>**What is a table ?**  
>A table represents information in a grid format like sport results for example  
>Each block in the grid is referred to as a table cell.

>**Basic Table Structure :**

>(**table :**) The (**table**) element is used to create a table. The contents of the table In HTML is written out  row by row.  
>(tr) You indicate the start of each row using the opening (tr) tag, (The tr stands for table row.)  
>It is followed by one or more (td) elements (one for each cell in that row), At the end of the row you use a closing (/tr) tag.  
>(td) Each cell of a table is represented using a (td) element, (The td stands for table data.) At the end of each cell you use a closing (/td) tag.  
>(th) The (th) element is used just like the (td) element but its purpose is to represent the heading for either a column or a row. (The th stands for tableheading.)  
>Even if a cell has no content, you should still use a (td) or (th) element to represent the presence of an empty cell otherwise the table will not render correctly.  
>Using (th) elements for headings helps people who use screen readers, improves the ability for search enginesto index your pages, and also enables you to control the appearance of tables better when you start to use CSS.  
>You can use the scope attribute on the (th) element to indicate whether it is a heading for a column or a row. It can take the values:  
>row to indicate a heading for a row, or col to indicate a heading for a column  

>**SPANNING COLUMNS :** The colspan attribute can be used on a (th) or (td) element and indicates how many columns that cell should run across.  

>**SPANNING ROWS :**You may also need entries in a table to stretch down across more than one row, The rowspan attribute can be used on a (th) or (td) element to indicate how many rows a cell should span down the table.

>**Long Tables :**There are three elements that help distinguish between the main content of the table andthe first and last rows (which can contain different content), These elements help people who use screen readers and also allow you to style these sections in a different manner than the rest of the table.

>1- (thead) : The headings of the table should sit inside the (thead) element.  
>2- (tbody) : The body should sit inside the (tbody) element.  
>3- (tfoot) : The footer belongs inside the (tfoot) element.  

>**Creating an object : constructor notation**  
>the {new} keyword and object constructor create a blank object .  
>you can then add properties and methods to the object.  
>first, you can create a new object using a combination of the {new} key word and the object () constructor function
>next, having created the blank object, you can add properties and methods to it using dot notation  
>each statement that adds a property of method should ends with semi colon ";".  

>**EX : let hotel = newObject ()**;  
>**to create an embty object using literal notation use let hotel = {} , the curly brackets create an embty object**  

>**Updating an object :** to update the value of properties, use dot notation or square brackets, they work on objects created using literal or constructor notation, to delete a property use the {delete} key word

>**CREATING MANY OBJECTS: CONSTRUCTOR NOTATION**  
>Sometimes you will want several objects to represent similar things, Object constructors can use a function as a template for creating objects,First, create the template with the object's properties and methods.








**_Resources_**

>**From the HTML book :**:  
>Chapter 6:  (126-145)   

>**From the JS book :**  
>Chapter 3: (106-144)  

>**Other Resources :**  
>[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)