# CSS !important Overuse Bug

This repository demonstrates a common CSS bug involving the overuse of the `!important` flag.  Overusing `!important` makes CSS difficult to maintain and debug because it creates unpredictable styling.

## Bug Description
The `bug.css` file contains CSS that uses `!important`. This makes it difficult to override styles.  The solution is to refactor the CSS to avoid using `!important`.