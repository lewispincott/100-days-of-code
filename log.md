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

### Day 21: August 24, 2017, Thursday

**Today's Progress**: Completed some more of the Flexbox Zombies tutorial today - it's fairly complex, but I love what I've learned about it thus far. I also tooled around a bit with browser SVG - I drew a simple circle, played around with the attributes, and experimented with modifying the attributes via JavaScript for some basic animation effects. I also looked up CSS3 animation, but stuck to checking out examples - I didn't do any experimenting. I didn't want to overload my brain, but I do plan on returning to it at some future point.

I added a background to Chicken vs. Egg! I'm not totally sure I'm satisfied with it, but it'll do for now. Now that I'm running the game fullscreen, the original sprite I made rather quickly is not sufficient, and since it's a bitmap image I won't be able to scale it up without distorting it to some degree. So I decide to go ahead and redesign the chicken. It's not the best, but I think it's at least a slight improvement.

I've been thinking through how best to get eggs to start coming in from random sides at random angles, and I should be able to implement it in the next few days if all goes well. I'm also going to eventually figure out how to animate the chicken via a sprite sheet, which should be much easier since I saved the GIMP project file and used a different layer for every single part of the chicken (except the wing, but that can be easily fixed). I'd intended to scale down the chicken, but I think for now I'll keep it bigger - so I scaled the egg up to match, and I increased the egg and chicken speeds.

