# Ruby Method Assignment Bug

This repository demonstrates a common, yet subtle, error in Ruby related to method assignment.  When defining a method without an `=` at the end of the method name, the method becomes read-only.  Attempting to assign a value to the method will not modify the instance variable.

The `bug.rb` file shows the buggy code, and `bugSolution.rb` provides a corrected version.

This example highlights the importance of correctly defining methods in Ruby to avoid unexpected behavior and ensure data integrity.