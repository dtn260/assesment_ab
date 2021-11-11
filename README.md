TEST ASSIGNMENT BY Doruk Taskin.

For this assignment I have created the runner class Maintest to run the passing tests. These tests can be run individualy or a a group by running the tests from class MainTest.
This class uses some other functions and is extended by the class BaseTest and imports some helper classes like MainHelper and Utilities classes and extended BaseTest class.

In BaseTest we add the rule to launch the activity before each test.

The other test runner class I have created is NegativeCasesTest and through this class we can run the negative tests, by testing and asserting unexpected values. 
Negative testing ensures that your application can gracefully handle invalid input or unexpected user behavior.

The tests can be run on the Test Folder as stated, the negative cases can be run under the NegativeCasesTest:

![image](https://user-images.githubusercontent.com/32645994/141368946-a641c9ce-2974-4bf4-8dcb-a1314579df63.png)


The tests are run with API level28 and android version 9 and first build the app by adding the configuration, then run the test Maintest

TEST RESULTS

![image](https://user-images.githubusercontent.com/32645994/141361392-680906a5-953b-4886-8388-d70478184a02.png)


After running the tests you can export the test results by clicking on 'Export Test Results' button that is circled in red.
This will automatically export the test result to the Test Results folder that I have created.

