<%*
  let title = tp.file.title
  if (title.startsWith("Untitled")) {
    title = await tp.system.prompt("Title");
    await tp.file.rename(title);
  } 
  
  tR += "---"
%>
title:  <%* tR += title %>
Tags: DisscussionNote, week(number),
Type: DiscussionNote

---
## Do Not Alter the Above Code
---
*Created: <% tp.date.now("Do MMMM YYYY") %>
Last modified: <% tp.file.last_modified_date("Do MMMM YYYY") %>
Your Name: [[]] *Put link to your bio here* 
Week:  *enter hashtag and week number: ie. #week1 #week2  #week3  etc.*
Tags: #SC *tag your initials and any tags you think are relevant to the post. Keep them as brief as possible ie. History, Identity, Heritage, Coins, Dogs_Bark, Cats_Meow*

---
### Disclaimer:

#### Remember to change the note title to DN_YourName_Week1 (or relevant week). DN = Discussion Note

###### It is important to fill in all the prompts. This will help us analyze how our ideas connect or do not connect. Furthermore, it will help make collaboration of your final project easier. 

---
### Discussion

- Type a discussion post in this section. 

- Remember, write as if you are writing for an academic paper. Use full sentences. 
    
- CITE!!  Include sources in the note.
    
-   Be precise, clear and brief.

---
### Citations
[Put title of article here - keep the square brackets using  [[AAA Citation Style]]](Put the link to the article, here)

---
### Related Links

{Put in 1-5 links below. Think about **how the newly created notes connect with your existing knowledge**. If you find some connections, connect the new notes with the older notes already in your system. To find these, ask:

-   How does this idea fit into what I already know?
-   What does this idea mean for some other idea that I already have?
-   Does this add to, contradict, or explain another idea I already have?

You link to other notes by putting them in square brackets. Remember that Obsidian will auto search as you type for notes with those words. Once you've selected a note, you can add the ^ symbol to link to a subheading or block within a note, too}

##### Examples:
[[Syllabus]]
[[Reflection_Paper]]

---
### My Reply

Enter the link to your reply notes in [[]]
##### Examples:
[[RN1_MyName_Week1]]
[[RN2_MyName_Week1]]
