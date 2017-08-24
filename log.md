# 100 Days Of Code - Log

### Day 1: August 2, 2017, Wednesday

**Today's Progress**: I've recently begun completing the problems presented on [CodeWars.com](https://www.codewars.com) using JavaScript. It's been awesome for seeing optimal answers and discovering various built-in functionality I had no idea existed. I'm currently working on a problem that's asking me to take an array of strings and an integer **k** and return a concatenated string of the first longest consecutive string composed of the first **k** array elements. Tonight I was able to initialize the repo with a JS and an HTML file and fill in some preliminary functionality, but I still need to do some thinking on the logical innards. [Here's a link to the "kata" on CodeWars](https://www.codewars.com/kata/56a5d994ac971f1ac500003e/train/javascript).

**Thoughts** I have a general sense of what needs to be done to solve this problem, I'm just trying to come up with the best way to go about it. I'm starting a week-long temporary gig tomorrow along with two job interviews for full-time day jobs, and I got interrupted by the waking of my infant son, so I'll have to return to this tomorrow when I've gotten a little sleep and have a little more downtime. I'll keep it on the back burner. I think I can solve it tomorrow, perhaps with a little googling to chase down the answer.

**Link(s) to work**
1. [Longest Consecutive Strings](https://github.com/jaredcaraway/longest-consecutive-strings/commit/402cbb9bdae3d66326c4214d508f6bb69a8362bc)

### Day 2: August 3, 2017, Thursday

**Today's Progress**: I continued chipping away at yesterday's [CodeWars.com](https://www.codewars.com) kata. When I left off yesterday, I had only coded stubs and a conditional statement to valid the argument k, which is the number of consecutive arrays I should be checking the combined length of. I commented every line along the way to make sure I understand what I'm doing, and with the help of the browser console, I ironed out all syntax errors and got the script to run. I see output, but unfortunately it is not correct at this point. That said, I have definitely made progress. Let's see if I can wrap this one up tomorrow.

**Thoughts** The challenge for this problem is keeping track of where the longest consecutive string in the inputted array begins. Since I am looping through and checking the length at each index of the combined k-length string (this problem is difficult to put into words, and I feel like I'm still not adequately explaining it, though I do understand what I'm trying to accomplish), I decided to set up a "max" object which contains both the index and the concatenated string at that length. Since I'm only supposed to return the first longest string, if I compare the current max with each new one moving forward in the loop, I should be able to return the max.str at the end of the loop. I'll debug tomorrow. It was hard to make myself complete the challenge today; I started a temporary position in the morning, had two interviews this afternoon, took a fairly long nap in the evening, and did a bit of preparation for another phone interview I've got scheduled for tomorrow morning. But I'll do my best to keep the streak going.

**Link(s) to work**
1. [Longest Consecutive Strings](https://github.com/jaredcaraway/longest-consecutive-strings/commit/f40c90fe383dc443cb980014e0b05c531be937b9)

### Day 3: August 4, 2017, Friday

**Today's Progress**: Still stuck on yesterday's kata. I struggled with debugging my logic, so I opted to scrap the innards of the function and start again. Rather than jumping right back in with recoding, I started out by taking my best shot at walking through the problem with pseudo code. The function still does not operate as it needs to, but has some necessary validation written in.

**Thoughts** This one still escapes me from some reason, and I must admit that it's a bit frustrating. But that's going to make it so much sweeter when I finally figured out where my logic falls short. I am determined to move onto the next problem, but I have two job interviews tomorrow morning and need to get to sleep for now. Hopefully I can still make time tomorrow to rethink my approach.

**Link(s) to work**
1. [Longest Consecutive Strings](https://github.com/jaredcaraway/longest-consecutive-strings/commit/736a41bbe78bf329e0e938368ecfb148955de6c4)

### Day 4: August 5, 2017, Saturday

**Today's Progress**: Starting over paid off! Thinking through the problem anew and stepping through it in pseudo code really helped. It would probably be beneficial to try that approach more regularly, if my impatience will allow me to do so. I solved the kata I've been stuck on for several days. I submitted my response on CodeWars and I'm pleased to say it passed. I reviewed several of the more optimal and clever solutions and picked up a few tips I hadn't considered. I love that feature of CodeWars!

**Thoughts** Very relieved to finally have this one done and behind me, and excited to get started on the next one. I've already made a directory and copied the files from the previous project into it - now I just need to initialize a new repo and customize the templates and get to work. I think I'll solve the next kata much more quickly after a cursory review of it tonight.

**Link(s) to work**
1. [Longest Consecutive Strings](https://github.com/jaredcaraway/longest-consecutive-strings/blob/master/longestConsecutiveStrings.js)


### Day 5: August 7, 2017, Monday

**Today's Progress**: I'm editing today's log in vim (rather than Atom or gedit, which I've been using previously), which is a whole learning process in and of itself. But I do see the potential power of this editor, once I become acquainted with it. It's pretty foreign initially, but I'll stick with it. I spent a lot of time today reading up on Python and typing in some practice code. I am learning how to use Pygame with the goal of completing my first game. It's a pretty basic concept that's been done many times before, but I think it'll be a good learning project. Basically, you control a character that you move around the screen and dodge objects flying at you from every direction with increasing speed and size until you die. I've had limited experience with Python, but it's been a while, and I've never used Pygame...so it's a bit of a slow process up front. Also, it's technically Monday as of my writing this, but it's just after midnight, so I'm still going to count this as a streak! Once I'm up to speed, I'll probably start working on the game for some of my upcoming entries and will thus be switching from JavaScript to Python for a little while.

Back on the Codewars front ([Join my team here! I just got my first teammate today!](https://www.codewars.com/r/O-OiLw)) with another kata, I started and solved a much more simple problem than the one I was working on in my previous few logs. I closed the Codewars tab and, for some reason, I wasn't able to pull the challenge back up...but I have a new script to show for it all the same, even if I can't get points for it on the website. My latest script takes an input string and returns either the middle character (if the string is an odd length) or the middle two characters (if the length is even). It didn't take me long to figure out how to accomplish this one, a fact more attributable to the ease of the problem than an advance in my coding skills (which is not to say I'm not making progress, because I definitely am!). I even figured out a way to return the solution in a single line of code using a ternary expression for a more "optimized" answer, but opted to flesh it out for the sake of readability and understandability, which I believe are more important than some extremely marginal (if any) performance improvement. All things considered, I'd say today was pretty productive.

**Thoughts** I'm quite pleased with my progess today, and while I'm still struggling through it, I'm slowly starting to get the hang of vim. I can see myself using this more regularly in the future, though I'll still probably incorporate Atom into my workflow. I hope to finish up my background self-education with Pygame in the next couple days and start uploading my work on my first game soon.

**Link(s) to work**
1. [Middle Character](https://github.com/jaredcaraway/middle-char/blob/master/middleChar.js)

### Day 6: August 8, 2017, Tuesday

**Today's Progress**: I started a new JavaScript project today. The goal is to take an integer and output it in expanded form (so if 10524 is inputted, you would expect "10000 + 500 + 20 + 4"). I thought I'd gotten it to work, but when I submitted my code through Codewars, I found that it fails on certain edge cases and tacks on an extra plus sign at the end of certain integers. I will have to sleep on it and revisit tomorrow.

**Thoughts** I am pleased at the speed with which I produced my pseudo code, but I'm currently frustrated with the edge cases issue. I thought I had it figured out! To be fair, though, I haven't put much bandwidth into debugging it. I'm glad I got it to run as well as it's running currently, at least.

I used vim for most of today's programming, but I honestly got a little frustrated at how frequently I had to switch to my browser to Google certain functionality. I'll still chip away at it, but it's slowing me down significantly. If I don't get the hang of it soon, I may switch to something else, such as gEdit. I don't think I need something as heavy as Atom for the complexity of what I'm working on, and I don't have the most powerful machine, so lightweight is better.

In the near future, I hope to figure out how to get my projects to run with the output properly displaying on Github pages rather than outputting to console.log, which is not acceptable for production code. While setting up Github Pages, I found instructions for installing a Ruby-powered, static-page blog platform called Jekyll. I'm going to experiment with it and see if it'll be worth switching over from my current Wordpress.com setup.

**Link(s) to work**
1. [Expanded Form](https://github.com/jaredcaraway/expanded-form/blob/master/expandedForm.js)

### Day 7: August 9, 2017, Wednesday

**Today's Progress**: I finished the Codewars kata I started yesterday...and man, this one was a battle. I started over numerous times in search of the winning solution. There's definitely nothing elegant about my code, and it's far from optimized, but it works (having passed over 100 case tests).

**Thoughts** I really struggled through this one and Googled extensively to get it running (though I was Googling mainly for Mozilla Developer Network entries for various JavaScript functions, not for tips on how to solve the specific problem). There were a lot of first uses for me in this solution, including my first usage of objects as well as first implementations of the built-in split, forEach, and repeat functions. It didn't seem *terribly* challenging at the outset, but as I got deeper and deeper into coding it, I started to realize the complexity. I'm hardly ready to be hired on as a junior developer, but I feel like I nonetheless grew as a coder in the process of nailing this one down. I'm hoping to revisit it one day with an eye for refactoring. [Here's a link to the problem](https://www.codewars.com/kata/write-number-in-expanded-form/train/javascript) in case you're interested in attempting it for yourself.

On a side note, I stuck entirely to gEdit while working out this solution. It's a lot more user-friendly than vim. I do like vim, but I wanted to make more progress on the problem rather than getting bogged down with the learning process for an unfamiliar editor. gEdit is more than adequate for my purposes right now.

**Link(s) to work**
1. [Expanded Form](https://github.com/jaredcaraway/expanded-form/blob/master/expandedForm.js)

### Day 8: August 10, 2017, Thursday

**Today's Progress**: Took a break from JavaScript today to get started on my first Python game (using the Pygame library), called Chicken vs. Egg! (exclamation point included). I spent a good deal of time reading up on the documentation and other people's examples to understand how to proceed. I'm starting off slowly; so far I've gotten the program to display a small window with a black background along with a chicken and two sizes of an egg. I drew all the graphics myself using Gimp. They're not cutting edge, but they could be much worse! My goal right now is to get a working draft out, not get hung up on perfecting the details. I will improve incrementally. I also incorporated git branching into my development process today for maybe the second time ever. As my programs increase in complexity, I intend to make more regular use of this feature so I can try out different things without messing up the master branch. Finally, I figured out how to compare my last commit and currently staged files via git diff. Productive and positive day of coding.

**Thoughts** I am pretty damn proud of today's progress. I have quite a bit of work ahead of me, but I am looking forward to achieving my childhood dream of making a video game for the very first time. It's been decades in the making now. It's a pretty awesome feeling to see my rudimentary graphics displayed onscreen. I can't wait to see them moving around. My code right now is a little bit disorganized, but I will clean it up as I go. I'm in the "trying to figure this out" phase right now, so elegance is not a priority at the moment!

**Link(s) to work**
1. [Chicken vs. Egg!](https://github.com/jaredcaraway/chicken-vs-egg)

### Day 9: August 11, 2017, Friday

**Today's Progress**: Today I was all over the place, but did not accomplish much on one specific project. I have several different branches open now on Chicken vs. Egg to implement various features. My major project is to refactor the code to make it follow a more logical object-oriented approach...but I'm currently a little disoriented. I'm tired; I'll come back to it tomorrow.

Earlier today, I started playing around with Django for the first time. I'll admit it, I'm initially intimidated by it, but I know that if I don't give up I'll get the hang of it at some point. In the process of connecting to the server on which I'm running Django, I also learned how to SSH into the server via Terminal. Again, I'll revisit once I get some sleep.

Finally, I started setting up my Github Pages and revisited a previous script to start the process of offering a decent interface that users can use to enter their own values (versus sticking exclusively to the examples coded into the script.

**Thoughts** I lost my focus today and started pulling myself in different directions, but I was still participating in the 100 days project all the same. I have no examples to show today beccause I didn't push anything to Github from my local machine. I left my code in a less than ideal state, so I didn't want to push it until I've had a change to go back over everying with fresh eyes. Tomorrow, I'd like to make some more meaningful progress on my game. I'm still working through the 100 days challenge, example or not. Did I mention I'm tired? I'm going to bed! I'll be back tomorrow with more updates.

**Link(s) to work**
1. N/A

### Day 10: August 12, 2017, Saturday

**Today's Progress**: Man, I was actually falling asleep when I typed out yesterday's log. I made more progress today after a good night's sleep.

For today's coding, I set up a new Python project with the simple goal of getting acquainted with classes and objects, which I'll ultimately need to incorporate in Chicken vs. Egg! This program is a command line-based script which prompts you for a dog breed and name, instantiates a new Dog object based on the provided arguments, and appends them to a list. After inputting the first dog's info, you are given the ability to view the current list of dogs, add another dog, or quit. This loop continues until you select the "quit" option, as you might have guessed. I specifically was struggling with the idea of how to create numerous instances of a class without having to specifically provide a variable name to store the objects in. Now I know how to do it via a list. This is how I plan on storing the multiple instances of Egg objects (and, if I ever get to that point, multiple Chicken objects for two-player support). It's definitely [Shitty First Code](http://peelingoffthebark.wordpress.com/2017/07/28/shitty-first-code/), but I am still fairly new to Python and am glad to have just gotten it working.

I strayed from my git discipline on this one, because I wasn't sure if this one would be worth tracking via a repo. But I kept chipping away at it, and while I don't think there are many people out there who would benefit from using this program, I figured at least I could put it up for evaluation by similarly situated beginners. I don't mean to imply that anything in my code is representative of best practices or elegance, but it's valuable to examine the output of others to analyze how they go about tackling a problem. Maybe somebody can look at what I did wrong, even, and learn not to take that particular approach.

**Thoughts** I feel accomplished, for sure. This is the most involved Python script I've written to date, and I feel like I learned a decent amount in the process. It's not the most useful script, but I feel good to have produced something functional, and my object-oriented skills are definitely improving. I've read quite a few criticisms of the OOP approach to programming, but I think it'll suit my purposes well enough. I ultimately want to have a solid mastery of procedural, functional, and object-oriented programming. I think they each have their strong suits and appropriate applications. But I'm also still a pretty young programmer, so perhaps I'll become more opinionated as my skills and experience continue to develop.

**Link(s) to work**
1. [Dogs](https://github.com/jaredcaraway/dogs)

### Day 11: August 13, 2017, Sunday

**Today's Progress**: I returned to Chicken vs. Egg! for today's coding. When I left off, I'd figured out how to display a window for displaying graphics onscreen, and I displayed static sprites of a chicken and an egg (in two sizes). At that point, there was no user input to control any of the sprites.

I made a branch in my git repository with the aim of getting the chicken to switch directions in response to the left/right arrow keys being pressed. I quickly got that working via pygame.transform.flip, so I continued on to implement actual movement (just left and right to start). This took a couple of passes, but it still ultimately didn't require too much of a time investment before I figured it out (thanks largely to the fact that I was able to Google code to model mine own after).

When I first got the chicken to move, I had it set to only move a pixel at a time in either direction, and it would not move continously as long as the key was pressed down (which was the behavior I was after). I experimented with a few different movement increments until I felt it was reasonable, and then I looked up another method to read keypresses which allow for continuous movement. Then I ran into a problem with detecting the edge of the screen - simple enough, just check if the sprite has moved beyond 0 or screenWidth-chickenWidth (since the coordinates are measured from the top left of the sprite, I needed to account for the width of the chicken on the right side). If the chicken has gone out of bounds, just move it back in with a conditional statement and an additional line of code.

Next, I ran into the problem of a fucking HYPER SPEED chicken that moved from one side of the screen to the other in a fraction of a second - so fast that it looked like it was teleporting. To solve this, I figured out I needed to create a Clock object and call clock.tick(30) at the end of each pass through the game loop to get the visual output down to a much more visible 30 frames per second.

So objective complete. Next up, I'll add the ability to move the chicken up and down. I also need to add a background at some point and, of course, add in the eggs. All in due time.

**Thoughts** Another day of pleasing results. I feel like the chicken's controls are off to a great start; the real challenges lie ahead, but I'm proud of my progress.

**Link(s) to work**
1. [Chicken vs. Egg!](https://github.com/jaredcaraway/chicken-vs-egg)

### Day 12: August 14, 2017, Monday

**Today's Progress**: Bit of a frustrating day working on Chicken vs. Egg!, but I did make a bit of progress. I figured out how to display text in the window and popped in a dummy bit of "Score" text that, for now, will always read zero until I start writing the scoring logic (which is admittedly still a ways off). I also added logic to exit the program when the Q or escape keys are pressed, so I no longer have to click the X in the window to close it.

![Chicken moving around with score displayed onscreen](https://github.com/jaredcaraway/chicken-vs-egg/blob/master/screenshots/chicken-movement-demo-2.gif)

The frustration came in when I tried to get rudimentary collision detection working. I set up a branch for this. As it stands right now, my chicken is basically a ghost on the screen that does not know where its edges are and is unable to know when it has run into something else. After a little research, I figured out I needed to make a Rect object in Pygame that matches up with the image. However, my attempts at getting it to work were futile up front. I broke the program and couldn't get it running again, and I committed it in its broken state before switching back to the master branch. When I got back to the master, I found that I had forgotten to merge the changes I'd made (described above) while the program was still working - so I did one of my first hard resets to roll the program back to the commit I made right before I broke it. (And thus I'm really beginning to see the value in regular commits.)

**Thoughts** It's becoming increasingly clear to me that I need to approach this in an object-oriented manner sooner rather than later, because my code is going to quickly get out of hand otherwise. Before I reset to my previous commit, the code was already starting to get pretty ugly! I will say, though, that my frustration should not be mistaken as discouragement. I'm actually determined to get some sleep and take another stab at this problem tomorrow. I may go ahead and start refactoring in OOP mode.

**Link(s) to work**
1. [Chicken vs. Egg!](https://github.com/jaredcaraway/chicken-vs-egg)

### Day 13: August 15, 2017, Tuesday

**Today's Progress**: For a slight change of pace today, I returned to a series of problems I first encountered *years*, ago, maybe a decade or more back. It's a puzzle website of sorts called [Python Challenge](http://www.pythonchallenge.com/). It's a clever website, even though it looks like it was designed sometime in the late 90s. Essentially, you have to write a Python script to solve a problem for each page in order to obtain the URL which will lead you to the next puzzle page. You often have to view the page source to find the information you need to progress - for example, one page included about a thousand lines of non-alphanumeric characters with alpha characters mixed in, all commented out in the source of the page. To find the URL for the next page, I had to figure out a way to filter out all the noise to find what were basically needles in the haystack.

What I like about this website is that it forces me to seek out functions of Python I wouldn't normally use, some of them fairly advanced. I just finished puzzle number 5, which introduced me to a serialization/deserialization process called pickling (wtf?), and the previous puzzle required me to use the urllib2 library to loop through a couple hundred pages, opening each following one programmatically to find the number to tack into a query on the URL to lead me to the next one. After almost 300 passes, the loop crashed. I plugged the last number into the query string tacked onto the base page URL, and the page then told me where I needed to direct my browser to carry on. If I'd clicked through manually, this probably would have taken me 10-15 minutes, but Python handled this problem in probably 30-45 seconds. Very cool.

**Thoughts** Python Challenge is further familiarizing me with Python, which is still relatively foreign to me in comparison with JavaScript (which I definitely am nowhere near mastering). I think I needed this detour; it'll help make me a little more comfortable when I return to Chicken vs. Egg! Among several other things I learned tonight was regular expression syntax and how to implement it in Python. It took me probably an hour minimum to really understand what I was doing, and even now there's still a lot I don't quite understand. But that'll come with practice. I'm anxious to try out regex in JavaScript, once I focus back on programming in that language. I wasn't intending on making a git repo for my Python Challenge scripts, but I went ahead and made one so you can look through to get a sense of what is involved in solving the puzzles. They really make me think (and Google furiously).

**Link(s) to work**
1. [Python Challenge solutions](https://github.com/jaredcaraway/python-challenge)

### Day 14: August 16, 2017, Wednesday

**Today's Progress**: I didn't make as much notable progress today as I have in previous days, mainly because I got so caught up on a particular level of the Python Challenge. I ultimately ended up completing it, mostly, but had to defer to looking up the answer after all my attempts kept failing. :-/

I'm referring to [level 7](http://www.pythonchallenge.com/pc/def/oxygen.html). For this one, you're presented with a PNG image which looks quite odd - it's a photo of a riverbank, but across the middle of the image is a series of grayscale chunks ranging from gray to black in seemingly random order. I figured it was some kind of message encoded in the image, so I spent a lot of time researching the appropriate library (or libraries) to use, as I'd never dealt with programmatically processing and manipulating raw image data.

I kept coming back to StackOverflow advice for this one. I made it almost all the way to the answer based solely on my own research (read: googling), but got caught up on the last stage of the problem. Basically, the RGB values for each successive block correspond to an ASCII character; you read in the values from the blocks, then convert them to characters to get the message. The catch is that the decoded message itself contains an additional message to decoded, and I made some sort of error in parsing the encoded image blocks which resulted in slightly incorrect output of the code within the code.

When I tried to translate these numbers, I got a mix of expected, readable characters and nonprintable characters, such as shift out, control, and feed forward. The error appears to be that for these erroneous characters, the hundreds digit got removed (returning 16 rather than 116, for example). In frustration, I went ahead and threw in the towel to find the answer and try to figure out what I did wrong. I have as yet not quite figured it out, but I did indeed make progress today, so I'm not too disappointed.

**Thoughts** I love how creative Python Challenge is, and it forces me to think outside the box (rather than solving more run-of-the-mill problems). Today I learned some basic image processing via script, and I also learned how to process zip files via programming as well (and a large number of them, at that). Python is not a panacea, and I imagine I'll need to dig into one or more other lower-level, non-interpreted languages as I progress in my development career. That said, I respect how powerful it is and how relatively easy it is to import a library and get things done with this particular language. I'd like to return to working on my game soon, though. Proud to have made it two weeks strong into the 100 Days of Code, in any event!

**Link(s) to work**
1. [Python Challenge solutions](https://github.com/jaredcaraway/python-challenge)

### Day 15: August 18, 2017, Friday

**Today's Progress**: So far, I'd figured out that it was possible to view difference between your current and previous commits. But I wondered - was it possible to see a difference between branches, or over time? As it turns out, yes! I haven't figured it out on git proper yet, but on Github, you just append "/compare" to the end of your project repo's URL and it pulls up a neat page allowing you to compare between the master branch and additional branches. There's also an option to compare different version tags, but I haven't gotten to the point of including version tags in my programs yet, so that's yet to be explored by me.

Today I returned, after a brief intermission, to Chicken vs. Egg! I'd honestly been avoiding it out of a slight fear of refactoring some of the code OOP style, but I knew it was unavoidable, so I figured today was as good as any. Rather than refactoring it all at once, I decided to start by branching my current working code to work on object orienting the chicken.

In order to make use of Pygame's built in Sprite class, I made my new Chicken class a sprite derivative - this was my first encounter with inheritance in Python, and it's pretty straightforward. The trickiest part was probably calling the parent class constructor; a tutorial I found made use of the super() function, but it appears to be a function of Python 3 (whereas I'm on Python 2.7). Otherwise, not as difficult as I'd expected.

I'll probably come back to the OOP refactoring tomorrow, but I deviated from that aspect of the project to add vertical movement for the chicken. This wasn't difficult at all; it was actually much easier than the horizontal movement (which wasn't particularly difficult to begin with). The main difference is that, since the chicken maintains the direction it's facing when moving vertically, I don't have to flip the sprite if it changes direction.

![Chicken moving around in ALL directions with score displayed onscreen](https://github.com/jaredcaraway/chicken-vs-egg/blob/master/screenshots/chicken-movement-demo-3.gif)

I ran into a brief issue when I moved the keypress detection code into the Chicken instance method. For some reason, it wasn't reading 'q' or Esc keypresses to exit when I tried to detect them within the move() function, but I got it to work again by moving the conditional statement back to the main game loop after the move() instance method call.

**Thoughts** Another day of marked progress. I feel more certain than ever that I'm going to achieve my goal of making my very first game at the tender age of 30 (something I've been dreaming of for decades now). I'm at a significant advantage having Pygame to rely on, and using Python itself is making it much easier than my previous attempts in C++ (though I'm interested in revisiting the language; I doubt I'll ever seriously get into it, but I also have a morbid interest in assembly language programming, too).

As a side note, I think I might incorporate version numbers into my project going forward to give a sense of my progress; I'm researching how best to do this. I believe I'm ready to call it v0.1; I'll bump it to 1.0 when I've implemented the bare minimum number of features to call it a playable game.

**Link(s) to work**
1. [Chicken vs. Egg!](https://github.com/jaredcaraway/chicken-vs-egg)

### Day 16: August 19, 2017, Saturday

**Today's Progress**: Today I ran my Chicken vs. Egg! project through Codacy, an online service that reviews and highlight any errors or inconsistencies in your code, and ultimately passed with 100%. I felt pretty good about that for one of my first "serious" programs. I think I'll start making it part of my development habit.

I did finish refactoring the Egg class today. Next, I think I'm going to add rectangles to the sprites to enable collision detection. I also moved onto level 9 of Python Challenge after getting caught up on one problem - I have to admit, I ended up getting so frustrated that I went online looking for tips or hints, but ended up finding the solution. I was on the right track, but my attempt at a solution was WAY more time intensive.

**Thoughts** I'm still learning every day. I look forward to finally putting the interactive touches on my game that make it feel like a "real" game. Short log today because I'm extremely tired and want to sleep. See y'all tomoorrow!

**Link(s) to work**
1. [Chicken vs. Egg!](https://github.com/jaredcaraway/chicken-vs-egg)

### Day 17: August 20, 2017, Sunday

**Today's Progress**: I hit a pretty major milestone today, though it might not look like much onscreen. I got collision detection working in Chicken vs. Egg! I felt that this warranted a bump up to v0.2. This involved adding Pygame rects (for rectangles) into my chicken and egg classes to act essentially as bounding boxes, invisible barriers representing the edges of the objects. I'd previously been using x and y attributes belonging directly to the respective classes, but now that information belongs to the Rect objects (which adds a number of other benefits, such as attributes for the various parts of the rectangles like top center, bottom right, and so on). I also added in sprite groups, creating lists for eggs, chickens (should I ultimately add multiplayer, which I intend to at least try), and one for all sprites - egg and chicken alike. I wrote a simple test that determines when the one chicken intersects with the one stationary egg onscreen, displaying a message in red at the bottom of the game window when they are colliding.

![Chicken moving around in ALL directions displaying a message when collision is detected](https://github.com/jaredcaraway/chicken-vs-egg/blob/master/screenshots/chicken-movement-demo-4.gif)

This latest development arrived with minimal resistance and debugging, which I'm pretty pleased with. Now I need to figure out where I'll go next with the game - I think I'll get the egg to move and make sure collision detection still works in that state, then figure out how to "kill" the egg object when it moves off the edge of the screen. Naturally, I'll keep you posted.

**Thoughts** Today's progress was very exciting and encouraging. Getting the sprites to recognize that they're making contact with one another is a major step forward for me; I don't want to be overly optimistic, but with the daily progress I've been making, I think I could have a playable game within a month, estimating conservatively, and a couple weeks, at best. But I'll still be adding features even once it is a "legit" game; I want to do the best possible job on this game, simple though it may be. I'd ultimately love to work in a rudimentary wing-flapping animation for the chicken and make the eggs rotate as they fly across the screen, but that's all secondary to the base gameplay!

**Link(s) to work**
1. [Chicken vs. Egg!](https://github.com/jaredcaraway/chicken-vs-egg)

### Day 18: August 21, 2017, Monday

**Today's Progress**: I was missing JavaScript, so I revisited one of my earlier scripts to improve its functionality.

When I pushed the repo to Github, it was strictly a script with no accompanying webpage to display the results or accept any user input. I later created a page in my local repo, but even that only gave the output of the numbers I hard-coded into it. I wanted to add interactivity, and I also wanted to acquaint myself with Github Pages, so this was a nice way to do both.

In the script, I find the ordered list with id "output" and save that DOM object to a variable outside the function itself, thus placing it in the global scope. This made it easy for me to adapt the script to accept input - I simply added a second ordered list with id "user-output", added a form, and added a submit action that found the new ordered list and updated the global list variable with this object. From there, it was just a matter of running the function. And it works like a charm, though I plan to revisit this project yet again to put some polish on the design (it's pretty shabby at present).

**Thoughts** I feel good about today's progress - I'm back in JavaScript and already a bit rusty after a couple days away from it and in the Python state of mind. But it was great to get the experience with form submission, even though I wasn't sending the input to a database or anything on the back end for processing. In a future iteration, I may add a cookie so the data persists between visits (I've never worked with cookies), and I'll also add a "reset results" button to clear the cookie data out. I don't think this project is really complex enough to warrant sending the info to a database, but I do want to get some db practice soon.

**Link(s) to work**
1. [isPrime on Github Pages](https://jaredcaraway.github.io/isPrime/)
2. [...and the source for it](https://github.com/jaredcaraway/isPrime)

### Day 19: August 22, 2017, Tuesday

**Today's Progress**: I branched off in a couple different directions today. This will be a LONG log entry.

I returned to the Python Challenge website to try to tackle [the current problem I'm stuck on](http://www.pythonchallenge.com/pc/return/bull.html), which I've been doing for short periods of time over the last several days; I keep it open in a tab and keep switching back to it to see if I can gain any insight. You're given the first several items in an array and basically told that the solution is index 30 at that array, when extended out. It looks at first glance like a basic pattern recognition problem, but a second look seems to reveal that it's a series of ternary (rather than binary) numbers.

That led me to throw together a very basic ternary to decimal script. I could have looked one up online fairly quickly, but I preferred to solve the problem and further hone my skills.  (I may upload the repo in the future, but as for right now it's programmed specifically for the challenge.) I still haven't solved the problem, but that's because I keep getting distracted by other things.

I started experimenting with Requests and BeautifulSoup. I'm using XKCD as a guinea pig, since they have a very simple URL structure (and I started reading the comics from the first one when I visited their site today). While I could just view the comics in the site and manually click through to the next one, I thought it would be an interesting project to Pythonically find the image source and display it in a window on my machine. Ultimately, the goal is to have an XKCD viewer where I can move back and forth to the previous/next entries via arrow keypresses. Once I get that working, I'll figure out how to display the caption text for each comic that appears when you mouseover it. (For now, I'm not quite ready to share the source on this one, either.)

I made more progress on Chicken vs. Egg! today, and I feel myself getting closer to a playable game. First, I wanted to simply make the egg move laterally across the screen, then remove it once it disappeared off the edge. Then I easily figured out how to make it wrap (Pac-Man style) and reappear on the opposite side, looping forever (or until I pressed one of the exit keys). This prompted me to modify the egg class constructor - the initial version took a tuple position argument for me to specify where on the screen to draw the egg upon instantiation. I remove the coordinates parameter, started the egg at the far left side of the screen, and added code to randomly generate its vertical position. I then modified the code to "kill" the egg object once it went offscreen, but subsequently instantiate a new egg as soon as the previous one disappeared.

After I got that working, I realized that the 400 by 400 pixel field I've been working with was far too small - so I made it fullscreen. In a future implementation, I think I'll add the option to toggle fullscreen (which won't be difficult). It feels SO good to be making progress!

![Fullscreen mode with egg moving sideways across screen with a new egg appearing at a random height on the opposite side with each pass.](https://github.com/jaredcaraway/chicken-vs-egg/blob/master/screenshots/chicken-movement-demo-5.gif)

On a side note, I intend to compete in the Pyweek game challenge, where I'll have to come up with a game in a week's time based on a theme that's revealed a week before the competition. I don't know if I yet have the knowledge and experience to pull it off, but I'd like to at least try and learn in the process. Even if I don't win, or finish for that matter, I could at least come up with the seed of a project I continue working on once the competition ends.

**Thoughts** Great progress today, for sure. I'll return to the XKCD viewer tomorrow; I bet I can get it working with enough Googling. I'll also do some research into how to make my eggs move in directions other than horizontal. From there, I'll need to start them off on varying sides of the screen, heading in different directions at different angles. Then increasing difficulty, a basic main menu, and other polish like a background, sprite animations, and a few other small details.

Tomorrow marks the 20% mark of my 100 Days of Code participation. It really is becoming a standard part of my day, and I'm finding myself seeking out information about libraries and other programming-related stuff daily. I haven't made any big, complex programs or apps yet, but I can comfortably say that I'm a developer/programmer/coder/whatever, if only on a basic level. I love doing this stuff, and I hope to have a job in the industry by this time next year.

**Link(s) to work**
1. [Chicken vs. Egg!](https://github.com/jaredcaraway/chicken-vs-egg)

### Day 20: August 23, 2017, Wednesday

**Today's Progress**: For a change of pace today, I started exploring the CSS3 flexbox model via a nifty little gamified tutorial I first heard about on the Talk Python To Me podcast. If you want to check it out, it's called Flexbox Zombies. The zombie meme was stale a long time ago, but this is a surprisingly fun way to learn the technique - and the animation is beautiful.

I revisited my prime-number-checking webpage to test out the flexbox functionality on a small scale. I've also prettied it up a little more, and overall I'm pretty happy with how it looks at this point (though I'm sure I'll continue to find small tweaks I'd like to make to it over time; it's hard to put my stamp on it and say "no more").

I made a branch of Chicken vs. Egg! to test out egg rotation, which I thought would be easy...WRONG! Python has a built-in rotation function, but it doesn't perform as expected. Rotating the sprite changes the dimensions, which in turn changes the bounding rectangle dimensions and provides a new center. The key is to rotate around the center, and the center changes with each rotation. I've still got some thinking to do on this one. It's not an absolutely necessary feature, but it would be cool to implement.

I started learning about linear algebra today; I'll ultimately need to know it if I want to move into 3D graphics.

**Thoughts** No major breakthroughs today, but progress was made all the same. I look forward to continuing my streak tomorrow!

**Link(s) to work**
1. [isPrime on Github Pages](https://jaredcaraway.github.io/isPrime/)
2. [...and the source for it](https://github.com/jaredcaraway/isPrime)