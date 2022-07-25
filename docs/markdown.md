# Markdown Syntax
This section describes the following:

- [Note](#note)
- [Tip](#tip)
- [Important](#important)
- [Warning](#warning)
- [Hyperlink](#hyperlink)
- [Image](#image) 
- [List - Unordered](#list-unordered)
- [List - Ordered](#list-ordered)
- [List - Nested](#list-nested)
- [Procedure Title](#procedure-title)

---

## Note

### A simple note

> **Note:** add your note text here. 

For more than one note, use **Notes** to indicate plural as shown in example below:

### A Note with list
> **Notes:**
>- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.   
>- Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum

### A complicated note with nested lists

> :note: **Notes:**
>- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
>- Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. 
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum:  
    - Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum  
    - Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum

---

## Tip

> :tip: **Tip:** Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum 

## Important

> :important: **Important:** Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum 

## Warning

> :warning: **Warning:**
>- Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
>- Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum

## Hyperlink
This section describes how to add various links.

### Inline links

| **Use This** | **Do not Use This** | **Notes**|
|---|---|---|
|```Click [here](destination url or markdown file) to know more.``` | ```Click <a href="destination url"> here </a> to know more.``` | This is not a preferred method of adding an inline link because the html tag might not render well in some of the markdown outputs. | 


---

## Image 
```
<kbd>![Alt text](./images/image-name.png ':size=100%')</kbd>
```
---
## List Unordered
Use only `-` for unordered lists. Using `+`, `*`, or a mix of these (or with `-`) does not render properly in all builds/browsers.

For sub nesting, please use `tab` key or 3 spaces for each additional level.

**code**
```
- item 1
- item 2
    - sub-item 1
    - sub-item 2
        - further nested item 1
        - further nested item 2
```        
**Output**
- item 1
- item 2
    - sub-item 1
    - sub-item 2
        - further nested item 1
        - further nested item 2
---
## List Ordered

Use `1. ` for all list items. Markdown and output builders automatically take the next number of alphabet as the case maybe.

1. item 1
1. item 2
1. item 3
1. item 4


---
## List Nested

### Example

```
- item 1
- item 2
    - sub-item 1
    - sub-item 2
        - further nested item 1
        - further nested item 2
```        

- item 1
- item 2
    - sub-item 1
    - sub-item 2
        - further nested item 1
        - further nested item 2

---

### Example

```
- item 1
- item 2
    1. sub-item 1
    2. sub-item 2
        - further nested item 1
        - further nested item 2
```

- item 1
- item 2
    1. sub-item 1
    2. sub-item 2
        - further nested item 1
        - further nested item 2

---

### Example 

```

1. item 1
1. item 2
    - sub-item 1
    - sub-item 2
        1. further nested item 1
        1. further nested item 2
```        

1. item 1
1. item 2
    - sub-item 1
    - sub-item 2
        1. further nested item 1
        1. further nested item 2

---
## [Procedure Title](#procedure-title)

- Use title case
- Start with a verb (not a gerund)


!



