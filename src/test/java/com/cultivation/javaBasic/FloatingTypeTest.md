## should_not_get_rounded_result_if_convert_floating_number_to_integer()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://www.javatpoint.com/java-math
2. Why the test failed at first?
* Because the expected result is set to Integer.MAX_VALUE
3. Why you corrected the test that way?
* Based on the knowledge point, I based on the operator where the float value will be not rounded if converting it into integer.
4. Do you have further questions on this knowledge point?
* No other concerns

## should_judge_special_double_cases()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://www.geeksforgeeks.org/java-lang-float-class-in-java/
2. Why the test failed at first?
* Because it would throw exception when calling the isInfinity and isNan method
3. Why you corrected the test that way?
* Based on the knowledge point, I based on the method in the Float class where it would check the float value is infinity or if it is not a valid value for float
4. Do you have further questions on this knowledge point?
* No other concerns

## should_not_round_number_when_convert_to_integer()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://www.javatpoint.com/java-math
2. Why the test failed at first?
* Because the expected result is set to Integer.MAX_VALUE
3. Why you corrected the test that way?
* Based on the knowledge point, the FLOOR method would prevent any float value being rounded up or down when converting into integer.
4. Do you have questions on this knowledge point?
* No other concerns

## should_round_number()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://www.geeksforgeeks.org/java-math-round-method-example/
2. Why the test failed at first?
* Because the expected result is set to Long.MAX_VALUE
3. Why you corrected the test that way?
* Based on the knowledge point, the ROUND method would add 1/2 to the existing value and taking the floor result of the total result.
4. Do you have further questions on this knowledge point?
* No other concerns