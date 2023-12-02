# Twitter-harvest scripting

Library = https://github.com/mongolab/twitter-harvest


search_keyword = "your_keywords lang:english -example"

## Params

- (lang:z) = Language
    - Examples = (lang:id) = Indonesian
        
- -<x> = Menghindari suatu keyword
    - Examples = -# = Menghindari keyword 

## Usage

1. Untuk mencari keyword pandemi & surabaya, juga filtering keyword dari #

```bash
search_keyword = 'pandemi AND Surabaya -#'
```

2. Untuk mencari keyword **pandemi & surabaya, juga filtering keyword dari #, dan filtering bahasa lang:<language>**

```bash
search_keyword = 'COVID AND Surabaya - lang:id'
```

3.
