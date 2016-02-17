[Natural Course of Refactoring – a Refactoring Workflow by Mariusz Sieraczkiewicz](http://www.infoq.com/articles/natural-course-refactoring)

# Takeaways

Makes distinction between "Everyday Refactoring" and "Strategic Refactoring"

Important to asses business value. Is it worth refactoring?

![alt tag](http://cdn.infoq.com/statics_s1_20160217-0123/resource/articles/natural-course-refactoring/en/resources/1fig2.png)

Use TDD (Test Driven Development) - Red-Green-Refactor strategy.

# Workflow

![alt tag](http://cdn.infoq.com/statics_s1_20160217-0123/resource/articles/natural-course-refactoring/en/resources/fig3.png)

1. Understand
  1. Familiarize with the code (ask help if possible)
  2. Start readinng & comment with 
  3. Do some sort of scratch refactoring for the sake of understanding.
  4. Rename variables and name the conditional to express extent. 



![alt tag](http://cdn.infoq.com/statics_s1_20160217-0123/resource/articles/natural-course-refactoring/en/resources/1fig4.png)

1. Express Algorithm - Get code speaks to you.
  1. Use Extract method refacoring to simplify
  2. or use Method Object refactoring for more messy methods
  3. The state of the code we are aiming to is called Composed method


![alt tag](http://cdn.infoq.com/statics_s1_20160217-0123/resource/articles/natural-course-refactoring/en/resources/fig5.png)

2. Extract Responsibilies - Apply Single Responsibity Principle
  1. Private method worth testing? Extract new class.
  2. Does the method name match the class name? If not? move to other class.
  3. Refactorings that may be helpful in this step: Move method, Extract class, Introduce Domain Object, Introduce Value Object.
  4. aim is to adjust responsibilities and cut the code a little bit
  

![alt tag](http://cdn.infoq.com/statics_s1_20160217-0123/resource/articles/natural-course-refactoring/en/resources/3fig6.png)

When you need design patterns:
* you have implemented many times similar algorithm
* your requirements state that something may be done in a variety of ways (for example you have to support different file formats, data formats, protocols, third party systems etc.)
* after you more understand the bigger picture, you can recognize better a nature of object interactions and patterns emerge

It is very handy to know what kind you may be looking for:

- data are built in many steps (Builder)
- you domain object has its lifecycle and you can define some sort of state machine (State)
- you need some form of caching data (Flyweight)
- you need to flexibly enhance some behaviour (Decorator)
- you want to hide the real object for some reasons (Proxy)
- you have different variations on the same algorithm (Strategy)
- and so on… 


3. Introduce Flexibility - Introduce design patterns
  1. Familiarize with the code (ask help if possible)
  2. Start readinng & comment with 
  3. Do some sort of scratch refactoring for the sake of understanding.
  4. Rename variables and name the conditional to express extent. 

![alt tag](http://cdn.infoq.com/statics_s1_20160217-0123/resource/articles/natural-course-refactoring/en/resources/2fig7.png)

4. Evolve Architecture
  1. Familiarize with the code (ask help if possible)
  2. Start readinng & comment with 
  3. Do some sort of scratch refactoring for the sake of understanding.
  4. Rename variables and name the conditional to express extent. 


![alt tag](http://cdn.infoq.com/statics_s1_20160217-0123/resource/articles/natural-course-refactoring/en/resources/fig8.png)
