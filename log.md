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