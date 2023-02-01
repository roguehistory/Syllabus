<%*
  let title = tp.file.title
  if (title.startsWith("Untitled")) {
    title = await tp.system.prompt("Title");
    await tp.file.rename(title);
  } 
  
  tR += "---"
%>
title:  <%* tR += title %>
Tags: week(number), ReplyNote,  
Type: ReplyNote

---
## Do Not Alter the Above Code
---
*Created: <% tp.date.now("Do MMMM YYYY") %>
Last modified: <% tp.file.last_modified_date("Do MMMM YYYY") %>
Your Name: [[]] *Put link to your bio here* 
Project: *enter hashtag and week number: ie. #week1 #week2  #week3  etc.*
Tags: #SC *tag your initials and any tags you think are relevant to the post. Keep them as brief as possible ie. History, Identity, Heritage, Coins, Dogs_Bark, Cats_Meow*


---
### Disclaimer:
#### Remember to change the note title to RN1_YourName_Week1 (or relevant week) or RN2_YourName_Week1 (or relevant week). The RN1, RN2, RN3...so on, refer to ReplyNote 1, 2, 3, or 4... This is to track how many replies you make. 

###### It is important to fill in all the prompts. This will help us analyze how our ideas connect or do not connect. Furthermore, it will help make collaborating on your final project easier. Not to mention my Diabolical plan!! 


---
### Discussion
Type in this section a 150-word reply. 

- Remember, write as if you are writing for an academic paper. Use full sentences. Be precise, clear and concise.
    
- CITE!!  Include sources in the note.

---
### Citation
[Put title of article here - keep the square brackets using  [[AAA Citation Style]]](Put the link to the article, here)

---
### Related Links

{Put in 1-5 links below. Think about **how the newly created notes connect with your existing knowledge**. If you find some connections, connect the new notes with the older notes already in your system. To find these, ask:

-   How does this idea fit into what I already know?
-   What does this idea mean for some other idea that I already have?
-   Does this add to, contradict, or explain another idea that I already have?

You link to other notes by putting them in square brackets. Remember that Obsidian will autosearch as you type for notes with those words. Once you've selected a note, you can add the ^ symbol to link to a subheading or block within a note, too}

Examples:
[[Syllabus]]
[[DN_MyName_Week1]]