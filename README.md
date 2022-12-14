# ECE444-F2022-Lab6
Name: Abhinav Sanjeeva Prasad

### URL to Unit Tests
https://github.com/ECE444-2022Fall/curriculus/blob/develop/Education_Pathways/tests/test_app.py#L102-L132

### What are the pros and cons of TDD?

The following are the pros of using TDD:
1. TDD enables more modular design. As a test is written first, the code itself becomes easy to check. The code that is easy to check features a clear interface and leads to a modular design of the application.
2. TDD makes it easier to refactor code and maintain it. This is because all the functionality is covered by tests. Thus, any change in code that could potentially cause an error will be easily detectable as the unit test will fail. This helps the developer in knowing which function/part of the code has errors. This could be fixed by revisiting the prior versions of that particular part.
3. TDD encourages developers to know the requirements for their tasks. This is because right from the beginning, TDD compels developers to define functionalities as comprehensively as possible. Therefore, developers have to fully understand the requirements to write tests.
 
The following are the cons of TDD:
1. The maintenance of the test code is essential and is highly dependent on the product's requirements. If for some reason, the requirements change, the tests associated with the affected functionality will have to be refactored first followed by changes in the implementation code.
2. TDD has a huge learning curve. For beginners, this process could be a bit complex. It requires a lot of practice. The developers will also need to understand the norm and conventions of the existing test cases. Moreover, TDD encourages breaking down a test into smaller unit tests, this again requires more time and experience.
3. Starting a project with test driven development is usually slower than conventional development. In addition to the learning curve as stated above, the developers have to spend ample time writing the tests first and then implementing the main functionality. If release velocity is the primary goal of the project, then TDD may not be the best approach.