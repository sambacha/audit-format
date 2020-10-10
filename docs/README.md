# Design Spec

Strings should be quoted with double-quotes instead of single-quotes.
[solidity style guide #other-recommendations](https://solidity.readthedocs.io/en/develop/style-guide.html#other-recommendations)

Spaces are the preferred indentation method.
[solidity style guide #tabs-or-spaces](https://solidity.readthedocs.io/en/develop/style-guide.html#tabs-or-spaces)

[solidity style guide #code-layout](https://solidity.readthedocs.io/en/develop/style-guide.html#code-layout)

`npm install --save-dev prettier prettier-plugin-solidity`

### Order of Layout

Layout contract elements in the following order:

Pragma statements
Import statements
Interfaces
Libraries
Contracts

Inside each contract, library or interface, use the following order:

Type declarations
State variables
Events
Functions

### Naming Styles

To avoid confusion, the following names will be used to refer to different naming styles.

b (single lowercase letter)
B (single uppercase letter)
lowercase
lower_case_with_underscores
UPPERCASE
UPPER_CASE_WITH_UNDERSCORES
CapitalizedWords (or CapWords)
mixedCase (differs from CapitalizedWords by initial lowercase character!)
Capitalized_Words_With_Underscores
