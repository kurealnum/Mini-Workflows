# Personal-Workflows
Workflows/best practices for coding. I _should_ be updating this a lot, so said workflows should be pretty well thought out!

I am **_very_** open to contributions, feedback, or any other form of help/communication! One person writing this may, and likely will, create a very opinonated environment.

Also, please keep in mind that this is not meant to be some rigid guideline that everyone follows. Take everything with a grain of salt.

# Best methods of practice for X + Outlining and workflows: 
My workflows for certain problems, where X is a problem, bug, question, ect.
<br></br>
## The Big 2:
The 2 ***REALLY*** important things to do every time you encounter a bug:

### 1. Check the syntax
This is a crucial part of almost every single one of my workflows, and you'll see it mentioned again and again. Even if you're working in an editor with linting/syntax highlighting, still check it. I've struggled on a lot of very simple errors because I thought that my editor would catch it.

### 2. Walk through your logic
Whiteboarding is an amazing practice here! Make sure to leave plenty of spaces between your "lines of code" so you can come back and change things later!
<br></br>
## Learning DSA/Grinding Leetcode problems:
This is a major learning experience for me, and it'll be changed as I go along!

### Random Notes:
-Data structures isn't just about organizing data, it's also about the operations that we use on those data structures 

-***Blinds 75 list*** (the ex-facebooks devs list) is something that I would love to work through, I just need to have the time and whatnot. I'd also like to note that I actually want to learn DSA (Data Structures and Algorithms), and not just interviews.

## Understanding Leetcode problems

***Use REACTO:***
1. Repeat: make sure you do understand the problem.
2. Example: get insights by doing examples 
3. Approach: come up with your approach(es) to the problem (brute force first)
4. Code: write the code for your chosen approach
5. Testing: pass the testcases
6. Optimize: optimize the complexities (time and space) of your algorithm

