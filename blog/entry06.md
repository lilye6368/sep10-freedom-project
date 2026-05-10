# Entry 6
##### 5/9/26
#### Lily Ebraheim

---

## Content: MVP

#### Content 1: How I Made my MVP

  - I made my MVP by first planning everything out on a timeline so I didn’t get completely lost while making my website. I started by making ideas on 4/24 *(I didn't start the page yet but I was still looking for a few ideas before I went into full on coding)* and decided to focus on a health and wellness technology type of website. After that, I tried thinking  about colors and the code of the layout of the page so the website would look not *AS* messy and a little bit easier to read. By 4/29, I created a wireframe which helped me pretty much know where each section like my <b>overview (First Section)</b>, <b>existing technology (Part A)</b>, and <b>future technology (Part B)</b> would go before I even started coding. After that, I started this time building the site using html right around 5/1 and kept adjusting things as I went just so the layout would look maybe a little bit more organized.

 - Also while I was making my mvp I kinda mostly tried focusing on just getting everything working first instead of making it look good right away. I added images, text cards, and sections so the content was structured clearly and easy to read. I also used <b>animate.css</b> to add small effects like pulsing titles, which made the site feel a bittt more active if you get what I mean. Overall, my mvp is basically a working version of my idea that shows the structure and content of my website, even if it’s still pretty simple since I didn't really add advanced stuff since it's just basic html right now.
 - <b>[CODE BELOW SHOWING THAT THE MVP BUILD IS WORKING]</b>
    
```html
<!-- (this is a comment for myself to remember btw) this is the pulsing thing for like the box and the website name, also a recap just link the animate.css library to the head of the code and apply the pulse classes and infinite thing to the div for animation (this is just here so i remember) -->
        <div class="animate__animated animate__pulse animate__infinite" 
             style="width: 100%; height: 220px; background: white; border: 2px solid #333; text-align: center; margin-bottom: 60px; border-radius: 8px; display: flex; flex-direction: column; align-items: center; justify-content: center;">
            <img src="https://cdn-icons-png.flaticon.com/512/3239/3239121.png" style="width: 50px; margin-bottom: 10px;">
            <h1 style="font-size: 35px; margin: 0;">Health & Wellness Website</h1>
        </div>
<!-- overview stuff over here -->
        <h2 style="text-align: center; margin-bottom: 20px;">Overview / Context</h2>
           <div class="animate__animated animate__pulse animate__infinite" 
        <div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; margin-bottom: 50px;">
            <div style="flex: 1; min-width: 250px; background: white; border: 1px solid #ddd; padding: 15px; border-radius: 8px;">
             <div style="width: 100%; height: 150px; solid #999; margin-bottom: 10px; overflow: hidden;">
                
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSXKhGd8MnNNLj6SPtH7_pZIoT_XZgdNtDwQQ&s" style="width: 350px; height: 150px;">
</div>
   
                <p><b>This website is for exploring some cool technology and interesting tools used in healthcare. These can go from online platforms or websites to physical equipment.</b></p>
            </div>
               
            <div style="flex: 1; min-width: 250px; background: white; border: 1px solid #ddd; padding: 15px; border-radius: 8px;">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQD9PAJ8ORy8V-0-taV7Gr-sGSeND8SqhzuGw&s" style="width: 300px; height: 150px;">
                <p><b>By understanding some of these tools, you can get a better idea of how new or already existing ideas can save lives and improves health management overall.</b></p>
            </div>
        </div>
```

#### Content 2: Challenges & Takeaways I Had While Making my MVP

 - One of my challenges I had was keeping my layout consistent because when I changed one thing in flexbox or spacing, it would sometimes mess up other parts of the page, which was kinda weird at first but it was pretty easy to fix since I put comments for each of my sections so I didn't have to go looking for like my Part A section and stuff like that. I also struggled a bit with images not fitting correctly inside the cards, so I had to keep adjusting the width and height until everything looked even, after I was done figuring that out I applied the same numbers to each of my cards so they looked the same for the most part.

- One takeaway for me was that like planning kind of mattered a bit, because since I already finished most of my *timeline and my wireframe* fully, it made it way easier to build my MVP without forgetting which part I was gonna put where and helps me get an idea of where everything would have originally went to. I also learned that my mvp pretty much just didn't have to be that perfect, it just has to work and show the main idea clearly.
-  <b>[READ]: For this code, it's functional and doesn't actually have bugs in it, but I didn't have any html testers that saved how my code looked like when it broke so just imagine this code but the card accidently became taller than I wanted or too long so I had to change the width of it and I had to fix the image width too.
- <b>[CODE BELOW]</b>


```html
   <div class="animate__animated animate__pulse animate__infinite" 
            <div style="flex: 1; min-width: 250px; background: white; border: 1px solid #ddd; padding: 15px; border-radius: 8px;">
    <img src="https://i.ytimg.com/vi/v9y4pAL4MvQ/maxresdefault.jpg" style="width: 300px; height: 150px;">
                <p><b>AI Powered Radiology is also another special type of technology, which is when AI systems analyze radiology and pathology scans to detect or find different types of things. These things include cancer, fractures, and any anomaly quicker than normal traditional methods. They can do this by using specialized algorithms (Neural Networks) that can find patterns hidden in the pixels by looking at it, also the AI learns complex patterns tied to knowing whether the person would be healthy or not.   </b></p>
            </div>
        </div>
```
---

## Sources

- For my sources, I mainly or mostly used the <b>animate.css library</b> or just [Animate.CSS](https://animate.style/) itself to help me add animations like the pulsing effect on my title and the other sections of my website. I changed some sections of my code depending where it was to make it so some of my text was pulsing for an infinite amount of time or the bottom which only did it's animation once, as well as fixing my code so it was how I wanted it to be. I also used an [HTML compiler website](https://onecompiler.com/html/3y5x8jr6s) aka tester to write, test, and debug my code while building my website without it ruining my actual website, which helped me see changes and fix some code issues as I worked, it also was nice to use since I could just copy and paste my finished code from the html tester right back into my actual website. These two tools were what I used the most while finishing my website.

* [Animate.CSS](https://animate.style/)
  
* [HTML Tester Compiler](https://onecompiler.com/html/3y5x8jr6s)

---

## Enginnering Design Process (EDP)

- Right now in the <b>engineering design process,</b> I am mostly at the stage where I have already found my problem, planned my idea, and built my mvp website for the most part. I started by thinking about and planning my website idea, then I created a wireframe and timeline to organize what I wanted to build *(just so I don't forget and know pretty much what i'm doing).* After that, I moved into the actual design and starting stage where I coded my actual MVP using html and animate.css, and tested it using the online HTML compiler/tester. At this point, I have a working version of my page, maybe I could polish it a bit but I don't think it needs it right now.
  
- The next stage of the <b>engineering design process</b> for me would be like testing and improving my website based on feedback and what I personally think should be added if needed. This includes fixing issues on like how the cards are supposed to be, adding features like *(possibly)* links or slightly improved image sizing, and possibly adjusting a little bit of the animations. I personally think i'm already near finishing my website and think i'm at a good spot now.



---
 
## Skills

Since working on this project, I got a few skills that I can use outside of this project or assignment. One skill I improved is problem-solving, because I had to fix layout issues like images not fitting correctly or sections shifting *(like the cards more of what i'm talking about)*. Another skill I developed is planning and organization, since I followed a timeline and wireframe to help me build my website step by step instead of getting lost while coding and forgetting what I was supposed to add or do.

I also improved slightly my html skills, especially understanding how like spacing, and styling work together to build a cleaner webpage than before. Over that too, I feel like I got a little better at learning by myself by using <b>animate.css</b> and testing my code in the online html compiler to quickly see and fix mistakes.

---

## Conclusion

Overall, this project helped me understand how the engineering design process works in real coding by planning, building, testing, and changing or even making my MVP better while also making or getting good skills like problem-solving, organization, and basic web development.


[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
