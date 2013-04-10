Testing
=======

Description of Testing Method
The tests are organized so that each user task has its own file. These files can be run on their own or congruent with any other test files. The tests are implemented in Python using the built in PyUnit test libraries. To mimic the HTTP post and get operations, a built-in library called mock is utilized. Each file is expected to go through as many, if not all, of the edge cases possible for each operation. Each file is expected to test its specific operation on both the mobile and web applications. 

Execution of Testing
To execute all tests at once, there is a bash script called runtests.sh. Simply run the script and all test will be executed that are in the tests folder. 
To execute a particular test, simply run the python file.
The results in both cases will be printed out to terminal. 