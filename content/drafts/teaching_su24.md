+++
title = "So I taught a CS course over the summer..."
date = 2024-09-20
description = "First-time instructor reflects on her summer teaching Data Structures and Java."
[extra]
featured = true
short_title = "Teaching SU24"
+++

This past summer (2024), I taught a six-week course on Cornell's [Data Structures and Object Oriented Programming](https://courses.cis.cornell.edu/courses/cs2110/2024su/) class (CS2110). This post is to reflect on my summer and give readers a taste of how summer teaching may go!

**Note:** This post is more of a summary of thoughts and takeaways than a chronological recalling of events.

### Navigation
- [Precursors](#precursors)
  - [Why did I decide to teach?](#motivation)
  - [Some luck-based advantages I had](#caveats)
  - [What is CS2110? How is it different during the summer?](#cs2110)
- [Challenges and Strategies](#challenges_and_strategies)
  - [Analysis paralysis & Cutting corners](#analysis_paralysis)
  - [From copying to arranging](#copying_to_arranging)
  - [Class observations](#class_observations)
  - [Code Demos: Letting go of perfectionism, and why it's actually useful](#code_demos)
  - [Aside: A CS2110 Summer 2024 problem - Longer lectures](#longer_lectures)
- [Takeaways](#takeaways)
  - [Teaching is a lot of fun!](#fun)
  - [Personal takeaways](#personal_takeaways)
  - [A big commitment](#commitment)
- [Special Thanks](#special_thanks)

<a name="precursors"></a>
## Precursors

<a name="motivation"></a>
### Why did I decide to teach?

**TL;DR:** I love helping people learn CS and have been wanting to pursue a career focused on that, and this felt like the next step.

Over the course of my academic journey, I've been lucky to have the chance to help students learn computer science. My first experience was as a [Ninja](https://www.swarthmore.edu/computer-science/ninjas) (aka Student Mentor, which sounds less interesting) for Swarthmore's Intro CS class (CS21), where I hosted help sessions in the evenings. I remember absolutely loving the spark that went off the moment a student grasped a concept they've been struggling with. As a student who also struggled with big-time impostor syndrome (which I still do sometimes as a fifth-year PhD student), it was immensely gratifying to see students build up their programming skills and gain confidence in their ability to do CS.

As a TA in grad school, I got the chance to lead discussion sections, where there was a mix of presenting new material and lab work where we helped students work on group activities. At first, I was really nervous about standing in front of students and being responsible for a part of the class. But as I went through it a couple of times, I got a bit more used to it, and I knew what to improve upon. Soon enough, discussion sections became my favorite part of my work week.

These experiences made me want to go into teaching-focused careers such as a Professor at a Small Liberal Arts College (SLAC), or a Lecturer/Teaching faculty at a Research University. Instructing a summer class felt like the next step towards that goal for a couple of reasons: (1) I could actually get a taste of what teaching CS is like, and see whether this was actually a career path that I wanted to take; (2) I can assess whether I was "fit"/"good enough" for such a job, and concretely figure out what I can improve; and (3) having solo instructor experience is important when applying for such jobs (both for the CV and for forming your own opinions about teaching).

<!--
- I've been considering a teaching-focused job as a career path
  - TA-ing as a ugrad (SLAC): "office hours"/help sessions. Helped me realize I like helping ppl debug
  - TA-ing as a grad student: leading discussion sections/recitations
  - These experiences made me want to go into teaching-focused careers, and this felt like the next step
-->

<a name="caveats"></a>
### Some luck-based advantages I had

I think I was set up to have a slightly easier experience than past summer grad student instructors for two reasons. First, I was a teaching assistant for CS2110 during the previous two semesters (FA23, SP24). On top of that, in FA23 I led grading sessions, and in SP24 I outlined future discussion sections during our weekly TA meeting, designed a couple of new discussion sections, and also designed some final exam questions. This meant that I was familiar with both the contents of CS2110 (and Java), but also the grading procedures, expectations, and discussions. Second, I ended up having only *ten* students. This small class size helped me feel like everything was managable and under control a lot of the time.

<a name="cs2110"></a>
### What is CS2110? How is it different during the summer?

[CS2110](https://classes.cornell.edu/browse/roster/SU24/class/CS/2110) is Cornell's Data Structures course, and often the second class students take after Intro to CS. Some unique topics in CS2110 are Loop Invariants, GUIs in Java (using Swing), and Concurrency.

The summer version of CS2110 is only six weeks long, compared to the 14+ weeks during the semester. Classes were held Monday-Friday for 105 minutes (more on this later). This meant that the class was very fast-paced - students had less time between classes and assignments. But, students usually only take up to two courses in the summer, so I heard that they enjoyed being able to focus on the class. This short-but-intensive summer period had similar pros and cons for me as the instructor. *Teaching during the summer was a LOT of work, but I'm really glad I had the chance to ONLY focus on teaching for a SHORT amount of time.*

<a name="challenges_and_strategies"></a>
## Challenges and Strategies

<a name="analysis_paralysis"></a>
### Analysis paralysis & Cutting corners

I spent two weeks preparing before my first class. I quickly found myself in a lot of analysis paralysis as it dawned on me that I had full freedom to customize this course! The syllabus, the course schedule, how each class goes, the assignments... all of that was under my control. And once I realized this, I simply didn't know where to start. It also didn't help that I felt that I had to do everything perfectly, especially since I felt that my students' quality of education rested within how well I could convey the information in the class.

Around this time, I got the advice to **cut corners as often as I can by borrowing existing material**. This included borrowing: parts of the syllabus, slides, code demos, assignments, grading rubrics, test questions, and more. The rationale here is to help lift some of my heavy load, and that the execution of the class is already a lot of work. The reality is that it's my first time teaching, which Cornell, my mentors, and my students all know. So, noone really expects me to have all of my own materials together. If I used existing lecture slides and tried to recreate the Spring 2024 lecture experience as much as possible, then I surely can't mess up the students' learning experience too badly right? So, I decided to embrace the "cutting corners" idea, by shamelessly borrowing material wherever I could.

<a name="copying_to_arranging"></a>
### From copying to arranging

For me, the first two weeks of lecture were really about *survival* (making sure the class actually ran), and getting a feel for how class can/should be run. Following the "cutting corners" idea, I started my lecture prep by quite literally copying slides from Spring 2024, making tiny tweaks, and doing things (nearly) exactly how [Professor Muhlberger](https://www.cs.cornell.edu/~curran/) did them. I had access to all of his lecture recordings from being a TA in Spring 2024, which I watched religiously for a while. This was really helpful for giving me some groundwork for concepts that I wasn't 100% sure about. I was still really nervous about explaining concepts incorrectly, and copying materials and lectures gave me a sense of assurance that I won't mess up too much. This strategy also helped me get used to my new *professor* (wow) role and focus on my speaking skills, like enunciating and speaking slowly.

The big downside of this approach was that I was starting to spend *too much* time on lecture prep (~4 hours a day), a large portion of which was watching lecture recordings. I also wanted to experiment and try adding my own spin to things. So, in week 3, I switched to watching recordings only when I needed the extra help on understanding or explaining a concept (like GUIs). I also tried to be creative by thinking about my own analogies for concepts, and adding in new slides. I even made my own "extra recursion practice" lecture, where we reviewed recursion concepts and worked on some practice questions. By switching to arranging my own lectures based on the original slides/code demos, I got myself some more time to sleep and also the chance to try my own things out!

<a name="class_observations"></a>
### Class observations

In the second and third weeks of the class, I asked a couple of my mentors to stop by lecture. This was very valuable because my mentors gave me confidence that I was doing some things well, and also pointed out a lot of things that I could improve. For example, my advisor [Adrian Sampson](https://www.cs.cornell.edu/~asampson/) suggested having handouts that students can write notes and draw on, which actually became one of my favorite things to put together in my lecture prep later on. Also, having mentors in the classroom also gave me a first-hand taste of how nerve-wracking teaching interviews might be! :)

<a name="code_demos"></a>
### Code Demos: Letting go of perfectionism, and why it's actually useful (*AYAKA NOTE: better title for this?*)

Coding on your own is one thing; coding in front of a group of students is another. For one, you need to *talk* while you are typing, and you need to make sure you aren't going too fast that students are lost. On top of that, you might feel pressure to never mess up. But of course, sometimes you might get lost in the heat of the moment and make a small bug.

Counterintuitively, a common piece of advice that I got was that **it's more than ok to make mistakes in code demos sometimes**. My reaction to this was "but wait, as the professor aren't you supposed to be a Smart Computer Scientist That Never Makes Mistakes™!?" But, it's actually really important to (indirectly) teach students that we all make mistakes. Bugs are a common part of coding, after all! Making mistakes and fixing them in class gives students an opportunity to watch your debugging strategies, which they can also adopt in their own coding. I once ended up turning a buggy code demo into a class activity, where students had a chance to try debugging the code we wrote together. I'd like to think this was a valuable experience for both me and my students!

Of course, you don't want to be making big mistakes all the time. So, I always had a paper copy of my code demos on the side as I was giving the demo, so that I can always have a reference. Also, I made sure to do a dry run of each of my code demos before lecture.

<a name="longer_lectures"></a>
### Aside: A CS2110 Summer 2024 problem - Longer lectures

CS2110 used to be a three-credit class, which meant that summer offerings of the class had 75-minute long lectures. But, CS2110 became a four-credit class in the past year, which meant that my summer lectures were now 105 minutes long! I was really concerned about how to fill those extra 30 minutes. I was advised very specifically to *not add any more content, but instead to add more activities*. Some other helpful pieces of advice were to *insert an 5-10 minute intermission* (I think this applies for any class that runs 90 minutes or longer), and to *speak slower/take more breaks to check if students have questions*.

So, I needed to figure out what activities to insert. This was another place where "cutting corners" really helped! Many of the code demos in the Spring 2024 lectures involved walking through some pre-written code that implemented an algorithm (I suspect due to time constraints). I decided to turn these code demos into exercises where students can take their own stab at the implementation, before we all got back together and I live coded the solution.

Ultimately, I was glad to have those 30 more extra minutes. Breaks in the middle gave me a chance to recollect myself and answer students' questions, and the extra time really gave me room to breathe!

<a name="takeaways"></a>
## Takeaways

<a name="fun"></a>
### Teaching is a lot of fun!

I really had a *lot* of fun teaching! I always looked forward to another day of class, until the last week when I realized the end was approaching. I felt a sense of fulfillment as I watched my students learn new concepts and improve their coding abilities. Through this experience, I became even more sure about a career path focused on teaching CS.

An interesting find was that I enjoyed *different parts* of the teaching experience as I progressed throughout the six-week session. In the beginning, I couldn't believe how giving lecture became so fun once I got past my initial nerves. There's a weirdly unexplainable adrenaline rush that often happened ~10 minutes into lecture, where I find my footing and let it carry me through.<!-- It felt like no matter how sleepy I was, how tired I was, or how sad I may have felt that day, I got to transform into the me that was so excited to teach computer science.-->

Later in the course, as I started to put my own spin to lecture by having handouts, creating new activites, etc, I started to really enjoy the lecture prep process. Teaching class was still really fun, but being creative and experimenting was another, different kind of fun.

<a name="personal_takeaways"></a>
### Personal takeaways

This experience and the feedback that I got from my mentors gave me professional confidence that I can be "good enough" to go into teaching. But more importantly, I got a lot of *personal confidence* from this experience as well. I knew that this was going to be a challenging summer with lots of *new* things (especially the "professor" role), so the fact that I successfully did it felt like a big accomplishment! The fact that I was responsible for students' understanding of Data Structures, and they demonstrated to me that they really learned the concepts from class, meant that I was able to make a meaningful contribution to their Computer Science experience. I will always remember that one of my students said this class helped them feel less scared of recursion :)

As a perfectionist, one of my biggest takeaways was that it's ok to make mistakes, and not just for code demos. I'm just a person doing my best, and sometimes that meant I made mistakes during class, or I had a couple of bugs in an assignment. When students pointed out a mistake, it was embarassing, but as long as I apologized and fixed the problem, it was fine. Of course, it's best to minimize these mistakes as much as possible, but at the end of the day, we recovered from most mistakes, my students still learned Data Structures, and everything was okay.

<!--
- Got a lot of confidence not only for being an instructor, but as a person?
  - big accomplishment
  - Personally found it really gratifying that students understood what I was teaching
  - takeaway: it's ok to make mistakes
  - improv exercise
-->

<a name="commitment"></a>
### A big commitment

As much as I loved the experience, I cannot end this post without acknowledging how much work summer teaching was. It was in some ways *more* than a full time job especially because so much of it was new. I spent most of my weekday waking hours on the class. I quickly realized that I needed to prioritize my physical health, since I could feel my energy levels decreasing regardless of the adrenaline rush I was feeling throughout the day. By "cutting corners" to the extreme, I became better at dealing with my workload and procuring time to decompress, but the job was still demanding!

Once I was fully done with the course, I gave myself a week to *do absolutely nothing* and that was really helpful. At the end of the day, the work was demanding, but the experience felt very worth it for me because I had *a lot* of fun. I'd do it again if I had the chance :)

<a name="special_thanks"></a>
## Special Thanks

My offering of CS2110 wouldn't have been possible without the help of many people. Thank you all very much!!

- My TA [Youming Deng](https://denghilbert.github.io/)
- My mentors [Curran Muhlberger](https://www.cs.cornell.edu/~curran/), [Adrian Sampson](https://www.cs.cornell.edu/~asampson/), [Zachary Palmer](https://www.cs.swarthmore.edu/~zpalmer/), [Dietrich Geisler](https://www.cs.cornell.edu/~dgeisler/), [Alexa VanHattum](https://cs.wellesley.edu/~avh/) who all provided me extremely helpful advice
- My labmate [Kevin Negy](https://www.cs.cornell.edu/~kevinnegy/) who was also great company as a fellow summer instructor
- Last and most importantly, my students who gave me a chance to help them learn CS :)
