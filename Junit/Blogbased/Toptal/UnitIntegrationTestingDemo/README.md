### Introduction
* For doing regression testing, there are many tests that should be carried out from an API-level point of view.
* But we will cover two major types of testing:
    * __Unit testing:__
        * Where any given test covers the smallest unit of a program (a function or procedure).
        * It may or may not take some input parameters and may or may not return some values.
    * __Integration testing:__
        * Where individual units are tested together to check whether all the units interact with each other as expected.
* Most of the times, we write methods in a class, and these, in turn, interact with methods of some other classes.
* So when writing the unit test for such a method, we need a way to return mocked data form those calls.
* This is because the intent of this unit test is to test only one method and not all the calls that this particular method makes.

### What is mocking and When does it come into the Picture?
Please see the illustration: [CalculateArea](../UnitIntegrationTestingDemo/src/main/java/com/shshetudev/tdd/unit/service/CircleService.java)
* Here we have a function `calculateArea(Type type, Double... args)` which calculates the area of a shape of the give type(circle,square or rectangle).
* Now if we want to unit-test the function `calculateArea()` of the class `CalculateArea`, then our motive should be to check whe