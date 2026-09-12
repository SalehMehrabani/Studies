Test-driven development (TDD) is an approach to software development in which software tests are written before their corresponding functions.
Programming in this style strengthens the relationship between coding, testing(in the form of automated unit-level tests), and code design. While test-driven development might increase upfront development time, it has been demonstrated to improve code functionality and dexterity and save time overall.
What is unit testing? Unit testing is a test-driven development (TDD) method for evaluating software that pays special attention to an individual component or unit of code- the smallest increment possible.
Levels of test-driven development: There are two main levels of test-driven development.
- Acceptance TDD (ATDD)
- Developer TDD

For ATDD - sometimes called behaviour-driven development (BDD)- programmers write a single acceptance test and then enough new code to pass. Acceptance tests are sometimes referred to as customer tests or customer acceptance tests.
They can generally be understood as test cases required for minimum functionality as outlined by product stakeholders. ATDD strives to identify detailed, executable requirements. Acceptance tests can be carried out using various testing tools, such as Fitnesse or RSpec.

Sometimes referred to as simply TDD, developer TDD requires coders to write single tests to evaluate their own solution to an ATDD test. Developer TDD uses test automation tools, such as JUnit or VBUnit. 

5 steps of the test-driven development cycle
When employing a test-driven development strategy, coders first write tests to check each individual element or function of a piece of software before writing enough code to pass that individual test. Once completed, the software is tested again, and if it passes, the code is refined (a process known as refactoring) to include only essential elements. Developers then repeat this process for each subsequent software function. 
1. Before writing the code for a certain software function, developers first write an individual unit test for that function.
2. Developers then run the test, which should fail because the code function hasn’t been written yet. This step is important to confirm that the test itself is functional and does not return any false positives. If the code passes, it indicates that the test needs to be rewritten.
3. When the program fails the test, developers write only enough extra software code to pass the test.
4. When the code can pass the test, both the test and the code are refactored for simplicity and to eliminate any unnecessary code.
5. When the sufficiently refactored software can pass the refactored test, developers move on to the next wanted software function. Testers then write and run tests for each new feature. 

