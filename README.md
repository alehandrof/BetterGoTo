BetterGoTo
==========

## Comment Bang

Allows you to add comments to your code that will appear in the Symbol List.

The syntax is:

	# ! This comment will appear in the Go To Symbol list.

You can also add a horizontal ruler as follows:

	# !-

(You can add more dashes if you like, as long as the first one is adjacent to the bang.)

### Notes

Comment Bang will work with all comments as long as there's at least one space/tab between the comment punctuation and the bang.

### Bugs / Todo

There are issues with consecutive single line comments, such as this:

	// ! This will appear in the Go To list
	// ! But this won't.