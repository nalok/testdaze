testdaze
========
Using Jbehave. Starting simple...

------------------------------------------------------------
Scenario: 1 add


Given a variable x with value 2
When I add x with 4 
Then x should equal 6

Scenario: 2 multiply


Given a variable x with value 8
When I multiply x by 8 
Then x should equal 64

Scenario: 3 multiply-fail


Given a variable x with value 3
When I multiply x by 3 
Then x should equal 10


Scenario: 4 power


Given a variable x with value 2
When I power x to 3 
Then x should equal 8



