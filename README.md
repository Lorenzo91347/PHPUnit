# Introduction to PHPUnit

This project is intended to introduce the developer to basic functionalities of PHPunit.

 ## Steps

 1. Create a new folder through the terminal with "mkdir NameOfProject".

 2. Navigate to the folder with "cd NameOfProject".

 3. Initiate a new project (must have Composer installed on your machine),
 with "composer init", it will take you through a series of steps, of which 
 for the purpose of this project you can leave the defaults.

 When asked which dependencies for "require" and "require/dev" you need,
 write "phpunit/phpunit", which will install the library after all of the prompts
 are cleared.

 After Composer has initialized your project, you are ready to begin!

 Note: make sure the "autoload" section of your composer.json is correct,this is the path where PHPUnit will search for the 
 class to be tested.
 
 4. Start writing up a class with some simple functions that you want to test(e.g. UserName(),UserAge() and so on).

 5. Create a separate folder called "tests", this is usually for convention, so whoever looks at the project does not mix up the actual project with your tests.

 6. Start writing up some tests,feel free to use the already present code or write something else altogether.

 7. Test your test! In the terminal write "./vendor/bin/phpunit tests", or "./vendor/bin/phpunit  tests/UserTest.php",
 if you want only that particular test to run.

 8. The test will run and display information on the result, if you use the exact same code in this project there
 will be one failure by design,to show that you can test the behaviour of deliberate failures in your flow.

 ## And that is all!

 Do play around with the code and different PHPUnit keywords,so you'll be able to write even more complex tests,
 with checking functionality being an integral part of a developer's job.

 ## Links:
    
 1. Webpage for download and documentation of Composer:[https://getcomposer.org/]
 2. Documentation of the latest version of PHPUnit,which is used here:[https://docs.phpunit.de/en/11.3/]
 3. The FreeCodeCamp page which inspired this project:[https://www.freecodecamp.org/news/test-php-code-with-phpunit/]