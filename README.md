# Premature Loop Termination Bug in Java

This repository demonstrates a common error in Java loops where the loop terminates prematurely because of a break statement within the loop's conditional logic. The `bug.java` file shows the erroneous code, while `bugSolution.java` provides the corrected version.

## Description

The provided Java code has an unintended loop termination due to a misplaced break statement. This can lead to unexpected program behavior and incorrect results, especially in scenarios where the loop should execute a fixed number of iterations regardless of the conditional statement.