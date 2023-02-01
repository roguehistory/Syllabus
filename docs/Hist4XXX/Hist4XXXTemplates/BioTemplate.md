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
Type: BioNote

---
## Do Not Alter the Above Code
---
*Created: <% tp.date.now("Do MMMM YYYY") %>
Last modified: <% tp.file.last_modified_date("Do MMMM YYYY") %>

Name:  [[]] *Insert name in double brackets (Put pronouns in brackets [Optional])* 
tags: tag1, *Use hashtag (#) initials. i.e. #SC for Scott Coleman*
Project: [[Hist4xxx]] 

---

## Bio: Tell us about you
Help me and your peers get to know you better. Fill out the below prompts or share anything else you would like (but only what you are comfortable with. I will not pressure you to fill in everything).  The sky is the limit.

###### Some inspiration: 
*Where are you from? 
What are your interests? 
Why did you take this course? 
What are your goals? 
What are your expectations? 
What do you hope to learn? 
Miscellaneous random Stuff?* 

--- 

## Course-Related Questions: 

###### Have you studied coins before? If yes, when? Where? What types?

###### Have you ever studied Byzantium? If yes, when? Where? 

###### What program are you in? What is your Major/Minor

###### Misc (Anything else you want us to know about you?)

---

### Related Links
If you want to share, put social media links here (Blog, FB, Twitter [if it is still in existence], Discord, etc.)
Remember to use [BlogName](www.myblogiscool.something)


[[Syllabus]]