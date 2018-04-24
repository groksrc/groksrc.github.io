## Background
I’ve worked in a lot of different engineering environments over the course of my career and one thing that always comes up as the team grows is how to handle documentation. At a certain point you just can’t scale effectively without it.

So then the question automatically becomes, “Who is going to write it?” In some places I’ve worked this question goes unanswered. That's unfortunate because now the ticketing system winds up as the default documentation center. This is problematic for a number of reasons, but more importantly the team suffers as a result.

## Technical Writers
Often the suggestion is made to hire a technical writer. Engineering time is valuable so why waste it on mundane tasks? Someone with experience writing good documentation will surely be able to produce high quality documentation that normal human beings can read. Right? Not so fast..

Technical writers can most certainly produce quality content. That's not an issue. But experience tells us that the content they produce can vary significantly based on how they understand the systems they are documenting and who is available to provide color commentary about what is going on.

In many cases having good documentation is not simply about users being able to access a set of instructions about how to use the software. The best documentation covers things like special conditions, potential problem areas and mediations, and background information on why the system is designed in the way that it is.

And how could a Technical Writer ever get any of that information by only looking at the screens of the software? More often than not, the software engineers are the only people in the room who know what is really going on under the hood.

Aside from that, if you think about the responsibilities of a Technical Writer we realize that they cover a lot more than just producing standard documentation for the system. They also need to format, publish, and version the documentation which can be a huge task in and of itself.

## Why Software Engineers Should Write Documentation
In an ideal world the Technical Writer on your team is not the author. They are the editor and the engineers are authors. Technical Writers can help guide us to publication, much like would happen when writing a book. But as software engineers we have the most in-depth knowledge about the systems we develop and often times can do the best job of explaining the details about how things actually work.

But wait! I can already hear some of you grumbling about how documentation is boring or that nobody reads it and that it's a waste of time. Well, if you've made it this far it's probably safe to assume that you have at least some passing interest in this topic. Maybe you're challenged by it too? Then why not become part of the solution?

I posit that software engineers are authors, but instead of limiting ourselves to writing code we should open ourselves to authoring all types of documents. The best engineers I know are also very keen on this point. If you've mastered writing code and tests, documentation is your next challenge.

## How To Write Good Documentation In 5 Minutes Or Less
It's more easy than you realize to write good documentation. You do it every day, you just don't recognize it as such. And the documentation you do write remains "stuck" where you wrote it: in the code. Here are 3 easy steps to break that documentation log jam.

### 1. Start a docs folder
The docs folder can live in your project repo or somewhere else. Just make sure it's easy for everyone else to get to it. Inside the folder I recommend vanilla markdown unless it's hosted and provides its own formatting. You could even use [Jekyll](http://jekyllrb.com) if you wanted. The key is that there's low friction to getting into the documentation and working with it.

### 2. Start An Outline
When you're ready to start a new page of documentation create an empty file and start with a title and some headings. Here's an example of how I did this very thing when writing this article:

<pre>
Software Engineers Are Authors

## Background
## Technical Writers
## How To Write Good Documentation
</pre>

If you've ever used GitHub's `hub` [utility](https://github.com/github/hub), this should be familiar. Like when you use `$ hub pull-request`, the first line of the document is the title, followed by an empty line. Anything after that is the body content. In the body use markdown headings an write an outline that covers just the main topics of what this feature does. The names of your public methods are good starting points.

### 3. Start A Loop
Any time you're stuck waiting on a task is a good time to loop into the docs and add flesh to your outline. It's this simple step that really makes the difference because you're now slowly adding to a critical component of the software that is often overlooked. If you're stuck waiting on a synchronous operation, go async. It will make you more efficient and your Technical Writer will thank you.

## You + Your Technical Writer = #winning
If you've done all of this, now your Technical Writer has awesome source material for coloring the documentation they create. If you don't have a Technical Writer yet you'll be prepared with some basic content for when they arrive. Either way it's a win/win.

## ProTip: For When You Don't Like Longform Entry
Speach to text is actually pretty good now. Using a dictation app can save loads of typing and speaking is typically faster than typing anyway. If you have a lot of content but don't want to bother typing it all out give this a try. You might be surprised at how well it works.
