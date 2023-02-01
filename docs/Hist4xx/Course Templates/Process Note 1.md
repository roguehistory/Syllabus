<%*
  let title = tp.file.title
  if (title.startsWith("Untitled")) {
    title = await tp.system.prompt("Title");
    await tp.file.rename(title);
  } 
  
  tR += "---"
%>
title:  <%* tR += title %>
Tags:
Type: Comps Note

---
*Created: <% tp.date.now("Do MMMM YYYY") %>
Last modified: <% tp.file.last_modified_date("Do MMMM YYYY") %>
Book/Article Title:
Zotero: 
URL:
Project: [[]]
Thematic Category: [[]]

---
### Tags:


---

# What I was trying to do

_description in own words; link to relevant tutorials or other materials_

-   link to the relevant github repo: like this: `[repo title](https://github.com/user-name/relevant-repo)`

## what I did

-   step 1
    -   results
-   step 2
    -   results
-   step 3
    -   results

_drop images, screenshots as relevant into the vault, link to them here. Use backticks to copy in relevant code snippets etc_

```
# example R code
data <- read.csv("data")
```

## challenges

_error messages, unclear instructions, gaps in my knowledge, links to relevant asks for help on discord, stackoverflow posts, websites I went to for help_

## thoughts on where to go next

_what can I do? who can I talk to? links to posts in discord, helpf fora, etc. links to other research projects etc_