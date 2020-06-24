<a href="https://drews.tips">home</a>

Alright, we've got our goals:
1. Complete 1-3 tasks/week for the first 30 days.</li>
2. Ask for help sooner rather than later (more of a rule than a goal, but that's ok!)</li>
3. Schedule meetings with existing team members to get a high-level
understanding of the architecture and design of the system within the next week.

Let's dive into the next step on the worksheet:

1. What's your goal?
2. **What materials are you going to use to achieve that goal?**
3. How have others achieved this goal?
4. How best can you simulate part (or all) of what you want to be able to do?
5. How much time and how often are you going to work on achieving this goal?
6. How will you receive feedback?
7. How will you incorporate feedback into your work?

This one's a little more straightforward than the first step. We just need
to compile a list of learning materials and resources based on our goals.

For the first goal, I just googled "How to learn a new codebase" and compiled
the sources. Here are the main results:

From https://dev.to/perigk/how-to-get-familiar-with-a-new-codebase-i9f:
* Read the documentation available, the first thing
* Build the software and use it as an end user would do
* Read the automation tests to get a first dive
* Read the actual business logic and make diagrams out of your understanding
* Trace the full process of each slice in detail
* Move to another slice of functionality, once confident
* Add some value to the system, by contributing to it with a bug fix or a new small feature


From https://simpleprogrammer.com/master-new-codebase-record-time/:
* Discover the toolchain and processes used to build the project by examining the build scripts.
* If possible, play with the product itself once you’ve built it to see what it does.
* Look at the libraries that the project depends on to determine what services and systems the product uses and depends on.
* Use UML diagram generating tools to create class and sequence diagrams for all, or part, of your project.
* Create sequence diagrams by hand as you read through the code.
* Investigate how the product is deployed on hardware by looking at deployment scripts (like Capistrano) or documentation.
* Look through how the project is laid out in the filesystem as well as how classes are grouped in packages or namespaces to help uncover the architecture.
* Use a small feature or low-priority bug as a way to get your feet wet in the code and start understanding what the code really does. Document anything interesting you find that might help future developers understand the project faster.

https://softwareengineering.stackexchange.com/questions/6395/how-do-you-dive-into-large-code-bases:
* Debug and walk through the code, following user-type interaction in the code to see how things flow

And:
1. Try to find out what the code is supposed to do, in business terms.
2. Read all the documentation that exists, no matter how bad it is.
3. Talk to anyone who might know something about the code.
4. Step through the code in the debugger.
5. Introduce small changes and see what breaks.
6. Make small changes to the code to make it clearer.
Some of the things I do to clarify code are:
1. Run a code prettifier to format the code nicely.
2. Add comments to explain what I think it might do
3. Change variable names to make them clearer (using a refactoring tool)
4. Using a tool that highlights all the uses of a particular symbol
5. Reducing clutter in the code - commented out code, meaningless comments, pointless variable initializations and so forth.
6. Change the code to use current code conventions (again using refactoring tools)
7. Start to extract functionality into meaningful routines
8. Start to add tests where possible (not often possible)
9. Get rid of magic numbers
10. Reducing duplication where possible

https://www.quora.com/How-do-you-go-about-learning-a-new-code-base
- Just start fixing bugs

https://hackernoon.com/how-to-learn-an-existing-code-base-28b88d954bfd
- Top-down
- Bottom-up
- Mix of the 2

I'm seeing 2 large trends from all the articles: reading/studying and working.
Like I covered in a previous post about false learning idols ##link, I'm always
wary when someone recommends a potential idol and not action. Like I said there,
you can read about running all you want, but eventually you're going to have
to put on the shoes and start moving. I'm not saying to avoid all courses and
books, just that taking in new information in any form should support the work
not be the goal in and of itself.

**I recommend 80-90% of your learning
should be hands on. That leaves 10-20% for reading and watching.**

It may seem like a
strange mix, especially to false-idol worshippers, but actually making use of
newly-learned materials is much more difficult than just finishing a chapter. If
you want to take in and keep what you're learning, you need
to put it into action. You're going to feel uncomfortable and like you don't
know what you're doing, but experience is the best teacher. So, read/watch
something interesting, and then dive into the work. Start testing your understanding,
start explaining to understand ##link, get a mock interview, make a presentation
teaching the new materials to some. _Do_ something with the information.

The first goal was the biggie, and the second two are a guideline and a step,
so I'm feeling good to go for my main goal: knocking out 1-3 tasks/week for my
first month on the team and taking in architecture and design info from existing
team members.
