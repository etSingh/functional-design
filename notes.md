# Notes

# ADTs
+ Sum type - Contains only one of it's "terms". You can get more compact code by taking the sum type and pushing it deeper.
+ Product type - Contains all of it's "terms".

# Composing Operators
+ Output of an operator can be plugged into itself - This is the primary design feature of creating operators that
are composable - Feedback loops - Lego blocks that can be attached in various ways.

# General Design
+ Only add methods in a sealed trait that are `deterministic`.
+ Look to companion objects for making constructors.