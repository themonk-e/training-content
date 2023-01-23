# What is Testing 
- Black-box, white-box testing
- Performance Testing, Load Testing, Smoke testing, Integration Testing, Penetration Testing, Unit Testing.
- **Unit Testing** is important component of developer testing which is heavily used in TDD.
  - In.Net/.Net Core supports multiple frameworks for testing 
  - MSTest, **[NUnit](https://learn.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-nunit)**, xUnit.
- Test-driven development (TDD) is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases. This is as opposed to software being developed first and test cases created later.
- Mantra: Red, Green, Refactor
- Structure/Phases of Unit Tests: Arrange, Act, Assert
- Process:
    - Start with degenerate test cases first
    - As the tests get more specific the code becomes more generic

## The flow of [TDD](https://www.guru99.com/test-driven-development.html)
1. Create a test case - What you expect the feature is suppose to do
2. Running the test case will fail the first time - obviously since you haven't created the actual implementation details to make it pass
3. Write code so the new test case will pass
4. Make sure old test cases won't fail because of the new feature (probably the biggest thing as to why we do unit testing so anything new added will also test our old functionalities to make sure everything is working as intended)
5. Clean up the code and have proper documentation for other developers

## Unit testing
* Like the word "Unit", you will test a small portion of your code to ensure it is working
* Helpful to check that particular section of your code is working

## Arrange, Act, and Assert (The 3 good ole As)
* Arrange
    * This is where you initialize objects or some values you will need for the test
* Act
    * Invokes the method/function under the test with the arranged objects/values
* Assert
    * Verifies that the action of the method under the tests behaves as expected

## Code Coverage
* It is the percentage given to you on how much lines of your code is actually covered by unit testing
* Ex: Lets say you have a total of 200 lines of code and your unit testins only covers 70 lines of code. That means you have 35% code coverage (Fancy math - 70/200*100 = 35%)
### Generally Supported Code Coverage Formats
- Supported code coverage report format types include all test coverage reports we've seen in the wild so far, including:
    - Most of .xml format types (Cobertura XML, Jacoco XML, etc.)
    - Most of .json format types (Erlang JSON, Elm JSON, etc.)
    - Most of .txt format types (Lcov TXT, Gcov TXT, Golang Txt)
# Unit Testing References
- [NUnit](https://learn.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-nunit)
- [Must watch code Kata by Uncle bob](https://www.youtube.com/watch?v=kScFczWbwRM)

# EF Core
- [Tutorial guide](https://www.entityframeworktutorial.net/what-is-entityframework.aspx)
- [Exercises](https://learn.microsoft.com/en-us/training/modules/persist-data-ef-core/)