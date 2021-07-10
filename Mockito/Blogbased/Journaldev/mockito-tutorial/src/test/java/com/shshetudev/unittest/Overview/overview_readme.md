### Mockito Mock Creation

The Mockito framework allows us to create mock object using either `@Mock` annotation or `mock()` static method.

* #### Mockito mock() Method:
* In the following example, we are testing `CalcService`.
* `Mockito.mock()` method is used to create a mock object of `AddService` class.

### Mockito Verify Interaction
* Mockito framework keeps track of all the method calls and their parameters to the mock object.
* __Mockito `verify()` method on the mock object verifies that a method is called with certain parameters.__
* __We can also specify the number of invocation logic__, such as:
    * __exact number of times.__
    * __at least specified number of times.__
    * __less than the specified number of times.__
* We can use `VerificationModeFactory` for number of invocation times logic.
* __Mockito `verify()` method checks that a method is called with the right parameters.__
* __It does not check the result of a method call like `assert()` method__
    