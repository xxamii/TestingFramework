# TestingFramework

A custom framework for testing C# projects. A simplified clone of testing frameworks like xUnit, nUnit, etc. It was developed for my .NET Bootcamp during my first year of university.

It was originally developed in my [DotnetBootcampYakovliev](https://github.com/xxamii/DotnetBootcampYakovliev) repository, but I copied it here for more convenient viewing.

# How to Use It

- Download the repository and unzip it.
- Open the solution in your IDE.
- Load up a class library, that you would like to test. Make sure it references the Core class library from this solution.
- Copy the path of the testing class library.
- Go to ./TestingFramework/bin/Debug/net6.0/appsettings.json and paste the path into the empty quotation marks "". 
- Make sure all the testing classes are public and have a "TestClass" attribute.
- Make sure all the testing methods have a "Fact" attribute.
- You can add a set-up and tear-down testing methods with attributes "RunBeforeEachTest" and "RunAfterAllTests".
- You can use the Core.Assertion.Assert class to assert within testing methods.
- You can now build, run, and see the results of your tests.

# What I Learned

- How to use Reflection in C# to test classes.
- Clean n-layered architecture design.
- How to use the built-in Dependency Injection from .NET.