![Screenshot of a larger chicken on a background photo of dry, cracked soil](https://github.com/jaredcaraway/chicken-vs-egg/blob/master/screenshots/chicken-vs-egg-screenshot-5.png)

Finally, I started working on the scoring mechanism. I figure once I get that up and running, it should only require a minimal amount of logic tweaking to make it work once the randomized egg functionality is working.

**Thoughts** I made more incremental progress today, and that's totally okay - it's still progresss. I am still moving forward and I'm happy about it. Seeing this simple game evolve step by step has been a strangely exciting process; every time I get something else working, it feels like a real accomplishment.

**Link(s) to work**
1. [Chicken vs. Egg!](https://github.com/jaredcaraway/chicken-vs-egg)

### Day 22: August 25, 2017, Friday

**Today's Progress**: Today I changed directions again and returned my focus to freeCodeCamp, where I left off a few months ago on the portfolio page project after half-assing it through the tribute page (mainly because I had a hard time coming up with someone to pay tribute to, and then because I settled on Abraham Lincoln and was more interested in moving on to the next lesson rather than researching a timeline of events in the life of Abe Lincoln, no offense to the guy).

I was stuck on the portfolio page because, while I've worked on a good number of WordPress sites, none of them were completely my work, and I felt like a phony calling myself a web developer/designer/whatever when almost all of my work was limited to trivial WordPress sites rather than hand-coded HTML. I also didn't enjoy working with Bootstrap, which is what freeCodeCamp promotes in its lessons.

But today I sucked it up and returned to the portfolio project, going through slowly while reading through the Bootstrap documentation to try to glean a more thorough understanding of the framework. It certainly is a powerful tool to have in my bag of tricks, so I think it's worthwhile to be familiar with - though I don't intend to rely entirely on it when I'm building sites. I was also hesitant to use something which relied on such unsemantic markup, but once I get the basics down, there are mixins I can use to make it more semantic. One step at a time.

**Thoughts** Bootstrap is thorough as hell, so I spent more time today reading than coding - but I still think I hit the bare minimum of an hour coding, anyway. I'm including a link to my current barebones/incomplete portfolio for reference as I shape it. It is just a skeleton at present, but it'll start taking shape in the next few days, I think. I feel good about Bootstrap thus far.

**Link(s) to work**
1. [freeCodeCamp portfolio project](https://codepen.io/jaredcaraway/pen/mMGrWZ)

### Day 23: August 26, 2017, Saturday

**Today's Progress**: When I was browsing through Codepen today, I came across a recommended pen by a creative lady named [Sasha Tran](https://codepen.io/sashatran/#) featuring a CSS drawing (not to be confused with CSS3 animations). I'd seen several CSS drawings recently and Googled the subject, and coincidentally, [an article she wrote on Medium](https://blog.prototypr.io/how-i-started-drawing-css-images-3fd878675c89) back in February was one of the top results. As I scrolled through her progressively more complex designs, I came down with a case of "Me Too!" syndrome and decided to try my hand at my first CSS drawing.

I showed my girlfriend some examples of Sasha's work and told her I was interested in learning how to make similar creations; she loves avocados, so she told me she thought it would be cool if I could try to make one. One of my weaknesses is coming up with ideas, so I graciously accepted her challenge. And that's what I ended up doing today - I made my first CSS drawing of a pretty basic avocado with a little face (and a smile)!

![Digital drawing of an avocado with little black eyes, a smile, and a pit for a nose](http://i.imgur.com/bBEGKBy.png)

I also read through more of the Bootstrap documentation, but in light of the version 4 alpha release, I'm thinking perhaps I should start reading up on that one instead; I understand they made some pretty big changes. On the other hand, it *is* only an an alpha release, so I think I'll at least continue using version 3 on my portfolio page and maybe then start working with the most recent version after that.

**Thoughts** I'm really branching out in terms of my skills, and I'm hopeful that it's not negatively impacting my growth - I wonder if I should be focusing on one thing and getting *really* good at it versus dabbling in a handful of different things. But I'm a curious person and a lifelong learner, so I think for the time being I'm going to keep pursuing what interests me. I feel good about the new skills I learned today, at least, and it definitely doesn't hurt that I'm solidifying my knowledge of what CSS can do (though some of the drawing techniques I'm using feel a little hacky).

**Link(s) to work**
1. [CSS Avocado Guy](https://codepen.io/jaredcaraway/pen/oePMqG/)

### Day 24: September 2, 2017, Saturday

**Today's Progress**: I'm cheating. It's been almost a week since I last logged, but Hurricane Harvey came through my area and threw us for a temporary loop. This broke my streak and made me lose my focus, but I'm back on the horse again (and very thankful to report nothing lost and no damage; we were very lucky). Honestly, I intended to just start from day one, but I wasn't sure exactly how to do that (leave this log as-is and start a new one?). I think the most important thing is that I *code*, and I doubt anybody is really going to care too much that I took a little hiatus. With that said...

I returned to Chicken vs. Egg! today, and I added several more pieces of functionality:

* Score now works
* Eggs now fly in from every side of the screen, though they're presently still limited to horizontal/vertical movement until I figure out how to make them fly at odd angles
* Egg speed increases by 5 (pixels) every 10 points and by 10 every 20 points

I added the random direction functionality on an older branch, so when I went to merge it into my master, there were several conflicts. This was my first time having to go through and reconcile the conflicts, and it was good experience. I only had to make a few changes, and luckily they were pretty minor. At this point, I can say that I have a *very* basic game...but I'm not done.

I still want to add in high scores, perhaps sprite animations, odd egg angles, game over text, and a basic menu. I'd also possibly like to add in some type of power-up, maybe the ability for a second player to join in, and even a difficulty setting (where, for example, you'd have a number of lives to lose before game over; it's currently pretty hardcore in that if you get hit, you start all the way over). Aside from those things, there are a handful of minor tweaks I'd like to make to polish it further.

**Thoughts** Great progress for my first day back at coding in about a week. My code isn't pretty or optimal, but I've got it working the way I want on a very basic level. For now, I'm happy with that - but there's still plenty of work to do.

**Link(s) to work**
1. [Chicken vs. Egg!](https://github.com/jaredcaraway/chicken-vs-egg)

### Day 25: September 4, 2017, Monday

**Today's Progress**: I started the Python track on HackerRank ("HR" for short) today, and since I'm a completionist (and a sucker for gamification), I took a big step backward by starting at the beginning (with printing "Hello, World!" and working with conditional statements, among several other fairly basic techniques). HR is point-based, so I wanted to start at the beginning to earn as many points as possible.

I completed the introductory module (which was so basic that I didn't bother to create repos for any of the problems) and moved into the more challenging...um, challenges. The first required me to take an inputted number between 1 and 9 and print what's called a "palindromic triangle" based on the number. So, for example, if I have an input of 3, the output would be "12321"; essentially, print every number leading up to the input, the input itself, and then every number leading back down to 1, thus forming a numeric palindrome.

My natural inclination would have been to write out some inefficient Shitty First Code, but this particular challenge demanded a solution using only two lines and a single for loop; otherwise, zero points would be awarded. This forced me to really dig into Python's functionality to learn how to effect the proper output in a single print statement. I knew I'd need to use functions.

After some tinkering, I figured out I'd need to print out a range followed by the inputted number. I also learned how to print the range backwards and that I could specify the interval by which the range incremented/decremented. My initial solution was correct, but the output was a couple of lists with the inputted number sandwiched in between. The solution calls for a string.

This led me to figuring out how to convert the list to a string. With a little research, I found that the map function is what I was after. The map function allows you to run a function on a list - in my case, I ran the str function on my ranges to convert each of the integers to a string; however, this still left me with a list of strings that I needed to join.

Enter the join function. I used ''.join() around my map function to join the elements together as a string with  no separator (denoted by the quotes with nothing inside).

And with that, I'd solved the palindromic triangle challenge... Or so I thought.

One of the other constraints is that you're not allowed to use strings at all. I racked my brain, but ultimately I had to look at the discussion section of the problem to figure out how to solve this. The problem is titled "Triangle Quest 2," and I hadn't completed Triangle Quest 1. If I had, I would have learned that this problem could be solved mathematically. The solution is very tricky, and I'm honestly not sure I would have figured it out on my own.

For n between 1 and 9, the palindromic triangle can be determined via the formula (10**n//9)\*\*2. In non-Pythonic terms, this means you would raise 10 to the power of n and divide it by 9 to return an integer (rather than a float; in Python 3, // returns an integer result whereas / returns a float). This result is then squared to give the answer. So for n=3, you would get 1000//9 = 111. 111\*\*2 = 12321. Very clever, but definitely over my head. All the same, I'm proud of having figured the answer out more literally with strings.

In other news, I switched interfaces on Ubuntu from the default Unity to Gnome. I like them both. I'm more comfortable with Unity, since I've got more experience with it, but I appreciate how much cleaner (and more extensible) Gnome is. It's probably been two months now since I've logged into Windows; everything I've needed to do has been possible (and usually, though not always) better in Linux. I'm sure at some point I'll log back into Windows to try my hand at game programming in that environment, but as for now, there's no real need.

**Thoughts** I learned a substantial amount from this two-line programming solution. It was surprisingly rewarding to have the minimalist constraint, which forced me to think in ways that disallowed bloated code. However, it also taught me how much more I have to learn about math (and how difficult it is for me to think mathematically).

**Link(s) to work**
1. [Numeric Palindrome](https://github.com/jaredcaraway/num-palindrome)

### Day 26: September 5, 2017, Tuesday

**Today's Progress**: Back with another HackerRank challenge today in Python. This one provides a list of text commands to be performed on a list, which involved me using the sys.stdin functionality. The list of commands starts with a number representing the number of commands to follow (which, in hindsight, I realize I disregarded in my solution). A list of plaintext commands, such as "insert 0 5" and "print" follows. The solution I came up with involved splitting each line from stdin into components, then inelegantly checking for each command with a set of if-elif conditional statements.

This one wasn't a brain bender, but it did take me a while to research how to run it on my local machine. I took the approach of storing the input text in a separate file, then running this command from Terminal: "cat commands.txt | python list-commands.py". This provided the data in commands.txt as the stdin (whereas on HackerRank the input is read in automatically). Fairly straightforward problem to solve, but I did enjoy it. I'm trying to figure out how I can refactor the code, perhaps using lambda functions in a dictionary.

**Thoughts** Not the sexiest problem, but I still learned some new stuff today. Among the things I learned, which I didn't even incorporate into the solution, was how to pass a list of arguments (args) and keyword arguments (kargs) by prefacing function parameters with \* and \*\*, respectively. I'm going to try to work on something a little more fun tomorrow, though.

**Link(s) to work**
1. [List Commands](https://github.com/jaredcaraway/list-commands)

### Day 27: September 6, 2017, Wednesday

**Today's Progress**: I told myself I'd be back in Windows eventually, and that ended up happening sooner than I'd expected. In the process of switching my Ubuntu GUI from Unity to GNOME and back to Unity, I somewhat broke it. Until I have time to figure out how to fix it, I'm back in Windows 10. I already miss Linux. I started to edit this log in my old go-to, Notepad++, but I discovered that it doesn't have built-in Markdown syntax highlighting. Coincidentally, earlier today I downloaded Visual Studio Code, since I've seen a number of other people recommend it, and as an added bonus it recognizes Markdown and automatically highlights it. So I'm giving this editor a try, but I'm only just now starting to work with and thus haven't had time to form any opinions on it yet.

I really want to make my way through the rest of FreeCodeCamp, but in order to do that, I'll need to use Bootstrap so I can revise my severely lacking/incomplete portfolio. And in order to do that, I'd prefer to go ahead and familiarize myself with BS4...and that's time I don't quite have at present, but I'll try to chip away at it.

Speaking of Unity, I also installed the Unity engine (for game development) today. It looks pretty complex, so I'll also need to find time to educate myself on that a bit before I start diving in. Also on my to-do list is learning to make my first 3D model in Blender, perhaps with the ultimate goal of incorporating it into a game. Again, the only real factor is free time. I've got an insatiable hunger for learning new things, but I'm also fond of biting off more than I can chew, which can have a negative effect on my overall progress if I overwhelm myself...so I'm going to try to keep taking small steps forward and attaining achievable goals. There's no real rush.

On a final note, I stopped by my local library again today and checked out 2013 book called PHP Design Patterns. It's got some advanced concepts, way beyond anything I've ever done in PHP (mainly in the WordPress realm), but I'm hoping to glean some knowledge which may even extend to other languages.

**Thoughts** I really want to get Linux working again. Switching back to Windows (which I've used for decades) has resulted in a severe decrease in my productivity. A little bit disappointed with my lack of progress today, but I can't realistically expect *every* day to be a total success. I'll devote more time tomorrow to troubleshooting whatever the hell I did to break Linux.

**Link(s) to work**
None today.

### Day 28: September 7, 2017, Thursday

**Today's Progress**: I'm pretty pleased to say that I got back into Ubuntu, and I feel back at home. It's strange because, while I don't consider myself to be a Windows fanatic, it's the OS I've used since I was a kid and with which I'm most familiar. And yet, within a matter of months, I've taken more of a liking to Linux. It's got its drawbacks, for sure, but when it comes to coding, I hit my stride in Ubuntu.

I wasn't able to get Unity running again for whatever reason (despite repeated failed attempts), so I decided I'd settle for reinstalling GNOME just so I could get back into Linux in some form. Luckily, I installed 3.8, and it's MUCH better than the version I installed previously (which must have been older). I think I'll give up on Unity and stick with this GUI. I went ahead and installed Visual Studio Code on this OS as well, and I think I'm starting to home in on my ideal development environment.

One of the things I like a lot about VS Code so far is its extensibility. I added a Python extension which runs PyLint every time I save, and it's brought to my attention that I've been writing code which isn't up to strict Python standards. For example, variables not contained within a function are considered classes, and there are certain naming conventions I've been disregarding. In the process of developing a single script, I've learned quite a bit about writing more "proper" Python code.

I got an email earlier today informing me that I've got a copy of Machine Learning in Python waiting for me at my local library; I'm excited to check it out. I started reading up a little on statistics in the meantime to prepare myself, since there's a *lot* of math in machine learning.

On the coding front, I started a new HackerRank Python challenge (which is what I started using PyLint on, learning about naming conventions and such). This one takes an XML file and returns a "score" which is the sum of all attributes associated with the XML tags. For my purposes while developing, I included a sample XML file in the project directory on my machine. My typical practice was always to reference the file name (without a path), and it's always worked, since I've always had the file in the directory I was running it from. VS Code gives you the option to run the file in Terminal from within the editor, and I found that it was unable to locate the relative path of the file. This led me to research how to more properly reference a file's relative path by way of importing the os module. It takes a couple more lines of code, but I think it's a much stronger way to read in a file via relative path.

The funny thing about all that is the HR problem requires reading in info from stdin, not a file. All the same, I learned some good info in the process. And new knowledge is my ultimate goal in this adventure; constant new knowledge. That's the only way to truly grow.

I haven't solved the problem according to HR's terms, but I have written a script which successfully traverses an XML tree and returns the sum of all attributes contained within the tags. With a little modification, I'll have it solved and bump my rank up a little.

**Thoughts**: I am so happy to be back working in Linux. I learned a good deal today, and for that, I am satisfied.

**Link(s) to work**
[XML Score](https://github.com/jaredcaraway/xml_score)

### Day 29: September 9, 2017, Saturday

**Today's Progress**: I took a day off yesterday, but I'm back at it again today.

I've been working as a contractor doing transcription editing for a company called 3Play Media, which has absorbed a good chunk of my free time as of late. I have previously worked for a couple of other web-based companies doing transcription work, namely TranscribeMe and Rev, but I ditched both of those due to low-quality audio files and substantially lower pay. The model for 3Play is also different - they run files (which, on average, are *much* higher quality) through an audio recognition software to produce a preliminary transcript, and my job is to run through the file and correct any errors the recognition software produced in addition to breaking the text into paragraphs, adding punctuation, and so forth. That's slightly irrelevant information, but I felt like mentioning it, because logging for this project feels pretty much like blogging at this point (and I thought I'd mention it for anyone who's reading and might be interested in applying to do this type of work).

On the learning front, I've started working through the Statistics and Probability course on Khan Academy in conjunction with reading The Cartoon Introduction to Statistics by Grady Klein and Alan Dabney, Ph.D. This knowledge will be crucial as I start getting into machine learning; as a Literature major, I never needed to take Stats in college. So far, it's pretty straightforward (although I did find what I believe to be a mistake in one of the problems on KA, which I reported).

So far, I'm entirely satisfied with my switch from Kate to VS Code. For a full-featured editor, it doesn't take too long to load, and I'm pleased with how responsive it is (no lag when typing, which I expected may be an issue).

In a major step forward, I set my laptop up on a shallow desk with a small LCD TV hooked up to it as a second monitor. I feel like I just got room to stretch my legs. Having a second monitor is SO awesome. I was previously doing all of my work sitting on my couch with a TV tray beside me to hold my various books/drinks/etc. I've still got that beside me as a sort of extension of the desk, but it's extremely nice to have a solid surface to sit everything on, to write on, and to get the hot laptop off my lap. I've also got my headphones hanging on a thumbtack on the wall within arm's reach for added convenience. Definite win.

I created a Kaggle account and downloaded a few datasets (top 5,000 movies on IMDB; 712 Pokemon). I doubt I'll get around with playing with them today, as I don't think I yet have the tools to do anything meaningful with them. But I'm interested to do some number crunching sooner rather than later, once I get a bit more of an idea of what I'm going to do with this information.

On the coding front, I am back on HackerRank again today. This time I solved a problem using a brand new (to me) technique: exception handling with try/catch. It's something I'm aware of, but have never needed to use (or wasn't sure how to implement). You're given a set of numbers as a list, and you're supposed to return the penultimate highest value. This means that if you sort the list and there are any duplicates, you need to keep looking back from the end of the list until you hit the second to last unique value. I couldn't immediately identify a function in Python which would allow me to quickly remove the duplicates. After some brainstorming, I tried searching for entries in the list using index(). I learned that it returns a ValueError if you give it an argument that's not contained in the list. My approach, then, was to create an empty list. Iterating through the given list, within a try statement I call index on the blank list for each element. If the element is found in the new list, it's a duplicat and unneeded, so nothing happens. If the element is not found, it's not in the list and needs to be. So within an exception statement, I append the current element to the new list. I'm sure there's a more clever approach, but I was proud to figure out how to use error handling of my own volition tonight!

**Thoughts**: I missed a day, but that doesn't bother me. I've still been constantly educating myself, and my will to continue coding hasn't lessened at all. I'm still thinking up new ideas to try out in a program. I can't wait to get into machine learning.

**Link(s) to work**
[Second Largest Number](https://github.com/jaredcaraway/second_largest_num)

### Day 30: September 10, 2017, Sunday

**Today's Progress**: I've decided to start another game - Tic Tac Toe. Even though it's a simple game, I'm finding myself spending a decent amount of time up front thinking out the design. I personally don't enjoy playing tic tac toe; I'm doing this as an exercise in thinking and implementing a new project. (I've included a link in today's log, though as of this posting there is not much to see, and the game is not anywhere near playable.)

I find myself asking: how do I represent the player in a way that would later allow me to easily implement a second player? Should I implement the game board as its own class? Which methods should each of these classes possess? So far, I've decided to create separate classes for both the game board and the player. I still need to add in a class to represent the computer AI while there is no two-player mode. Within that, I'll also need to figure out how to effectively provide for several different difficulty settings (with the highest being impossible, where the computer will only be able to either win or draw). Since this is one of the simplest possible games I could program, I'm trying to figure this all out on my own through the iterative process of trial and error.

Even once I've got the core mechanics of the game done, there's not a whole lot of polish I can really add - but I'd like to at least add in a menu. Maybe I'll add in a "time trial" mode so the player can compete against their personal best time in beating the computer. This is honestly a pretty boring game, so I'm doing this all for my own information and experience. So far, it's paying off; I am using a Python technique that's still relatively new to me (list comprehension) to automatically fill a two-dimensional array with values upon instantiation.

I'm also still loving Visual Studio Code. PyLint has been extremely useful to me, though I do suspect that some of the objections it's throwing at me are unnecessarily strict. All the same, I'm modifying my code to remove the errors/warnings so that, even if it compiles with them?

On the education front, I've continued with my Khan Academy lessons on Statistics. I'm going through basic graphing/plotting stuff today. Most of it is not new to me, but I did learn about stem-and-leaf plots, which I don't recall ever learning about in school. I'm not sure how useful that particular skill will be, but it can't hurt to tuck it away in case I need it one day. I've also continued reading my stats graphic novel (basically) which I mentioned in yesterday's log. It's pretty cute, and it's got some good information. I don't think, though, that I'll retain this info until I actually put it to use.

**Thoughts**: Solid progress today. I am happy about it! Looking forward to getting another simple game under my belt. I'm sure even programming something so simple will offer me some new knowledge, especially when it comes to calculating potential moves for the AI.

**Link(s) to work**
1. [Tic-tac-toe (main repo)](https://github.com/jaredcaraway/tictactoe)
2. [Today's commit](https://github.com/jaredcaraway/tictactoe/commit/7c3f2bd231612037f318b44e8a695e08edd5cb9c)

### Day 31: September 11, 2017, Monday

**Today's Progress**: I started working on my first major refactoring project - drastically modifying Chicken vs. Egg! to meet PyLint's standards (the best I can, at least). This ranges from removing trailing whitespaces to breaking too-long lines to renaming variables to make them more Pythonic. I started by moving the main guts of the program into a main function, and this threw up close to 80 errors and warnings(!).

When I was writing the game, I was more focused on learning how to use Pygame and simply *getting it working*. I was under no impression that I was following best practices. Going through these errors shows me the extent to which I was ignorant of best practices (and I say that strictly factually, not negatively). I'm learning a *lot*, and I'm being forced to rethink my original approach in many cases. Just to name one: I originally had three different color variables storing RGB values as tuples. One of PyLint's warnings advises you when you have too many local variables; to try to reduce this number, I combined the colors into a single dictionary.

I am currently working on a Game and GameField class; I'm trying to compartmentalize the various variables as much as possible. It's taking quite a bit of mental processing power.

For a change of pace, I switched back to Tic-Tac-Toe. I've gotten the game to the point where a windowed display opens and remains open until it is closed via clicking X or, alternatively, hitting Q or escape.

**Thoughts**: Refactoring makes me go cross-eyed. I'd be lost without Git.

**Link(s) to work**
1. [Tic-tac-toe (main repo)](https://github.com/jaredcaraway/tictactoe)

### Day 32: September 12, 2017, Tuesday

**Today's Progress**: After over three months of searching, I've finally found another full-time job (not in the development field...yet). I start Thursday; this will drastically reduce the amount of free time I've got for coding, but I'll still make sure to get in at least an hour a day if at all possible. I really enjoy it. Also, I did my coding duties yesterday, but I was too lazy to publish and tweet the log... so I'm posting my logs for both yesterday and today as though I didn't miss anything.

I continued working on my Tic-Tac-Toe game today. I have now changed the background color to white and added in lines, neither of which were particularly difficult. I've also added a red selector box (an outline within a cell) to indicate which square the user is currently focused on. I now need to implement a function that draws the player's letter. As it stands currently, the so-called "selector" is hard-coded and cannot be moved. I just need to figure out how to make it work mathematically so I can easily shift it from square to square in response to the user's keypresses. My ultimate goal is to make it possible for the user to define a field size larger than the standard 3x3 grid (and possibly even a rectangular shape).

As I got deeper into the code, I realized I should probably rethink my approach, because it was already starting to get tangled. When I started, I had a main function in which I instantiated the various objects, including Pygame and the game board. This made it awkward to get the various class instances to recognize one another for various functions, and I also found that there were a number of variables and data structures which didn't fit neatly into one class or another.

So I checked out my master branch, made a separate branch off of that, and took a shot at creating a Game class. What's useful about the Game class is that it includes instances of the necessary game objects. Also, upon instantiating a Game object, I can run things like pygame.init() and keep the main function clean. I got it running again on a basic level (as mentioned a few paragraphs up); next, I'm not sure whether I'll continue developing the current feature branch I'm working on, or just abandon it and start from scratch using a new branch based off of my currently good master branch. I don't think it would take much more work to restart the feature development, and it may make for a cleaner process. I'll report back.

Separately, I learned that the underscore character in Python terminal is used to return the last result. I often use IDLE as a calculator, and sometimes I find that I'd like to save the last result into a variable. This is exactly the way I can do that. Nice.

**Thoughts**: I'm pleased with the progress on Tic-Tac-Toe so far. I haven't experienced too many hang-ups yet. A third of the way into this challenge, I can already tell that my code structure is improving. I Google a lot to find answers to smaller, individual pieces, but I'm starting to independently think up better ways to structure my code so that it makes more sense and is easier to write as I flesh my ideas out. I still need to finish refactoring Chicken vs. Egg!, and I haven't really been closely looking at PyLint on this current project...but I will.

**Link(s) to work**
1. [Tic-tac-toe (main repo)](https://github.com/jaredcaraway/tictactoe)
2. [Today's commit](https://github.com/jaredcaraway/tictactoe/commit/580b6b72c25ce7e483ecbbf44b74931ac0d14d23)

### Day 33: September 13, 2017, Wednesday

**Today's Progress**: I return to full-time day job status tomorrow, so I'm going to have to bring my coding more into focus and make the most of my time while I'm doing it. This challenge has been very valuable to me in that it inspires me to keep coming back [nearly] every day to work on something else (or continue working on something I'd started previously, rather than letting it fall by the wayside.) If I'm not coding, I find myself at least sporadically thinking about it. I'll look up articles online about Pygame modules, or read about the Phaser HTML5 engine I'm curious to try out once I get my current projects to something resembling a stopping point. Or Unity. Or any number of other things. My curiosity and thirst for knowledge are boundless. I've got the 100 Days project to thank for my following up on my curiosity. The more I read and do, the more I want to learn and try.

For today's work, I don't have anything particularly interesting to share with the reader, though I did make more progress. I switched back over to my Chicken Vs. Egg! refactoring project for a change of pace and to prevent myself from stagnating by putting too much time between the last time I worked on it and forgetting where I left off. I learned a new Git command, merge-base, which returns the hash of the last commmit in common between two branches you compare. I was interested in knowing how to find the common ancestor of two branches because I've got a couple of feature branches which are branches off of a branch, and I wasn't quite sure which ones incorporated some of my more recent work. Merging the branches in these is going to be interesting, because I've diverged to a certain extent. In one, I began developing a feature within my initial structure, and the branch I'm currently on is largely a rewrite to provide a cleaner structure. As with Tic-Tac-Toe, I added in a Game class where I'll store the global-ish variables that don't fit neatly into any other class (and which I would prefer not to include in the main) loop. I've also moved the Chicken and Egg class instances to the Game function along with other objects like the clock instance.

In the process of working on and switching between so many different branches, I've also learned about Git's stash feature. There have been times when I've done work, realized it fell outside the scope of my branch, and wanted to switch over...but when you've got uncommitted changes, Git won't let you change branches. This is where stash comes in handy. It lets you essentially save your work to a stack of uncommitted changes, thus allowing you to switch to the appropriate branch. You can view a list of the stash stack, find the one with the work you want to pull in, and apply it to the current branch. Very handy feature. I truly do love Git at this point and in only rare circumstances (throwaway single-purpose scripts) would consider working without initializing a repository, if only to keep track of my changes locally without pushing them to Github.

Correcting my code to fall in line with PyLint's standards has also led me to another discovery: the staticmethod decorator. Within the Game class, I created a few methods which don't work on any class information. For example, one of them is called quit(), and it's called when the Pygame window is closed. This used to be at the end of my main program code, then at the end of my main function. Because it doesn't have any real relation to the Game class (other than logically), I removed the self parameter. PyLint then told me it could be a function rather than a method. Upon looking into it, I discovered the staticmethod and classmethod decorators. Adding @staticmethod before the function declaration took care of the error. My next challenge will be figuring out how to access the field\_width and field\_height variables, which are within the Game class, from within the Egg class.

**Thoughts**: I'm a third of the way through the challenge as of today, and I feel confident that I'll be able to see it through (and perhaps even start another round at the end to keep propelling myself forward). I feel highly motivated to continue learning. There's so much I want to be able to do. I want the power to do cool things with code, and continue to improve the games I'm making. I've started slowly reading Game Programming Patterns by Robert Nystrom in an effort to get more insight into the structure that goes into a solid game. It's highly informative and enjoyable to read. (NOTE: I've included a link to the add-game-class branch on Github in case you're interested in looking at my code, but it is not currently runnable. The master branch should still be fine, though.)

**Link(s) to work**
1. [Chicken Vs. Egg! (main repo)](https://github.com/jaredcaraway/chicken-vs-egg)
2. [Today's commit](https://github.com/jaredcaraway/chicken-vs-egg/commit/2893bd6d11f6465b2741b19b0f5f9596092f5ef5)

### Day 34: September 15, 2017, Friday

**Today's Progress**: I skipped another day yesterday. I didn't get much sleep the night before my first day back on the job, and I was exhausted all day. I couldn't muster up the energy to sit at my computer and work on code, or do much of anything, really. I was still exhausted today, too (even though I got a little more sleep last night), but it's Friday, and I can't let myself go dormant. If I stop for too long, there's a chance I'll lose momentum and stop for good. I don't want that to happen.

I "finished" refactoring my code today for Chicken vs. Egg! I'm not actually finished, of course, because there are still several features I need to work back in (I started from a branch that was behind the most-developed one). I actually got a strange pleasure from going through and reworking my code. It feels a lot cleaner. I ran into several snags which, while I was able to ultimately solve, I'm still not sure I've fully resolved. The main issue is how to access the Game properties field\_width and field\_height from the Chicken and Egg classes. I got the code to work by recalculating these properties within each of the classes themselves. I feel like the alternative would have been to extend the Game class for the purpose of exposing those properties, and that was just overkill. I am probably wrong, though, and at some point in my coding journey I'll figure out the proper way to do it. I don't think my architecture was necessarily wrong.

My code is definitely much stronger now than it was when I started out making this game. I've been working on multiple monitors since I set up my desk, so I reverted from fullscreen to a windowed display. The problem is that when Pygame gets the screen dimensions, it considers the entire width of *both* monitors. The playing field thus becomes doublewide, and it just doesn't work for this game. I have yet to find a feasible solution to this issue. Until that point, I'll just keep the game windowed (and reduce the chicken size and egg speed) to get the performance I want, even if it's not ultimately ideal.

I'm worn out. I am going to bed now.

**Thoughts**: In some ways, refactoring isn't as exciting as starting a new project. In other ways, it's exciting to tighten up my old code. The visual performance seems smoother; I haven't closely compared, but something about how I am updating and rendering the code now removes a previous visual glitch that made the chicken lag behind a bit, leaving something of a "ghost" on the screen when moving. Maybe it's the placebo effect of having neater, more thought-out code structure, maybe there's a real performance improvement; either way, it really does feel smoother. After comparing the two files with Github's built-in compare (add /compare to the base project URL on Github), I learned I could merge the two. So I went ahead and merged all of my changes back into the master. Nice!

**Link(s) to work**
1. [Chicken Vs. Egg! (refactored, runs!)](https://github.com/jaredcaraway/chicken-vs-egg/)

### Day 35: September 16, 2017, Saturday

**Today's Progress**: After logging yesterday, I stayed up a little longer and looked into a little bit of Google's Golang. I found it interesting, and its execution performance is unsurprisingly much faster than Python in benchmark tests of "toy programs" (a term I just learned today). However, it doesn't seem to be as well-suited for programming as C++, which is still fairly widely used in making games. Using Pygame is fairly straightforward, and it's a fairly popular Python package, but I'm afraid that Python is ultimately going to lack the performance I'm looking for in programming.

I initially took a year of C++ in high school and returned briefly to it for less than a semester in college when I switched my major to Computer Science (before getting fed up and switching right back out of it). So, all things considered, I haven't really messed with C++ in over a decade. But today, I decided to set up my development environment for C++ so I could get started learning again.

I read that Eclipse is a decent IDE for C++, and I also discovered that it was already installed on my Ubuntu distro, so I fired it up, took a few additional steps to configure it specifically for C++, and typed in a sample program I found online to ease myself back into the syntax. After compiling (something that had become foreign to me in my dealings with Python and JavaScript), I got the program to run successfully...and I was hooked. So the next step was to identify a halfway decent game development library and start learning how to use it. This led me to the SDL (Simple DirectMedia Layer) library, which I understand to be fairly popular and perhaps a good place to start. There's nothing preventing me from switching to a new library if this doesn't offer what I'm looking for.

Right out the gate, a major difference (aside from compiling and syntax) is the process of adding libraries to the C++ environment (whereas Python's packages install rather neatly via pip install). SDL in particular hung me up for a bit because initially I was under the impression that I needed to download the library's source and compile it myself, which required a sizeable number of dependencies to be installed as a prerequisite. I ultimately learned that I could more easily install the library via apt-get, which was a relief. However, getting the compiler to recognize the installed library was something else altogether. I wasn't sure coming into the C++ world exactly where on my machine the include files were stored, but after Googling I found my answer. This led me to then figuring out how to add in the SDL library to be recognized at compile time. All of this took away time that I could've been programming, but that's standard overhead to be expected when taking on a new language and new set of tools.

So for today, I don't have anything to really share in terms of proper programming; but I've embarked upon a new path, and I'm looking forward to seeing what I can come up with in C++.

**Thoughts**: I wish I'd gotten my IDE up and running more quickly, but the important thing is that I *did* get it up and running, and I'm excited to start working with C++. I do plan on still working with Python occasionally. The simplicity of it is very appealing, and it's probably still going to be my go-to language when it comes to prototyping and throwing together scripts where performance isn't the key consideration.

**Link(s) to work**
1. None

### Day 36: September 17, 2017, Sunday

**Today's Progress**: I continued practicing with SDL in C++ today. I completed the second lesson at [LazyFoo.net](http://lazyfoo.net/tutorials/SDL/index.php), which led me through how to blit an image to a window. I'm still not confident enough in my abilities with this library (or my return to C++) to try my hand at my own program, but it's only a matter of time; it won't be long.

A fairly bigger development came today when I returned to Python. I was thinking about what feature I want to get running next in Chicken vs. Egg!, and I thought about how I could add in sprite animation. I know that a common method is using a sprite sheet, where all of the different stages of a sprite animation are included in a single file, laid out horizontally or in a grid, and you programmatically display slices from that single image file to produce animation in a similar way to how film frames projected onto a screen simulate action and movement.

I remembered reading in the Pygame documentation that, when blitting one surface to another, you could also specify a rectangular area to select within the surface to be blitted - in other words, a slice. I decided to adapt the base game logic from CvE! to set up a little demo. I whipped up a simple 50x250px image in GIMP containing the numbers 1 through 5, all laid out horizontally. My goal was to blit each number to the screen running up to 5, then start over at the beginning in an infinite loop that ended only when the window closed. Since my default FPS in my loop is set to 30, and there are 5 slices of image to display, I wrote logic that moved the frame of reference within the sprite sheet to the right by 50px every 6 frames. I'm sure there's a way to do this with Pygame's built-in Clock, but for the purposes of getting it running, I added a frame counter variable that incremented every frame up until 30 frames, at which point it started back at 1.

![Animation cycling numbers 1 through 5](https://github.com/jaredcaraway/sprite_sheet_test/blob/master/assets/sprite_sheet_test_1.gif)

I ran into a little snag due to an initial misunderstanding of the pygame.surface.blit function parameters. It accepts two mandatory parameters, source and destination surfaces, as well as two optional parameters, area and special flags. I have yet to use special flags, but area is where I tripped up. In my head, the area of the rectangle to be selected from the larger image would be specified by providing the coordinates of the top left corner followed by the coordinates of the bottom right corner. In fact, you only need to supply the coordinates of the upper left corner followed by the width and height of the rectangle. Once I figured this out, my little animation demo worked like a charm.

My next move will be to create a basic actual animation (not using numbers) and scale it up so it's more visible (50x50px is pretty small). Soon after that, I should be able to apply this technique to my game without too much sweat.

**Thoughts**: This is honestly one of the most exciting developments I've achieved since I got back into coding several months ago. I feel like this will be invaluable in my game-making journey. I'm sure there are other, more optimal ways to animate, but I am super proud that I got this method working without having to reference an outside source. I arrived at this through my own thinking and exploration. I'm very happy. Back to work tomorrow!

**Link(s) to work**
1. [Sprite Sheet Test](https://github.com/jaredcaraway/sprite_sheet_test)

### Day 37: September 18, 2017, Monday

**Today's Progress**: On the heels of yesterday's development, I began looking at free assets on [OpenGameArt.org](https://opengameart.org/) that I could put right to use in my game. There's a certain sense of pride with making every bit of it myself, but at some point I have to accept the division of labor and focus on what I'm better at - which is coding over digital drawing. I found a really cool sprite set for a chicken that looks like something out of Angry Birds, [available for free by a user named Bevouliin](https://opengameart.org/content/bevouliin-free-flappy-chicken).

The challenge with this set of assets is that they were provided in multiple different files, not one contiguous sprite sheet. I certainly could have invested some more time to figure out how to make this work, but I prefer the unified sprite sheet approach. I initially opened up GIMP and tried to manually align the images, but quickly learned that this was not the most accurate approach. Remember some of my earlier experimentation with Python's image libraries - actually, one called Python Image Library (PIL) - I Googled how to "stitch" images together programmatically. It turns out that it can be done quite easily.

I copied and very slightly modified a script I found on [StackOverflow](https://stackoverflow.com/questions/10657383/stitching-photos-together) and, with a little tinkering, arrived at a sprite sheet in less than time than if I'd sat there trying to manually adjust each frame. I won't create a repo for this one since it wasn't really my own handiwork, but I'll count it toward my coding time today, at least.

I played around with adding the new chicken into Chicken vs. Egg!, but I didn't get it working; I'm not sure whether to use set_clip or subsurface on the Surface object. I'll have to return to this tomorrow.

**Thoughts**: I was hoping to make more progress, but I am happy to get some more experience with PIL. Now I know how to programatically combine images on a basic level. This seems like a pretty powerful library, and I'm sure I'll come back to it in the future.

**Link(s) to work**
1. None today.

### Day 38: September 19, 2017, Tuesday

**Today's Progress**: I didn't make much progress today, unfortunately - but that's part of the game. The Pygame, in this case.

I ran into an issue which I have yet to diagnose - my PNG sprite sheet, which has a transparent background, is blitting with a black rather than a transparent background. I didn't have this issue using my previous chicken PNG, but I also wasn't trying to blit a smaller rectangle from that image.

I switched back to my master branch, and I found out that I had apparently committed changes to the master rather than the feature branch. I rewound my changes by a few commits, finding that I'd then undone my .gitignore file (which I added to exclude the original assets used in the sprite sheet as well as the utility script used to stitch them together). I added the .gitignore back and ran the utility script again to regenerate the sprite sheet...in the master branch, rather than the feature. So I decided to give myself some time away from the project to untangle my brain and think on it a bit.

I switched over to a new project where I'm trying to read in a JSON file from Trello and manipulate it with the ultimate goal of presenting a custom report based on the file (which is one of my Trello boards). I've only just started working on it, and I'm trying to figure out how to work it...so not much progress on that front, either. I'd like to stay up working more, but I also need to get some sleep so I'm not falling asleep at work. I'll be back tomorrow to make some more progress.

**Thoughts**: Bit of a disappointing day in coding, but that's alright. Once I figure out how to get over my current hurdles, it'll be so satisfying. As a side note, if anybody happens to be reading this and is interested in working collaboratively on a project, shoot me a message on Twitter or email me at jared.caraway@gmail.com. I'd like to get some experience coding with someone else, and I haven't yet found an open source project that isn't above my current skillset (though it's just a matter of time).

**Link(s) to work**
1. None today.

### Day 39: September 21, 2017, Thursday

**Today's Progress**: I took a mental health day yesterday to catch up on my sleep. I've been exhausted at work, and working on nonpaying code yesterday would have been detrimental to my performance at my paying day job. So I just relaxed and got to bed early. But I'm back today!

I purchased a cheap domain and reinstated my hosting account with Nixihost with the aim of playing around with more web technology. I've been focusing a lot on "software" development with my little scripts (and games), but I do want to build my skills back up in the web development field. That won't happen tonight, because my time as a working man is now severely limited. However...

I figured out what was causing my previous issue with losing transparency in Pygame. I fixed the issue by adding in a parameter when initializing my target surface with a flag that specified the surface needed alpha transparency. So I've now figured out how to blit a chunk (animation frame) of my sprite sheet to the screen in such a fashion that it looks like a single PNG with a transparent background (the way it was before, when I was using my own image). The next step will be to animate it. I don't think I'm far from making that work.

In another step forward, I added a README and an MIT license to the repo. I was pretty uncertain about what all to include in the README, so I just gave it my best shot. I figured I needed to just start somewhere, and I can improve it incrementally over time.

**Thoughts**: After a good night's rest, I feel good about today. I definitely made progress, small though it may be, and that makes me happy. It means I'm moving forward. I'm not stagnating. This is good. I pushed the updated code to my Github repo, linked below.

**Link(s) to work**
1. [Chicken vs. Egg!](https://github.com/jaredcaraway/chicken-vs-egg)

### Day 40: September 22, 2017, Friday

**Today's Progress**: I took another day off yesterday. Balancing work life and home life and learning development skills is surprisingly challenging. I don't have a bottomless well of energy like I used to...but I've still go the determination to press forward as time allows.

I got sprite animation working on a basic level, but it's sketchy and buggy. The method I got to work still displays a mysterious second frame underneath the animation, and there's a thin border around the sprite. I've got to do some debugging to get it cleaned up, but I do, one a basic level, have working sprite animation. And it looks pretty cool, even in its broken state.

I've made a Trello board to start organizing the features I want to incorporate. I think it'll be good for me to brainstorm and get all the ideas out of my head and onto "paper," so to speak.

**Thoughts**: Feeling accomplished and also anxious to get the issues ironed out of my player sprite animation. Maybe tomorrow I can get to the bottom of it.

**Link(s) to work**
1. [Chicken vs. Egg!](https://github.com/jaredcaraway/chicken-vs-egg)

### Day 41: September 24, 2017, Sunday

**Today's Progress**: I've given myself license to take a day or so off from logging whenever I need to, but I'm still working on at least a little bit of code every day. I've got to strike a balance between life outside coding and my goal to eventually work my way up to my goal of making a living off of coding. Whether I log daily or not, I'm still constantly thinking about coding or doing something to advance my goal.

I've made progress on my sprite animation. Previously, it was somewhat working, but the animation layer was displaying on top of the previous frame beneath it, and it looked messy. I used a technique called "dirty rects" to, in between animation frames, get a sample of the background, blit it to the location on the screen where the sprite goes, and then blit the sprite there - effectively "erasing" the previous sprite. I had a hiccup at first where I copied the dirty rect, then flipped the Surface containing the sprite drawn onto the dirty rect, and that resulted in a chunk of background behind the sprite getting reversed. To fix this, I simply blitted the dirty rect to the screen *before* flipping the sprite, and it now seems to work more less the way I want it to. I still don't have the animation running *exactly* the way I want (I want to cycle to the end of the sprite sheet, then cycle backwards frame by frame until I hit the beginning, starting again), but this is a great start.

One issue now is that the dirty rect draws over the egg sprite as it moves into the dirty rect's space on the field, but I feel like that won't be too difficult to fix. It's on my to-do list.

In other news, I've made a friend through Twitter with whom I'll be collaborating on some simple projects remotely for experience with working collaboratively. He also advised me of a platform called Chingu, which pulls people together to collaborate remotely on projects, and I applied to be part of a back-end development team today. I'm really looking forward to working on code with other people and sharing ideas and experience. I think it's a key component that's been missing so far in my coding, and I can see it being a very valuable skill to have (especially since, once I finally achieve my goal of working as a professional developer, I will absolutely *have* to work collaboratively).

I'm also considering a structured education (vs. my current method of self-education) to help advance my skills. Yes, all the information I could possibly need to get a job is available to me for free, but the difficult part is disciplining myself and focusing. I think I would benefit from paying somebody else to help provide that structure, which would in turn force me to to focus and discipline myself. Bloc looks great, but it's substantially expensive; I think I'm going to try out the Udacity front-end nanodegree plus program. It's a good chunk of money, but you pay per month and work at your own pace, and they offer a money-back guarantee if you don't end up with a job. I've still got a bit of time before I have the funds available to make any final decisions, but I am considering a couple of different options currently.

**Thoughts**: I feel pretty great about my progress. I am so anxious to further my progress, sometimes it's hard for me to shut down at the end of the day. But I'm doing what I love, and I feel pretty confident that if I continue doing what I'm doing, it'll lead to a career doing what I truly want to do: working with computers and making them do (more or less) what I want.

**Link(s) to work**
1. [Chicken vs. Egg! (current working branch)](https://github.com/jaredcaraway/chicken-vs-egg/tree/animate-sprite)

### Day 42: September 26, 2017, Tuesday

**Today's Progress**: Through the magic of Twitter, I befriended a guy on the other side of the world and began collaborating with him remotely. Until now, I've been coding alone and in a vacuum. It gets lonely working alone, and the necessity of doing everything myself gets limiting. Since I want to become a professional developer, I also knew I would need to learn how to collaborate on a project sooner rather than later. So I tweeted out to my followers saying I'd like to work with someone, and I got a response from someone named Darshan in India.

We spent a few days talking before setting up a Slack channel and a Trello board to communicate, brainstorm, and organize our ideas. He is currently learning front-end dev skills through freeCodeCamp, and I'm more interesting in back-end stuff, so we brainstormed a project that would play to both of our skills. Ultimately, we came up with a tried and tested calculator concept.

Darshan set up the structure of the calculator and I was left with the task of wiring it all up. That's what I spent hours doing today. For a fairly straightforward app, it's surprisingly complex to get running like a real calculator. I've been working in almost exclusively Python for a month or two, so my JavaScript skills have gotten a bit rusty. But I'm picking them back up, and I'm making progress.

At this point, I've gotten it to where it recognizes mouse clicks on the buttons and displays them in the calculator's designated output display area. I'll spare you all the boring explanation, but if you're interested, you can check out the shitty first draft of my logic in the repo. Even though this is a basic app, I am hooked. I am anxious to keep working on it until it's working (more or less) perfectly and we can put some polish on it. We're thinking about adding in CSS zen garden-style functionality where you can apply different skins. It's awesome practice, and I'm really enjoying working with someone. I could definitely see myself doing this for a day job (though I imagine the stress of that will be on a whole different level).

**Thoughts**: I am truly excited about this project. It's not that I've gotten bored with coding by any means, but finding someone to work with and hold me accountable has really given me a second wind. I look forward to getting some rest and returning to it after work tomorrow.

**Link(s) to work**
1. [Simple Calculator (dev branch)](https://github.com/juzJar/SimpleCalculator/tree/dev)

### Day 43: September 27, 2017, Wednesday

**Today's Progress**: Made some more progress on the calculator app today. I figured out how to get the page to recognize any general keypress, then honed in on the specific keys I'm targeting. I adapted the main function I was using to process button clicks to now recognize if it was being passed a keypress event, read in the value of that key, and was able to maintain a bulk of the previous logic. I'm finding that I've really taken for granted what all goes into something as seemingly simple as not duplicating a decimal on the display when it's pressed more than once (which was actually pretty easy to implement, but didn't work the way I probably would've expected by default). Not that this project is necessarily difficult, but it is much more challenging and complex that I anticipated at the outset. But I love being challenged, so that's a great thing. I'm going to be so proud of our work once this is done. It's a big relief having Darshan on my team to help with the front-end stuff, too.

The logic inside of my button/keypress handling function is a series of if/else statements right now, and it's pretty nasty, but I'm considering it Shitty First Code and running with it until I inevitably stumble across the smarter and sexier way to get it done. I have no doubt that there's a superior method, but right now I'm settling for what works and is accessible to me now. I suspect it may have something to do with key/value pairs? I'm not certain, but I'll look for it once I get to the point of refining and refactoring.

**Thoughts**: I feel great about the progress I made today. Now I'm passing the ball to Darshan on the other side of the world to work on while I sleep and then go to work. It's an interesting dynamic. I'm definitely anxious to wrap this project up and see what's next. At some point soon, I'm going to take time to return to Chicken vs. Egg! to chip away at it some more, too. I want to make sure I keep my Python skills on point. Check our dev branch below if you're interested in checking out what code was added today.

**Link(s) to work**
1. [Simple Calculator (dev branch)](https://github.com/juzJar/SimpleCalculator/tree/dev)