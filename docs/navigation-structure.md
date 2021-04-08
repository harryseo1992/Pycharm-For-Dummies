---
layout: default
title: Testing Your Codes
nav_order: 5
---

# Testing Your Codes
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

## Introduction

When coding, it is important to document them as well for future coders. It is a lot like writing this tutorial! It helps the reader understand what each of the function will do with the values it has been given. Then, we need to showcase or "test" out the functions to promote better understanding by showing off what they can do. We can do this via doctesting and unit testing.

---

## Doctesting Documentations

1. Under the function, type double-quotation mark (") 3 times. This sets up the space for doctest documentations
2. Click on the middle on 6 double-quotation marks and press "space".

As seen above, parameters and return values are set automatically by PyCharm.

3. Write out a sentence that briefly describes what the function does. Start with a verb.
4. Write out the type of parameter that the function takes in.
5. Write out the type and description of what it returns.

```
--------NOTE--------
If the function does not return anything, there is no need to type out the information for "return".
```

6. Type ">>>" to write out the function or variables needed for doctesting.
7. Type out what is expected if you run the program to carry out the function.
8. At the very end of the page, type out the following code:
```
if __name__ == '__main__':
    main()
    import doctest


--------NOTE--------
If you type "main", PyCharm will give you an option to fill out "if __name__ == '__main__':...". 
```
7. There you have it! That's how you doctest in PyCharm.


## Using "Generate..." for Unit Testing

The main navigation for your Just the Docs site is on the left side of the page at large screens and on the top (behind a tap) on small screens. The main navigation can be structured to accommodate a multi-level menu system (pages with children and grandchildren).

By default, all pages will appear as top level pages in the main nav unless a parent page is defined (see [Pages with Children](#pages-with-children)).

---



The result is shown at [the top of this page](#navigation-structure) (`{:toc}` can be used only once on each page).
