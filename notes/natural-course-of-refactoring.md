[Natural Course of Refactoring – a Refactoring Workflow](http://www.infoq.com/articles/natural-course-refactoring)

# Takeaways

Code Should be understandable by humans. 

Clean code is readable, cared for, efficient, extensible and simple.

Write dirty code and succesively refine.


# Practical Takeaways
Guard Clauses. Reverse the logic. Throw/return early.

Avoid too many nested if-else. Refactor into helper methods with descriptive method names.


# Summary
Makes distinction between "Everyday Refactoring" and "Strategic Refactoring"

Important to asses business value. Is it worth refactoring?

![alt tag](http://cdn.infoq.com/statics_s1_20160217-0123/resource/articles/natural-course-refactoring/en/resources/1fig2.png)

Use TDD (Test Driven Development) - Red-Green-Refactor strategy.

# Workflow
0. Understand
..1. Familiarize with the code (ask help if possible)
..2. Start readinng & comment with 
....* //SMELL a smell code description
....* // REFACTOR an idea for refactoring 
....* // REFACTOR an idea for refactoring 
..3. Do some sort of scratch refactoring for the sake of understanding.
..4. Rename variables and name the conditional to express extent. 
![alt tag](http://cdn.infoq.com/statics_s1_20160217-0123/resource/articles/natural-course-refactoring/en/resources/fig3.png)

1. Express Algorithm
⋅⋅* Unordered sub-list. 
2. Extract Responsibilies
..1. Ordered sub-list
3. Introduce Flexibility
4. Evolve Architecture
