* This readme file is used to help anyone that reads it get a better understanding of how the project went and why I
  chose this website. This readme is tarrgeted towards the instructor, but I don't think that anyone else would have 
  difficulties understanding it.
* It states all the issues and obstacles encountered during the makeing of the website.
** No need to state the date as it will be present on the git log history.
=====================================================================================================================
----------------------
1.Reason For Choice: |
----------------------
    - I chose this website because it tells a lot about the person without using words and paragraphs to 
      discribe him, only (video/audio).
    - plus the design of the website is mesmerising and easy to navigate through. 
---------------------
2.Major challenges: |
---------------------
    - On the home page, in the navigation part on the top-left corner, I wasn't able to remove the underline 
      on the anchor tags(links) as it would requiere the style attribute which is not allowed in this project.

    - I had to use the 'valign = "top"' tag inorder to make the navigation pane stick in the top left corner of
      the webpage to increase the simmilarity of the web page with the base link. 
      (Note!!, the 'valign' atribute is no longer used in hTML5.)
    
    - When users scroll to the botto of any page, the navigation pane is either fully or partially invisible.
      this is because it is not allowed to use any css atributes, like the 'position: fixed' property.

    - In the about bape I couldn't easily make texts float next to my image so I had to use a table which makes 
      the process tiring. 

    - Since the anchor tags are embeded in the <td></td> tag of the table it is hard to maintain the width and 
      height of the anchor tag icons/logos. If css was available we could've used the display:"inline"; styling
      attribute but it is out of our reach in this project.

-------------------
3.Lessons Learnt: |
-------------------
    - CSS is a really important styling tool that lets you have 100% control over how you want your website to
      look.
  
    - You might have noticed the rather unusual naming of my HTML files. But that is because I wanted the file
      name to be differen from the name that is displayed in the website itself, (to keep safe from hackers). 
      I did it based on your recommendation on one of our lab sessions.
    
    - Since this website uses tables and its attributes intensely, I have aquiered a good amount of skills in 
      manipulating 