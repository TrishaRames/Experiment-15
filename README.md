# Experiment-15
## The study of the Selenium Web Testing Tool reveals its effectiveness in automating web applications for testing purposes across different browsers and platforms.

# What is Selenium?
JavaScript framework that runs in your web browser Works anywhere JavaScript is supported Hooks for many other languages Java, Ruby, Python Can simulate a user navigating through pages and then assert for specific marks on the pages All you need to really know is HTML to start using it right away

# Selenium IDE
Selenium Integrated Development Environment (IDE) is a Firefox plugin that lets testers to record their actions as they follow the workflow that they need to test. It provides a Graphical User Interface for recording user actions using Firefox which is used to learn and use Selenium, but it can only be used with Firefox browser as other browsers are not supported. However, the recorded scripts can be converted into various programming languages supported by Selenium and the scripts can be executed on other browsers as well.
Selenium-IDEDownload
Step 1 − Launch Firefox and navigate to the following URL - http://seleniumhq.org/download/. Under the Selenium IDE section, click on the link that shows the current version number as shown below.

<img width="770" height="261" alt="image" src="https://github.com/user-attachments/assets/47d69a99-04f2-4e29-957e-63d9ecb1f3b7" />

Step 2 − Firefox add-ons notifier pops up with allow and disallow options. User has to allow theinstallation.

<img width="408" height="172" alt="image" src="https://github.com/user-attachments/assets/2935d5d2-0932-481d-ba31-832e5c2c22ac" />

Step 3 − The add-ons installer warns the user about untrusted add-ons. Click 'Install Now'.

<img width="568" height="388" alt="image" src="https://github.com/user-attachments/assets/231f9c47-e99a-49da-9efa-51f1043b08fe" />

Step 4 − The Selenium IDE can now be accessed by navigating to Tools >>Selenium IDE.

<img width="508" height="233" alt="image" src="https://github.com/user-attachments/assets/25b8c627-0a4b-4bb3-a471-7aad33f8cbd9" />

Step 5 − The Selenium IDE can also be accessed directly from the quick access menu bar as shown below.

<img width="279" height="91" alt="image" src="https://github.com/user-attachments/assets/dee5b33d-80ad-4d9f-8335-9bc3853b4a97" />

# Selenium IDE Features
This section deals with the features available in Selenium IDE. The following image shows the features of Selenium IDE with the help of a simple tool-tip.

<img width="505" height="354" alt="image" src="https://github.com/user-attachments/assets/c6084c63-b14d-4d81-96fd-3525152a3c38" />  

The features of the record tool bar are explained below.

<img width="574" height="740" alt="image" src="https://github.com/user-attachments/assets/410aa1ad-737e-4d08-a60d-b0c6f5014bd9" />

# Creating Selenium IDE Tests
This section deals with how to create IDE tests using recording feature. The following steps are involved in creating Selenium tests using IDE − Recording and adding commands in a test Saving the recorded test Saving the test suite Executing the recorded test RecordingandAdding CommandsinaTest We will use www.ncalculators.com to demonstrate the features of Selenium.

Step 1 − Launch the Firefox browser and navigate to the website - https://www.ncalculators.com/

Step 2 − Open Selenium IDE from the Tools menu and press the record button that is on the top- right corner.

<img width="513" height="236" alt="image" src="https://github.com/user-attachments/assets/d8e82073-bd4e-4ab7-a2b4-3d3ee0b5dac3" />

Step 3 − Navigate to "Math Calculator" >> "Percent Calculator >> enter "10" as number1 and 50 as number2 and click "calculate".

<img width="643" height="219" alt="image" src="https://github.com/user-attachments/assets/79ce4710-58bc-4dd1-b3d5-c8079695c25c" />

Step 4 − User can then insert a checkpoint by right clicking on the webelement and select "Show all available commands" >> select "assert text css=b 5"

<img width="647" height="333" alt="image" src="https://github.com/user-attachments/assets/c0337a22-5180-4681-8607-69f9ad4c6a16" />

Step 5 − The recorded script is generated and the script is displayed as shown below.

<img width="649" height="351" alt="image" src="https://github.com/user-attachments/assets/01998bbb-201b-4a04-b541-3f8c175012c5" />

# SavingtheRecordedTest
Step 1 − Save the Test Case by navigating to "File" >> "Save Test" and save the file in the location of your choice. The file is saved as .HTML as default. The test can also be saved with an extension htm, shtml, and xhtml.

<img width="627" height="287" alt="image" src="https://github.com/user-attachments/assets/dc64c9ef-b826-4ade-a45f-abf15cc88bcf" />

