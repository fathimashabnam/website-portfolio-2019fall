Surprisingly, I did not have too many different ideas for this project at the brainstorming phase. 
This is because I have been wanting to to make an engineering blog of sorts for a while now to add to my 
website, but I just haven’t gotten around to doing this. This project gave me the perfect opportunity to do this, but
I wanted to add a personal challenge to it and code it from scratch (without using a template). This was a challenge to me, as I had
used a template from HTML 5-UP when I built my website, and while that yielded a satisfactory layout, I felt like I did not
understand underlying structures and code. My beginner level HTML training from my freshman engr class had given me enough 
leverage to do whatever was needed to get my website running, but my coding etiquette for my website was abysmal (in class, we made
our webpage using tables…so I’ve come a long way). By challenging myself to code these webpages from scratch, this allowed
me to understand good coding practice, and learn css style sheets (which I knew nothing of before).   

My main image for my website sprung from this comic I came across before. Thank you Dr. Miller for helping me identify 
the source: https://xkcd.com/1106/. 
I wanted to show this frustration (as this is what I felt too often in my freshman year of engineering) on my main page
. Upon further thought, I decided engineering was like walking a tightrope above crocodiles with weights weighing you 
down—so that’s what I set out to make using GIMP. 

I made the background image, and then each of the weights as separate images. This was done after a lot of thought on how to
make the image interactive without needing to learn Javascript (or any other type of difficult code). My solution to this
problem was to center the image on the page and not make it responsive, and then place the balloons/weights on the image 
and make these responsive. The easy part was making the images. 

<img src="docs/websitephoto.png" alt="Website main image- crocodile" width="250"/> <img src="docs/pinkballoon.png" alt="Website main image- weights" width="90"/>

The difficult part was placing all my images on the page and having them stay exactly where I wanted relative to the main 
image. After a lot of trial and error (and googling), I placed them in a relative div and called the class “centering”. 
Inside this, the main image is absolute with the weights/balloons relative (located with pixels on the main image). 
This yielded a satisfactory result in a Firefox browser at full width, but when I moved the browser or see it as a mobile
screen, the image gets cropped in view, so I added a media query to readjust the image. However, this part needs to be 
tweaked further for my final project. 



Once the main image was finally done, the next steps involved adding multiple connected pages with content in them. I was 
able to add content relatively easily, but I soon realized my bad coding practices came back to hurt me. I started adding 
stylistic elements with <font> tags and size changes in the html page. When trying to recode and clean up my code, I couldn’t
figure out why my font color wasn’t changing… until I realized I had also used a strong tag in my html page that superseded
the css command. An example of me cleaning my code below: 

XX 

In terms of visual aesthetic, I knew I wanted it to be fun, cheery, and sarcastic. I used a variety of bright colors and
used a carefully crafted visual for my main page. At first glance, the person is just holding a rod with lines, and when
the user scrolls, the balloons and crocodiles are visible together due to the vicinity of the two. I used the “scroll” 
available on a website to add that surprise factor. Another area I used a lot of color was in the grades html page. I also
used a collapsible button here. The main reason for this is the amount of text. I knew in order to keep the reader’s attention,
I would have to separate the information and make it attractive. I also wanted to bulletpoint my points but add detail so the 
collapsible button was the best option available. For this (and the menu bar), I ended up using javascript tutorials despite 
my initial reluctance to do so. I ended up sacrificing a little of my “I will code everything from scratch” goal to attain 
visual satisfaction. 

I also added various details to the code to make it minimalistic in design and clean. I added the padding that was suggested 
to the body of my pages, and kept everything centered. I also kept the header the exact same in every page, and added a footer
to the index page. I felt like this linked the different pages together well (and reminded the user where they were—a subpage
of my website).   

One small detail I am proud of is my alignment and color of the words “Don’t be a fool” in my “Why should you listen to me?” 
page.  I think the right alignment and color change successfully adds surprising humor (this is repeated in the grades page). 
Best part of it all, I used the same class tag in both pages! 

Unfortunately, my website is not yet complete. I need to add content to my “Clubs and Organizations” page. I shall have this 
completed for my final portfolio. 

My peer feedback was extremely encouraging as they seemed to enjoy the “simple layout” and “playful colors”. Ellie suggested 
that I may either keep the home icon or keep home in the menu tab as it seemed to repeat itself by being in both places. I 
considered this, but felt as if something were missing if I removed the home icon (the empty space bothered me) or if I removed
it from the menu (as all the other pages were listed). I decided not to incorporate this suggestion for the time being, but if 
I can think of something to put in place of the home icon, I will more than happily remove it (sugesstions are very welcome). 

Through this project, I have learned a lot. Flexboxes, media queries, nth-of-type, tags in css, divs and classes are just a 
few things I was introduced to with this project. This has, by far, been the most challenging of projects in this class, and
dare I say, most rewarding. My website is by no means fancy or professional, but I am pretty proud of it thus far. 
