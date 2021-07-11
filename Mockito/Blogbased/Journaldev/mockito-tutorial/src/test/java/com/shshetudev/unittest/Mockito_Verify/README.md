### Mockito Verify
* Mockito Verify methods are used to check that certain behavior happened.
* __We can use Mockito verify methods at the end of the testing method code to make sure that specified methods are called.__
* __verify():__
    * Mockito `verfiy()` method can be used to test number of method invocations too.
    * We can test exact number of times, at least once, at least, at most number of invocation times for a mocked method.
* __verifyNoMoreInteractions():__
    * We can use `verifyNoMoreInteraactions()` after all the `verify()` method calls to make sure everything is verified.
    * If any method verification is still left, it will fail and provide proper message.
* __verifyZeroInteractions():__ `verifyZeroInteractions()` behavior is same as `verifyNoMoreInteractions()` method.
* __inOrder():
    * __ We can use `inOrder()` method to verify the order of method invocation.
    * We can skip a method invocation but the methods being verified must be in the smae order.


### Mockito verify() simple example
Please see the implementation at: [MockitoVerifySimpleExample](../Mockito_Verify/MockitoVerifySimpleExample.java)


### Mockito verify with number of times
Please see the implementation at: [MockitoVerifyNumberOfTimes](../Mockito_Verify/MockitoVerifyNumberOfTimes.java)


### Mockito verifyNoMoreInteractions()
Please see the implementation at: [MockitoVerifyNoMoreInteractions](../Mockito_Verify/MockitoVerifyNoMoreInteractions.java)


### Mockito verifyZeroInteractions()
Please see the implementation at: [MockitoVerifyZeroInteractions](../Mockito_Verify/MockitoVerifyZeroInteractions.java)


### Mockito verify only one method call
Please see the implementation at: [MockitoVerifyOnlyOneMethodCall](../Mockito_Verify/MockitoVerifyOnlyOneMethodCall.java)


### Mockito Verify Order of Invocation
Please see the implementation at: [MockitoVerifyOrderOfInvocation](../Mockito_Verify/MockitoVerifyOrderOfInvocation.java)


