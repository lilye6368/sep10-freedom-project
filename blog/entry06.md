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

I am currently in a stage where I am creating simple code and testing it for my <b>Engineering Design Process (EDP).</b> 

#### Enginnering Design Process Stage I (Current)

* This is my current stage for the EDP. I have been testing out some *Animate.CSS* code (aka the animations) and thinking where I should probably put it in my project. I can test different classes to see how they affect or change my text and trying to debug my code when the animations don't seem how I wanted them to be.

#### Enginnering Design Process Stage II (Next)

* My next stage for the EDP will be trying to plan to fix the basic animations that im currently stuck on and try to tune the timing just right so the transitions look a *bit* more professional before the final changes happen.

---
 
## Skills

Since my last entry, I have possibly developed <b>2 specific skills</b> for outside stuff too, not just this blog or work.

*<b>1) Problem Solving and Debugging:</b>* While trying to move past basic animations, I almost always run into confusion with the code. When this happens, I can stay patient and try figuring out different ways to solve it and potentially even debug it, one of the ways is either searching up some of the correct code, or either using different types of code yourself to see where the error occured and fix it quickly.

*<b>2) Visual "Communication" or Vibe</b>* By using Animate.css, I have improved very very slightly in using a little bit of motion to communicate or get the right vibe to a user on my website. You can learn how to choose the right animation, like a small fade vs a loud or really big bounce, just to make sure the vibe of the website matches the content. This skill of balancing design and function is pretty useful for any type of creative work, like websites or webpages. 

---

## Conclusion

Overall, learning how to use Animate.css has been a pretty big challenge since I am a beginner even though the code is basic, but it is cool to see the small amount of progress I made with the basic animations.


[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
