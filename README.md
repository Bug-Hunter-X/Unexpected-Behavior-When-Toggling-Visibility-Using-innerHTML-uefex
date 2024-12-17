# Uncommon HTML Bug: Incorrect Visibility Toggle
This repository demonstrates an uncommon bug in HTML related to controlling element visibility using innerHTML.  The issue arises from incorrectly using innerHTML to hide a div, which results in the content being completely removed instead of merely hidden.

## Bug Description
The provided HTML code attempts to toggle the visibility of a div by setting its innerHTML to an empty string. This approach is incorrect, as innerHTML completely removes the content, rather than simply hiding it.

## Solution
The bug is fixed by using CSS display property to toggle visibility instead of manipulating innerHTML.  This maintains the div's content while controlling its display.