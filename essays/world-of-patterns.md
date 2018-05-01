---
layout: essay
type: essay
title: A World Full of Patterns
# All dates must be YYYY-MM-DD format!
date: 2018-04-30
labels:
  - Software Engineering
  - Design Patterns
---

<h1 align="center">
  <b>A World Full of Patterns</b>
</h1>

In our every day world, we can spot patterns in the many things around us. If you have a dog or a cat, there may be a pattern that can be found in their fur. You may even find patterns in the coats of many animals, such as tigers and zebras. We also see patterns in the way that city blocks are laid out. We even see it in the scales of the vast array of fishes in the sea. Beyond all of this, one may not realize it, but there's a pattern to our every day life. Once we wake up, we follow our routine to get ready for the day ahead of us. We see patterns in our lives every day, regardless of whether or not we realize it.

<img align="center" src="../images/pattern-tiger.png" />
<p align="center">
  Fur coat pattern of a tiger
</p>
<br/>

The patterns we see in our every day life can also be extended to software development, whether we realize it or not. When we encounter a common problem, we generally have a way to solve it or we find one. The solution we get may be of our own or it may be from the knowledge we gained from viewing how other people approached the problem. Obviously, the solution has to work for it to be a valid method for us to solve the problem. This is where the pattern of it all comes into play. We use a method or methods to solve our problem by looking at what works. We find a pattern that allows us to solve the problem. These patterns are not absolute. They're more general in that they solve the problem but the specifics are left to us. This encompasses what are known as design patterns.

To compare a design pattern to something that's maybe more relatable, let's take for example, when you suffer an injury. The pattern that we end up using is to clean and disinfect the wound and then to protect it via a bandage, gauze, or some other material. Well, this is the generaly solution, however, the specifics are left for us to decide. Maybe the wound is large enough where a visit to a hospital is necessary. Or it could be small enough where you just need to use some rubbing alcohol and a bandaid to resolve the injury. Whatever the case nay be, you end up with a cleaned wound and protection of the wound area.

Now, taking all of this into account, I fall into the group that didn't realize that I was following design patterns until I was explicitly told so. For example, when I write simple C# programs with WinForms GUI, I was using a design pattern. The buttons and other various components in the GUI fired off events when they were interacted with that would be caught by its dependents, which would result in some action being done. I wasn't aware of the pattern that was being employed in this case until I learned about design patterns. This is also something that's happening in the present with the use of Meteor collections. Collections are published and subscribed to that end up being displayed on some webpage.

<img class="ui image" align="center" src="../images/pattern-gui-small.png" />
<p align="center">
  A program I made to fiddle with the tags of mp3 files with buttons that when interacted with executes some logic. An example of using   the observer pattern
</p>
<br/>

Being aware of such design patterns are useful because it allows us to quickly find a solution that is known to be working instead of wasting time trying to come up with a solution that may already exist. This further helps us because these known solutions result in less complication later as many problems with the solution may have already been found and solved. It's also easier because if the solutions are already known, then it's easier to go to other people and say 'well I used this method to solve the problem' instead of having to spend time explaining a whole new idea.

However, these patterns are not always the answer to everything. If one blindly tries to use design patterns then they may end up in convoluted mess because they tried to implement a big system to a very small problem. The hard part of all of this is to figure out when it's best to use a design pattern and when it's best to just use a much simpler solution.
