# Groovy: Missing Return Statement in Conditional Block

This example demonstrates a common coding error in Groovy: forgetting to explicitly return a value from all possible code paths within a conditional statement. 

The `bug.groovy` file contains a method with a conditional statement that lacks a return statement in one branch. This omission can lead to unexpected null values or runtime errors.

The `bugSolution.groovy` file shows the corrected method with a return statement added to ensure that a value is returned in all cases.