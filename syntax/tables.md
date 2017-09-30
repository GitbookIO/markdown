# Tables

Tables aren't part of the core Markdown spec, but they are part of GFM (GitHub Markdown) and Markdown here (on GitHub) supports them.

Here is an example of table in markdown and the output below:

    | Tables        | Are           | Cool  |
    | ------------- |:-------------:| -----:|
    | col 3 is      | right-aligned | $1600 |
    | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |

Output:
***

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

* Colons (:)  can be used to align columns.  
* The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily.  
* You can also use inline Markdown.

Example:

    Markdown | Less | Pretty
    --- | --- | ---
    *Still* | `renders` | **nicely**
    1 | 2 | 3

Output:  
***
    
Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