# SavingtheTest Suite
A test suite is a collection of tests that can be executed as a single entity.

Step 1 − Create a test suite by navigating to "File" >> "New Test Suite" as shown below.

<img width="615" height="294" alt="image" src="https://github.com/user-attachments/assets/50c1857d-7b0c-40e4-a834-300583754115" />

Step 2 − The tests can be recorded one by one by choosing the option "New Test Case" from the "File" Menu.


Step 3 − The individual tests are saved with a name along with saving a "Test Suite".

<img width="652" height="293" alt="image" src="https://github.com/user-attachments/assets/eb851415-7b40-4117-a17b-2813d9a000b4" />

# Executingthe RecordedTest
The recorded scripts can then be executed either by clicking "Play entire suite" or "Play current test" button in the toolbar.

Step 1 − The Run status can be seen in the status pane that displays the number of tests passed and failed.

Step 2 − Once a step is executed, the user can see the result in the "Log" Pane.

Step 3 − After executing each step, the background of the test step turns "Green" if passed and "Red" if failed as shown below.

<img width="940" height="498" alt="image" src="https://github.com/user-attachments/assets/afee70c9-9672-40b4-9364-adc436bdb99b" />

# Selenium IDE Script Debugging
This section deals with debugging the Selenium IDE script. Debugging is the process of finding and fixing errors in the test script. It is a common step in any script development. To make the process more robust, we can make use a plugin "Power Debugger" for Selenium IDE.

Step 1 − To install Power Debugger for Selenium IDE, navigate to https://addons.mozilla.org/en- US/firefox/addon/power-debugger-selenium-ide/ and click "Add to Firefox" as shown below.

<img width="917" height="324" alt="image" src="https://github.com/user-attachments/assets/a7333a85-24ce-43d9-8846-19431f1d104e" />

Step 2 − Now launch 'Selenium IDE' and you will notice a new icon, "Pause on Fail" on recording toolbar as shown below. Click it to turn it ON. Upon clicking again, itwould be turned "OFF".

<img width="913" height="426" alt="image" src="https://github.com/user-attachments/assets/adf31ee7-ecc8-4027-ad8f-f5743d01a7f5" />

Step 3 − Users can turn "pause on fail" on or off any time even when the test is running.

Step 4 − Once the test case pauses due to a failed step, you can use the resume/step buttons to continue the test execution. The execution will NOT be paused if the failure is on the last command of any test case.

Step 5 − We can also use breakpoints to understand what exactly happens during the step. To insert a breakpoint on a particular step, "Right Click" and select "Toggle Breakpoint" from the context- sensitive menu.

<img width="924" height="663" alt="image" src="https://github.com/user-attachments/assets/4cd450d1-0ac2-466a-a527-db824cad2f6e" />

Step 6 − Upon inserting the breakpoint, the particular step is displayed with a pause icon as shown below.

<img width="923" height="576" alt="image" src="https://github.com/user-attachments/assets/295592c7-95f9-4f69-87ea-052adf73f15f" />

Step 7 − When we execute the script, the script execution is paused where the breakpoint is inserted. This will help the user to evaluate the value/presence of an element when the execution is inprogress.

<img width="923" height="506" alt="image" src="https://github.com/user-attachments/assets/a0e02617-1ffa-4bb6-8a58-4bc4d3c2d41e" />

# Inserting Verification Points
This section describes how to insert verification points in Selenium IDE.

The test cases that we develop also need to check the properties of a web page. It requires assert and verify commands. There are two ways to insert verification points into the script. To insert a verification point in recording mode, "Right click" on the element and choose "Show all Available Commands" as shown below.

<img width="921" height="520" alt="image" src="https://github.com/user-attachments/assets/25474912-08a5-4eb1-95ec-6f1a5572bd87" />

We can also insert a command by performing a "Right-Click" and choosing "Insert New Command".

<img width="931" height="557" alt="image" src="https://github.com/user-attachments/assets/bfd784f5-4cf8-4054-a063-7bb83c8e6132" />

After inserting a new command, click 'Command' dropdown and select appropriate verification point from the available list of commands as shown below.

<img width="928" height="332" alt="image" src="https://github.com/user-attachments/assets/5ba2f900-0b41-4a52-9791-088a761da8c9" />

Given below are the mostly used verification commands that help us check if a particular step has passed or failed.

 verifyElementPresent  assertElementPresent  verifyElementNotPresent  assertElementNotPresent  verifyText  assertText  verifyAttribute  assertAttribute  verifyChecked  assertChecked  verifyAlert  assertAlert  verifyTitle  assertTitle

# SynchronizationPoints
During script execution, the application might respond based on server load, hence it is required for the application and script to be in sync. Given below are few a commands that we can use to ensure that the script and application are in sync.

