# Ruby puts statement with assignment

This example demonstrates an unexpected behavior in Ruby when combining assignment with the `puts` method.  While the assignment itself works correctly, the output of `puts` is not what one might intuitively expect.

The issue lies in how Ruby evaluates the expression within `puts`.  The assignment returns the assigned value, and `puts` then prints that value.  This can lead to unexpected results if you're not aware of this behavior.