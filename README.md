# The Variable Lookup Expression

## Learning Goals

* Define the Variable Lookup Expression

## Introduction

The final of our _essential three_ expressions is the variable lookup
expression. Like the _constant expression_, it rounds out the "essential three"
by being boring, yet profound.

It retrieves the value that we set with the _assignment expression_ from the
name we assigned to it.

It looks up the variable's definition in the dictionary, to use the metaphor from the previous lesson.

![Dictionary lookup](https://curriculum-content.s3.amazonaws.com/programming-univbasics/the-assignment-expression/Image_87B_VariableNamingMetaphors.png)

Or, it shakes out the evaluated result of the expression that was put in the
labeled box, to use the other metaphor from the previous lesson.

![Box shake out](https://curriculum-content.s3.amazonaws.com/programming-univbasics/the-assignment-expression/Image_87D_VariableNamingMetaphors.png)

## Define the Variable Lookup Expression

To look up the value in a variable we simply type the variable name's name in.

```js
// Assignment expression that returns 32
age = 32

// Type in the assigned name
age
```

In return, we get `32`.

<iframe height="400px" width="100%" src="https://repl.it/@MaxwellBenton2/TraumaticQuixoticDriver?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>

That’s it. The values we associate with the assignment expression can be retrieved by simply typing the variable's name.

## Variable Lookup as Conversation

In the previous lesson, we talked about a parent and a baby. A parent repeats
their name hundreds of times to get the baby to assign their face to the
variable `ma-ma`. When the baby first sees that face again and says "`ma-ma`!"
the parent has successfully taught the child "variable lookup." Although there
are no pages in baby journals for "Baby's First Variable Lookup."

![Successful Lookup](https://curriculum-content.s3.amazonaws.com/programming-univbasics/the-assignment-expression/Image_55_Mama-Baby_4.png)

If you think about it, most of childhood education until early elementary
school is giving them thousands of assignment expressions so they can
participate in the world: "Red," "one," "eleven," "far."

Consider this scenario. Look for the _essential three_ expressions in here.

<!-- Don't trim trailing whitespace, used to force newline -->

Parent: See the doggie? That’s a doggie.  
Child: Doggie?  
Parent: That’s right, that’s a doggie. Doggies say "Woof-woof!"  
Child: Doggie?  
Parent: Right. Doggie.  

_Some time later_

Child: Doggie!  
Parent: That’s right. Doggie!  

Let’s compare teaching a baby a four-legged animal's name and teaching JavaScript
that `a` is `4`.

|Expression|Real-Life Conversation|JavaScript Conversation|
|----------|----------------------|-----------------|
|Value Expression|Parent points "Doggie"|`4` evaluates to `4`|
|Assignment Expression|"Doggie" = ![Puppy Picture](https://curriculum-content.s3.amazonaws.com/programming-univbasics/the-variable-lookup-expression/small_puppy.JPG)|`a = 4` evaluates to `4`|
|Variable Lookup|Child sees the dog and says "Doggie!"|`a` evaluates to `4`|

## Conclusion

With the _essential three_ expressions under your control, we're going to start
rapidly building up the richness of things you can do using expressions. Whole
programming languages are built around executing through evaluating expressions!
Languages that work this way are called "functional languages" and they are some
of the first programming languages ever created.