The above was written by by [Diego](https://www.youtube.com/channel/UC9s8Wy4D_4dsFjwiufqNAng)

Practice is the most important thing here. Other than that, make sure you actually solve the problem each time. Here's my little "guide" (that I constantly update/change) to succesfully do Leetcode problems, and then actually absorb the information. 

Before I knew about REACTO, I made up my own method of solving these problems:

### 1. Write the problem out:
-Identify what you need to find to solve the problem

-Ideally do this on a whiteboard (leaving plenty of space), but if you can't, do it in the comments.

-Make sure your comments are friendly to ***you***

### 2. Review your written problem a few times:
-Go back over it multiple times, check for so called "plot holes"

>Is there anything that differs from the original prompt?

>Is there anything that I could do to make this better?

### 3. Start coding:
-Explain the problem to yourself as you code

-Write it out. No matter what, walk yourself through a testcase on a whiteboard or something in similar fashion. 

-Practice backtracking through your code; you'll often find yourself doing this when you realize that something needs to be changed

### 4. Revising your algorithm. 
-Take a step back and look at the bare minimum required to pass the testcases. Do you *really* need that whole array?

-It's ok to completely redo something! Just make sure you save your working answer

-If you can't find anything to completely redo, look at how you can optimize your current algorithm

### 5. When you finish:
-Reflect on negative tendencies, on any problems that you're not doing so well on. Make sure you don't repeat those.

-Write it out again. If there was a mistake, if there wasn't

>Why did I come up with this solution?

>Do I need all of this code that I wrote, or is there a lot of boilerplate?

>Is there something I could do differently? How can I make sure I do that next time?

Credit to *haekuh#0254* for this part ^^

### 5. "Post Problem":
-Once you're finished with the problem, write your solution down somewhere

-You can't write or memorize the entire problem, so try and stick to a few sentences, one paragraph at most.

-Google docs/sheets or any similar program works well for this
<br></br>
## Encountering an incorrect function return

### 1. [The Big 2](#the-big-2)

### 2. Walk through the function by:
-Go past the function you're working in

-Go through every function that is called/used in said function

-Go into documentation if the function is built in

-Figure out what it should be returning, and why

### 3. Minimize
-Take away as many functions as possible, and try and isolate the problem function

### 4. Find context
-Look at some other code that involves this function. What does it do differently/the same?

-If it's your own function, attempt to isolate the sub-function (if you will), and do the same for that function
<br></br>
## Encountering a bug
### 1. [The Big 2](#the-big-2)

#### 1.5. If it's an algorithm:
-Are you considering all possible data structures?

-Could you have multiple options for different cases?

-Did you whiteboard it, and truly think through it?

### 2. Reference other code of yours

#### 2.5. Before you google it:
-Should I know this code?

-Should I be able to do this?

-Did I thoroughly complete steps 1-3?

### 3. Google it

#### 3.5. Before you use GPT:
-Have you done everything else you could?

-Are there any other personal methods that I could use?

-Would a person be better suited to this question?

### 4A. Ask a human being:
-There are plenty of amazing online communities that are here to help!

-Places like [TPH (The Programmers Hangout)](https://discord.gg/programming) and language specific communities are frequently found on places like Discord and Reddit

-GPT tends to be better for technicals, but past that, humans will always excel in the artistic design of code

### 4B. Ask GPT (Or a similar tool)
-Make sure you *completely* understand why you couldn't solve the problem

-Practing similar problems isn't a horrible idea, althought it may be incredibly time consuming.

<br></br>

# The mini blog!:

## Introduction/Journaling:
*I'm 16, I'm not a psychologist :>*

All of these workflows are really intended for ***education***, not just for you to code as quickly as possible. That's the secondary goal of course, but if that was truly the primary goal, there would be one section telling you to go straight to ChatGPT.

## Planning

Planning is so incredibly important. The only time I don't completely plan my software out is when it's one file, and ***I know*** that it's going to be shorter than 80 some lines. 

If you don't plan your work out, it becomes so much more tiring to keep track of your goals, and your current place in those goals. This kinda flows into the next section, Breaks.

## Breaks
Breaks are ***very*** important. Whether you want to be as refined as the Pomodoro technique, or you just take breaks sporadically, like me, breaks are incredibly imporant.

I also feel like your mind works a lot better in the background (i.e., the subconscious), than it does in your “conscious” state. What I’m getting at is, if you’re stuck on something, go stare at something and think about something else. Professional chess players do it, so it must work, right? 

## Learn by doing, not by looking
I'm a firm believer in this concept, and if you're reading this, it's likely that you are too. You can read documentation all you want, grind out W3 Schools tutorials, but until you sit down and push yourself through something that you didn't do yesterday, you're not really "learning". Even if you're taking notes, or copying the tutorial down into your own editor, I still don't think it equates to actually doing something. Learning is hard, and while repetition can help, actually challenging yourself will really do the trick.

However, a major problem comes with said concept. That problem being projects; i.e. what projects to do, when, and where. In my opinion (*please remember that I'm 16*), beginners struggle with this the most, because there's no prior experience to help guide you into a new language or framework. However when you take someone who already knows concepts and 1 or 2 languages, the entire dynamic of the whole process changes. You already have a foothold to step on, and leap into that. I think this flows somewhat nicely into the next topic, Tutorial Hell.

## Tutorial Hell
I think tutorials are both a blessing and a curse. On one hand, it can be quite a pain to struggle through the basics of a language without some guiding you, but on the other hand, you could _(and probably will!)_ become very dependent on them. I feel like it's very easy for you to get sucked into an "easy" way of doing things, and not taking the time to struggle through projects/bugs on your own.

Once in, Tutorial Hell is a hard thing to get out of. As I partially mentioned, it feels a lot better to understand a topic immediately, rather than really putting in the effort to have a deeper and more permanent understanding of it. As I've previously mentioned, I think that it's a lot better to sit down and struggle through a problem first, rather than looking at the answer, then memorizing the answer.

## How to google it (properly!)
A lot of information is likely taken from [this video](https://www.youtube.com/watch?v=cEBkvm0-rg0), sue me. Some of my own thoughts, experiences, and opinions will be mixed in there as well.

"Googling it" is a really important skill to have, because who doesn't just copy and paste their error into google? Here's some helpful techniques:
- Use quotations around your search term to force google to only give you exact matches
- If you only want results from a certain site, enter the site like so: site:google.com (Only returns results from google.com)
- If you don't want to find a certain result, use the "-" symbol like so: "good python frameworks -django"
- Filter old, new, and _any range of_ content out with the after:, before:, and DATE..DATE operators like so: how to program in C++ after:2017
- Use the wildcard operator (" * ") to find subdomains and come up with new ideas!
- Search for certain file types with the filetype: operator like so: cute cats filetype:png
- Look at some related sites with the related: operator like so: related:angular.io
- Find the latest cached version of your website with the cached: operator like so: cached:yourwebsite

## Closing thoughts
Take everything I and others say with a grain of salt. Figure out what works for you. Ideas like this shouldn't be all encompassing, but just an idea, in a sea of other ideas. 

Also, not to be the shameless plug, but I do write about similar topics on my [blog.](https://dev.to/kurealnum)

<br></br>

# TODO
- Add a section on "How to google it" (with information from [this](https://www.youtube.com/watch?v=cEBkvm0-rg0) video)
- Revise/change/add to best methods of practice
