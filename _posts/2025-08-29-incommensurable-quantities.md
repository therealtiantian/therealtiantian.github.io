---
layout: post
title: Incommensurable Quantities
subtitle: On dimentions of linear algebra
tags: [maths]
---
Numbers not only make sense with quantity but also units. two numbers with different units cannot be operated. They are unrelated. 

Gilbert Strang gives a succinct comment on this matter: “you can’t add apples and oranges.” In a way, you can’t operate two numbers until you have unified them with the same unit through calculation or abstraction. Consider another situation where I declare a new project of calculating the number of fruits, among which there are apples and oranges. Then they can be calculated with the same unit (entity). This is where units are integrated through abstraction. Or consider another situation where there is a universal measure for fruits, and for the sake of convenience I’ll take monetary value as a vulgarized unit. Suppose 2 apple equals one orange, then we can calculate apples and oranges either with the absolute price or the cancellation of one variable. 

Linear combination is like this. Consider the combination of a matrix A and a column x, the numbers in the column vector are coefficients, meaning they represent operations instead of quantities. And the column of the resulting Vector y is calculated by adding together the products of each column of the Matrix multiplied by one coefficient in the vector x. This is to say, in this column picture, each row of the matrix A is considered a quantity in different units. They cannot be added vertically, but can be added horizontally with each row being multipled by its own weights. 

Now there is the row picture. Consider multiplying a row vector x by a matrix A, now each column of A is a quantity with different units. The resulting row vector y is the combination of each row of A multipled by a certain coefficient in x. 

So for matrix multiplication, an important thing is which numbers are addable. Namely, which numbers are of the same unit and nature? Those with the same units can then be added with magnified or reduced quantities, depending on their coefficients. 