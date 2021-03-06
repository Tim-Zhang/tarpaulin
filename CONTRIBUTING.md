# Contributing to Tarpaulin

Contributions to Tarpaulin are always welcome and encouraged. Check below to
information on the various methods of contributing.

## Feature Requests

Currently there's no mechanism for feature requests as such so just use the
Github issue tracker.

## Reporting bugs

If you find an issue in Tarpaulin, please report it using the Github issue
tracker. When you make the issue if you could provide the following information
we can recreate the issue and resolve it quicker.

* A description of the problem
* Tarpaulin output
* The rust project you ran Tarpaulin on
* Your linux distro and version (output of `uname -a` is sufficient)
* Version of rustc used

The verbose output of Tarpaulin is preferred but isn't always necessary. If you
want to include the verbose output and it's very long a pastebin link or similar
is ideal.

If there's a reason you can't share your project code publicly, a small example
project which recreates the issue would help a great deal. You can always
download one of the example projects used to test Tarpaulin from tests/data and
see if they work.

## Pull Requests

Pull requests are welcome, after you've implemented your feature test it on your
own system and submit a PR. Make sure to explain what the feature adds to 
Tarpaulin and any information you feel will make the review go easier. 

Tarpaulin uses the gitflow model so for new features branch off of the develop
branch and add your changes.

Any changes which break existing functionality won't be merged, but you'll
receive feedback and help to resolve those issues and close the PR.
