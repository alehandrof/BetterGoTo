BetterGoTo
==========

## Comment Bang

Allows you to add comments to your code or markup that will appear in the Symbol List.

The syntax is:

	# ! This comment will appear in the Go To Symbol list.

A single space *before* the bang is mandatory. So:

	// !This is valid
	//! But this invalid

In the case of multi-line comments, only the first line will be preserved. E.g.,

	<!-- This line will appear in the Go To Symbol list
	     but this one won't -->

You can add a horizontal ruler by placing a hyphen immediately after the bang:

	# !-

*Note.* You can add more dashes or any other character you like, but they will not appear in the Go To Symbol list.

### Bugs / Todo

There is a known issue with consecutive single line comments, such as this:

	// ! This will appear in the Go To list
	// ! But this won't.