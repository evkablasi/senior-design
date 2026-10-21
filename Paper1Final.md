Evka Blasi

## Introduction
In this paper, I will discuss two software development methodologies, namely Test-Driven Development and Kanban, and how we might integrate them into our project. After researching both methodologies and considering the length of our project and dynamic of our group, I have decided that the best option is to utilize Test-Driven Development in our individual coding processes while letting a different methodology guide our group roles and meetings, though I am not set on Kanban as the best one.

## Test-Driven Development
### Summary
Kent Beck, the father of Test-Driven Development, insists that he merely "rediscovered" this software development methodology, though he alone can be credited for defining a formal name and framework. Just as the name implies, Test-Driven Development guides developers to define goals and expectations, write tests that successful (i.e. meeting the expectations) code would pass, then writing the actual code [^1]. This methodology was so revolutionary at the time Beck began writing about it because it is essentially the reverse workflow of every other software development strategy. Right away, there are a couple things I notice that make me lean towards the philosophy of Test-Driven Development. First off, it forces developers to embrace failure as a necessity of the development process, which I am strongly in support of. I also appreciate how writing the tests first dictates more specifically what the code needs to accomplish, which will cut down on excessive code and prevent bias towards your code when writing tests. 
### Overview
The process of Test-Driven Development is generally interpreted into three main steps, referred to as Red Green Refactor [^2].
1. Red
   
   The developer begins by writing a test based on variables and functions etc. that don't exist yet but will be included in the written code. The tests are broken down so that each expected behavior can be written and confirmed individually, in keeping with the principles of the methodology. This step is named "Red" because, obviously, the test will fail. 
1. Green

   The next step is to write the most minimal code possible to pass the one test you are focused on. Writing in small bits like this ensures that the developer does not stray from the flow of Test-Driven Development. Continue to rework the code until the test passes, thus this being the "Green" step.
1. Refactor

   Finally, "Refactor" or rework code to be more elegant and expand tests to reflect more advanced behavior and every extenuating circumstance that the code should be able to handle. This step is the connection back to the beginning of the whole cycle.

In his article, [Canon TDD](https://newsletter.kentbeck.com/p/canon-tdd), Beck goes into a bit more detail and clarifies some common misunderstandings or misuses of Test-Driven Development. He adds the first step of creating a "Test List", which covers all expected behaviors, outputs, errors, etc. from the code. He also stresses the importance of tackling each test on the list at a time and ensuring as the developer moves through the list to ensure the previous tests are still completely successful. Lastly, I quite enjoy Beck's bit of wisdom on how to split the "Green"/"Make it Pass" step from the "Refactor" step: "Make it run, *then* make it right".

One aspect of the process that could lead to issues depending on the scope of the project is how the testing grows as your understanding of the needs of the output grows. Test-Driven Development does not encourage the developer to consider efficiency or performance during the coding process, which could lead to unnecessary or redundant code and tests. It also could produce code with low readability because of the back and forth. In our case, where we are working in a group and also handing our product off to a company who presumably may want to edit or expand on our code, readability is very important, so this is less than ideal. 
   
### Examples
In 2015, AllState was noticing a shift in the insurance industry and didn't want to be left behind. They abandoned their previous methodology, Waterfall, for Extreme Programming, the core of which is Test-Driven Development. This switch allowed them to constantly be improving and pushing out new products in features as opposed to the slow, linear pace of Waterfall development, which was restricting their growth [^3]. 

## Kanban 
### Summary
Kanban was developed as a part of the Toyota Production System in the 1940's and is widely used today as a methodology of Agile Development. At the core of the Kanban method is the Kanban Board, which is a visual display of every task on the team's docket, no matter what stage of development the task is in, from waiting on deck to being completed. The breakdown of categories on the board is flexible to the developers' needs, with the exception of the essential "Work in Progress," around which the workflow is centered [^4]. I believe the visual aspect of the Kanban methodology would help us stay on track, considering the length of our project, and would also promote collaboration as we could see what our teammates are working on or could be stuck on. 
### Overview
As mentioned before, the critical component of Kanban-style development is the Kanban Board, which was originally a physical whiteboard, but digital options have been created with the expansion of the technique. The board is split up into as many columns as the developers decide they need, though the essential steps can be broken into just five: To Do, Work in Progress, Testing, Complete. At the beginning of the project, the To Do stage contains every identifiable step from the briefing or description, and new tasks can be added as they arise. Work in Progress is for each step that is currently being worked on, and the fundamental goal of Kanban is to limit the number of steps in the Work in Progress column. The Testing column is for validating that the piece works as intended and works with the rest of the project. Once thorough testing is done, the step can be moved to the Complete column. Each task is written on a card and moved through the flow, creating a living document of progress.

A lot can go right with Kanban when teams are willing to take on the full methodology, but when they merely scrape the surface without doing the proper research, that's when things can go wrong. It is essential to create and respect limits on how many tasks are allowed in the Work in Progress column and for how long. There also needs to be very clear communication and common understanding of what requirements need to be met for a card to move from one column to the next, otherwise the flow will not serve its purpose. 

### Examples
Many big-name companies besides Toyota use Kanban, such as Spotify, Pixar, and Zara, which truly is a testament to the success that this methodology can bring and the size of the companies it can support [^5]. Spotify divides their Kanban board into "To-Do", "Doing", and "Done", while Zara names its categories "Pre Control", "Control", and "Post Control". Each of Pixar's departments has their own Kanban board which is shared with the rest of the company so that they can easily collaborate and stay up to date with each other.


## Comparison & Conclusion
Where Test-Driven Development focuses on the individual developer's process, though it may impact the rest of the team's work indirectly, the Kanban approach dictates how the team should operate together but does not address the developers' coding process or style. They both have a workflow broken down into multiple phases, TDD being Red, Green, Refactor, and Kanban being the stages of progress, but they differ in how to navigate the flow. Test-Driven Development works in a cycle, while Kanban has an end and a beginning and only progresses forwards through the flow. It seems that a good option would be to form a hybrid of the two, letting one dictate our coding style while we allow the other to inform our team dynamic. However, I do think there would be some clash because of the cyclical nature of TDD and the push in Kanban to swiftly move things out of the Work in Progress stage. Test-Driven Development is definitely a style that we should try to integrate as a group, but I do believe we should also identify a software methodology that will give more guidance on group roles and how the team should operate.

[^1]: https://framework.scaledagile.com/test-driven-development/
[^2]: https://www.drizz.dev/post/tdd-vs-bdd
[^3]: https://wedotdd.com/
[^4]: https://www.geeksforgeeks.org/software-engineering/what-is-kanban/ 
[^5]: https://kanbanzone.com/2022/big-companies-using-kanban-for-business-operations/
