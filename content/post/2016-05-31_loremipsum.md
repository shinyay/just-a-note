+++
categories = ["miscellaneous"]
date = "2016-05-31T10:47:06Z"
draft = true
slug = "lorem-ipsum-test"
tags = ["", ""]
title = "First post: Hugo operation check"

+++

# Lorem ipsum

---

## Plain text test
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Syntax Hilighting test
```
<section id="main">
  <div>
    <h1 id="title">{{ .Title }}</h1>
    {{ range .Data.Pages }}
      {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
```

## Markdown Sytax test
### Blockquotes
> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");
---
```
> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");
```

### Lists
*   Red
*   Green
*   Blue

---
```
*   Red
*   Green
*   Blue
```

#### Lists - blockquote
*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.

---
```
*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.
```

#### Lists - codeblock
*   A list item with a code block:

        <code goes here>

---
```
*   A list item with a code block:

        <code goes here>
```

### Links
This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

---
```
This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.
```

#### Links - reference style
This is [an example][id] reference-style link.
[id]: http://example.com/  "Optional Title Here"

---
```
This is [an example][id] reference-style link.
    [id]: http://example.com/  "Optional Title Here"
```

I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

    [1]: http://google.com/        "Google"
    [2]: http://search.yahoo.com/  "Yahoo Search"
    [3]: http://search.msn.com/    "MSN Search"

---
```
I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

    [1]: http://google.com/        "Google"
    [2]: http://search.yahoo.com/  "Yahoo Search"
    [3]: http://search.msn.com/    "MSN Search"
```

