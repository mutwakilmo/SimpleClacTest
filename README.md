# SimpleClacTest


## Android fundamentals 03.2: Unit tests

## Summary

Android Studio has built-in features for running local unit tests:

-   Local unit tests use the JVM of your local machine. They don't use the Android framework.
-   Unit tests are written with JUnit, a common unit testing framework for Java.
-   JUnit tests are located in the  `(test)`  folder in the Android Studio  **Project > Android**  pane.
-   Local unit tests only need these packages:  `org.junit`,  `org.hamcrest`, and  `android.test`.
-   The  `@RunWith(JUnit4.class)`  annotation tells the test runner to run tests in this class.
-   `@SmallTest`,  `@MediumTest`, and  `@LargeTest`  annotations are conventions that make it easier to bundle similar groups of tests
-   The  `@SmallTest`  annotation indicates all the tests in a class are unit tests that have no dependencies and run in milliseconds.
-   Instrumented tests are tests that run on an Android-powered device or emulator. Instrumented tests have access to the Android framework.
-   A test runner is a library or set of tools that enables testing to occur and the results to be printed to the log.

## What you'll do

-   Run the initial tests in the SimpleCalc app.
-   Add more tests to the SimpleCalc app.
-   Run the unit tests to see the results.
