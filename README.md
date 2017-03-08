# XCTestSample
Unit Testing and UI Testing in Xcode with Swift

It’s a simple app that will do a percentage calculation of a given number and a percentage. (For example: 10% of 80 is 8).
This PercentageCalculator project is simple. The only essential file for you to look at is ViewController.swift. The code is documented in comments and very straightforward.

In PercentageCalculatorTests.swift there are 4 initial methods created for us in the PercentageCalculatorTests class. Two of them are example test methods that you can delete (you can recognise test methods because they start with the test keyword and have a diamond icon next to them in the gutter, and end with “…Example”). The other two, setUp() and tearDown() are special boilerplate methods in that they are called respectively before and after every test method is executed.

In Unit Testing you check if a certain chunk of code does its job. The chunks of code being tested are usually just a few lines and typically, you are only testing a single method or function. Unit testing is done by providing the unit of code an input value, allowing that value to run through the code, and then checking to see if the output value is what we expect it to be.

The comparison ‘to what we expect it to be’ part is handled by XCTAssert functions. The simplest XCTAssert function is the XCTAssert(expression: BooleanType). This one takes in a boolean expression (This can be something like 5 > 3, 8.90 == 8.90 or true) and makes the test pass if the expression is evaluated to be true or fail if evaluated to be false.

In this sample, you can learn about Unit Testing in Xcode and how it can help you to find bugs in your code. Besides bug prevention, Unit Testing can also be used for Performance Testing and Asynchronous Testing. Another thing that might interest you is UI Testing, where you test how your app performs in real life situations by recording actions on your app.

Use following link to know more about UI Testing : https://developer.apple.com/videos/play/wwdc2015/406/

Thanks,
