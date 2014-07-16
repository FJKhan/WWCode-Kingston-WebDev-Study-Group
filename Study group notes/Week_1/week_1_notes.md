Introduction to HTML/CSS

HTML stands for Hyper Text Markup Language.

HTML defines the structure and layout of a Web document by using a variety of tags and attributes. The correct structure 
for an HTML document starts with <HTML><HEAD>(enter here what document is about)<BODY> and ends with </BODY></HTML>. 
All the information you'd like to include in your Web page fits in between the <BODY> and </BODY> tags.

Eg:

Structure of a basic html webpage:
<html>
<head>
 <title>My Page</title>
</head>
<body>
 Hello World!
</body>
</html>



Assigning value to a div
Eg: <div id="about"></div>

Eg: <div class="textStyle"></div>

CSS: Cascading Style Sheets (CSS) is a style sheet language used for describing the look and formatting of a document 
written in a markup language.

ID vs Class

ids must be unique where as class can be applied to many things. In CSS, ids look like #elementID and class elements 
look like .someClass

In general, use id whenever you want to refer to a specific element and class when you have a number of things that 
are all alike. For instance, common id elements are things like header, footer, sidebar. Common class elements are 
things like highlight or external-link.

It's a good idea to read up on the cascade and understand the precedence assigned to various selectors: 
http://www.w3.org/TR/CSS2/cascade.html

The most basic precedence you should understand, however, is that id selectors take precedence over class selectors. 
If you had this:

<p id="intro" class="foo">Hello!</p>
and:

#intro { 
   color: red;
}
.foo { 
  color: blue;
 }
The text would be red because the id selector takes precedence over the class selector.

IDs are an incredibly powerful tool. An element with an ID can be the target of a piece of JavaScript that manipulates 
the element or its contents in some way. 

ID attribute
#about{
    Background: red;
}

Class attribute
.textStyle{
  Color: white;
}