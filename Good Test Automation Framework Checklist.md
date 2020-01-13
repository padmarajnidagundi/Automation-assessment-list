# Test Automation Framework Checklist
Automation assessment list
Here is the list of Good Test Automation Framework Checklist

 <li>Reusable methods or page classes – Create reusable methods wherever you find repeatable code. Don’t duplicate the same thing multiple tests.
 <li>Data driven – Test data like URLs / User Names and Passwords are maintained in properties file or Excel files. Don’t hard code everywhere.
 <li>Explicit waits – Thread sleep delays everywhere in test scenarios. Also reduce the performance. So try to use Explicit waits.
 <li>Variables names should be meaning full.
 <li>Try to use public API’s instead of creating more utility files from scratch.
 <li>Reporting – Don’t print results using System.out.println. Always use Reporting mechanisms.
 <li>Headless test execution support when there is a necessity
 <li>Don’t hard code absolute paths given to files used in the framework, rather than just putting the files into a folder relative to the framework.
 <li>Data should read from test scenarios but not in page classes.
 <li>Try to reduce Unnecessary program loops in the code.

 <li>Test framework should organize into well-defined packages
<br>Pages – Where page classes reside
<br>Test – Where test reside
<br>Utility – Where utility classes resides. Such as reporting and file reading classes

 <li>Documentation on deploying the test framework
 <li>Logging facility for frameworks, when something goes wrong
 <li>Base driver support to run in multiple browsers
 <li>Good naming conventions for page class and test class naming
 <li>Tests should be independent when executing
 <li>Detailed reports on test executions and failures
 <li>Use design patterns and principals
 <li>Use BDD – But this is not mandatory always
 <li>Screen shots on failures - Helps failure investigation easy.
 <li>Use dependency management like Maven for Java, Nuget for .net, PIP for Python
  
  Ref http:// www pavantestingtools com/2019/11/good-test-automation-framework-checklist_10.html
