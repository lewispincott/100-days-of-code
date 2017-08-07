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

### Day 4: August 5, 2017, Friday

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