waitForAlertNotPresent

waitForAlertPresent

waitForElementPresent

waitForElementNotPresent

waitForTextPresent

waitForTextNotPresent

waitForPageToLoad

waitForFrameToLoad

# Selenium Pattern Matching
□ This section deals with how to work with regular expressions using IDE. Like locators, patterns are a type of parameter frequently used by Selenium. It allows users to describe patterns with the help of special characters. Many a time, the text that we would like to verify are dynamic; in that case, pattern matching is very useful.

Pattern matching is used with all the verification point commands - verifyTextPresent, verifyTitle, verifyAlert, assertConfirmation, verifyText, and verifyPrompt. There are three ways to define a pattern −

Globbing

Globbing

regular expressions, and exact patterns.

Most techies who have used file matching patterns in Linux or Windows while searching for a certain file type like *.doc or *.jpg. would be familiar with term "globbing"

Globbing in Selenium supports only three special characters: *, ?, and [ ].

• * − matches any number of characters.

• ? − matches a single character.

□ [ ] − called a character class, lets you match any single character found within the brackets. [0- 9] matches any digit.

To specify a glob in a Selenium command, prefix the pattern with the keyword 'glob:'. For example, if you would like to search for the texts "tax year 2013" or "tax year 2014", then you can use the golb "tax year *" as shown below.

However the usage of "glob:" is optional while specifying a text pattern because globbing patterns are the default in Selenium.

<img width="875" height="281" alt="image" src="https://github.com/user-attachments/assets/f68afa90-8c6b-472a-adbc-3e0e44c82a78" />

# ExactPatterns
Patterns with the prefix 'exact:' will match the given text as it is. Let us say, the user wants an exact match with
the value string, i.e., without the glob operator doing its work, one can use the 'exact' pattern as shown below. In this example the operator '*' will work as a normal character rather than apattern- matching wildcard character.

<img width="879" height="286" alt="image" src="https://github.com/user-attachments/assets/553a99cf-dab9-468c-b14e-99f8ed0150c8" />

# RegularExpressions
Regular expressions are the most useful among the pattern matching techniques available. Selenium supports
the complete set of regular expression patterns that Javascript supports. Hence the users are no longer limited
by *, ? and [] globbing patterns.

To use RegEx patterns, we need to prefix with either "regexp:" or "regexpi:". The prefix "regexpi" is
case- insensitive. The glob: and the exact: patterns are the subsets of the Regular Expression patterns.
Everything that is done with glob: or exact: can be accomplished with the help of RegExp.

Example
For example, the following will test if an input field with the id 'name' contains the string 'tax year', 'Tax Year',
or 'tax Year'

<img width="797" height="253" alt="image" src="https://github.com/user-attachments/assets/87b3b8f2-7200-42bf-b7ec-8a8e1c51a0f2" />

# Selenium User Extensions
The Java script that allows users to customize or add new functionality.

It is easy to extend Selenium IDE by adding customized actions, assertions, and locator-strategies. It is done with the help of JavaScript by adding methods to the Selenium object prototype. On startup, Selenium will automatically look through the methods on these prototypes, using name patterns to recognize which ones are actions, assertions, and locators.

Let us add a 'while' Loop in Selenium IDE with the help of JavaScript.

Step 1 − To add the js file, first navigate to https://github.com/darrenderidder/sideflow/blob/master/sideflow.js and copy the script and place save it as 'sideflow.js' in your local folder as shown below

<img width="716" height="185" alt="image" src="https://github.com/user-attachments/assets/4266220c-ce97-41f0-a3b8-52f61ea4ea4e" />

Step 2 − Now launch 'Selenium IDE' and navigate to "Options" >> "Options" as shown below.

<img width="945" height="270" alt="image" src="https://github.com/user-attachments/assets/002c3997-ef67-4375-a8a5-aa71d118a580" />

Step 3 − Click the 'Browse' button under 'Selenium Core Extensions' area and point to the js file that we have saved in Step 1.

<img width="805" height="314" alt="image" src="https://github.com/user-attachments/assets/da790ca2-76cc-4e60-aa44-5699ffaa40d5" />

Step 4 − Restart Selenium IDE.

Step 5 − Now you will have access to a few more commands such as "Label", "While" etc.

Step 6 − Now we will be able to create a While loop within Selenium IDE and it will execute as shown below.

<img width="941" height="424" alt="image" src="https://github.com/user-attachments/assets/3ea35563-f29b-4a53-af95-129e2c379337" />

# Result:
Thus, the study of selenium web testing tool is conducted and the results were noted.
