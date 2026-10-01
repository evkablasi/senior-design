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
### Overview
### Examples
## Comparison
## Conclusion

[^1]: https://framework.scaledagile.com/test-driven-development/
[^2]: https://www.drizz.dev/post/tdd-vs-bdd?_gl=1*nebr69*_gcl_au*MTg4NDU0OTk5OS4xNzkwODEwODY5*_ga*NDk0NTExMDY5LjE3OTA4MTA4Njk.*_ga_DRVCD5PR3T*czE3OTA4MTA4NjgkbzEkZzAkdDE3OTA4MTA4NjgkajYwJGwwJGgyNzI1ODE4NDg.
[^3}:
[^4]:
[^5]:
