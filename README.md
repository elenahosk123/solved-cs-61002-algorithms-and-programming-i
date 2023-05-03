Download Link: https://assignmentchef.com/product/solved-cs-61002-algorithms-and-programming-i
<br>
Project Objectives

This assignment will give you more experience on the use of:

<ol>

 <li>classes</li>

 <li>class methods</li>

 <li>inheritance</li>

</ol>

In this project, you are going to use turtle graphics to draw one or more “snow persons.” You will define and use at least 7 classes in doing so. Using instances of these classes, you will write a main()  function that creates and draws one or more snow people.




Project Specification

<ol>

 <li>Define a minimum of 7 classes. Most can be classes for geometric shapes (e.g., Line, Rectangle, Circle, Triangle), but 3 must be “drawing-specific” classes (see #5).</li>

 <li>Each class will have at least the following methods:

  <ol>

   <li><strong>__init__:</strong> the constructor will take arguments indicating the positions (coordinate pairs, e.g., (0.0, 0.0)) of one or more reference points (e.g., start and end points for a line, vertices for a triangle, etc); and other arguments appropriate for an instance (e.g., pen color, fill color, etc.).   To simplify creating instances, it will define appropriate default values for most of the    (If the argument for fill color is the empty string (“”), the shape is not filled.)</li>

   <li><strong>__str__</strong> : a conversion method, it returns the string to be used for printing an instance in Python.</li>

   <li><strong>draw</strong> : the draw method will take a turtle.Turtle object to use for drawing the shape.</li>

   <li>Other arguments may be required for your methods; all arguments will be described in your docstrings.</li>

  </ol></li>

</ol>




<ol start="3">

 <li>All classes, methods and functions require a docstring for a general description of the object/method/function.</li>

</ol>




<ol start="4">

 <li>Define a main function that is called without any arguments. Your main function should create and draw one or more snow people at different positions on the canvas.</li>

</ol>




<ol start="5">

 <li>Define a drawing-specific class hierarchy containing (at least) 3 classes:</li>

</ol>




<ol>

 <li>Snow_person : an instance contains (at least) the 3 snowballs</li>

</ol>




<ol>

 <li>Snow_man : specializes a Snow_person with a handful of additional components (e.g., arms, buttons, head wear)</li>

</ol>







CS 61002 Algorithms and Programming I

<ol>

 <li>Snow_lady : specializes a Snow_person with an alternate set of additional components.</li>

</ol>




<ol start="6">

 <li>At a minimum, a snow person should include three snowballs, drawn one on top of the other, and two eyes and a mouth. Feel free to personalize your classes to include other components.</li>

</ol>





