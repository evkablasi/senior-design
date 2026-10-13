Evka Blasi

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
   
### Examples
## Kanban 
### Summary
Kanban was developed as a part of the Toyota Production System in the 1940's and is widely used today as a methodology of Agile Development. At the core of the Kanban method is the Kanban Board, which is a visual display of every task on the team's docket, no matter what stage of development the task is in, from waiting on deck to being completed. The breakdown of categories on the board is flexible to the developers' needs, with the exception of the essential "Work in Progress," around which the workflow is centered [^3]. I believe the visual aspect of the Kanban methodology would help us stay on track, considering the length of our project, and would also promote collaboration as we could see what our teammates are working on or could be stuck on. 
### Overview
As mentioned before, the critical component of Kanban-style development is the Kanban Board, which was originally a physical whiteboard, but digital options have been created with the expansion of the technique. The board is split up into as many columns as the developers decide they need, though the essential steps can be broken into just five: To Do, Work in Progress, Testing, Complete. At the beginning of the project, the To Do stage contains every identifiable step from the briefing or description, and new tasks can be added as they arise. Work in Progress is for each step that is currently being worked on, and the fundamental goal of Kanban is to limit the number of steps in the Work in Progress column. The Testing column is for validating that the piece works as intended and works with the rest of the project. Once thorough testing is done, the step can be moved to the Complete column. Each task is written on a card and moved through the flow, creating a living document of progress.
### Examples
## Comparison & Conclusion
Where Test-Driven Development focuses on the individual developer's process, though it may impact the rest of the team's work indirectly, the Kanban approach dictates how the team should operate together but does not address the developers' coding process or style. They both have a workflow broken down into multiple phases, TDD being Red, Green, Refactor, and Kanban being the stages of progress, but they differ in how to navigate the flow. Test-Driven Development works in a cycle, while Kanban has an end and a beginning and only progresses forwards through the flow. It seems that a good option would be to form a hybrid of the two, letting one dictate our coding style while we allow the other to inform our team dynamic. However, I do think there would be some clash because of the cyclical nature of TDD and the push in Kanban to swiftly move things out of the Work in Progress stage. Test-Driven Development is definitely a style that we should try to integrate as a group, but I do believe we should also identify a software methodology that will give more guidance on group roles and how the team should operate.

[^1]: https://framework.scaledagile.com/test-driven-development/
[^2]: https://www.drizz.dev/post/tdd-vs-bdd?_gl=1*nebr69*_gcl_au*MTg4NDU0OTk5OS4xNzkwODEwODY5*_ga*NDk0NTExMDY5LjE3OTA4MTA4Njk.*_ga_DRVCD5PR3T*czE3OTA4MTA4NjgkbzEkZzAkdDE3OTA4MTA4NjgkajYwJGwwJGgyNzI1ODE4NDg.
[^3}: https://www.geeksforgeeks.org/software-engineering/what-is-kanban/ 
[^4]:
[^5]:
