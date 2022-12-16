# THE PRAGMATIC PROGRAMMER
Most of this tips has been extracted from the book "The Pragmatic Programmer: From Journeyman to Master" .

### 1. Care About Your Craft
Why spend your life developing software unless you care about doing it well?

### 2. Think! About Your Work
Turn off the autopilot and take control. Constantly critique and appraise your work.

## A Pragmatic Philosophy
#### 3. Provide Options, Don’t Make Lame Excuses
Instead of excuses, provide options. Don’t say it can’t be done; explain what can be done.
### 4. Don’t Live with Broken Windows
Fix bad designs, wrong decisions, and poor code when you see them.
### 5. Be a Catalyst for Change
You can’t force change on people. Instead, show them how the future might be and help them participate in creating it.
### 6. Remember the Big Picture
Constantly review the project, look out for the big pig picture, things can deteriorate pretty fast
### 7. Make Quality a Requirements Issue
Involve your users in determining the project’s real quality requirements.
### 8. Invest Regularly in Your Knowledge Portfolio
Make learning a habit.
### 9. Critically Analyze What You Read and Hear
Don’t be swayed by vendors, media hype, or dogma. Analyze information in terms of you and your project.
### 10. It’s Both What You Say and the Way You Say It
There’s no point in having great ideas if you don’t communicate them effectively.

>## A Pragmatic Approach
### 12. Good Design Is Easier to Change Than Bad Design
A thing is well designed if it adapts to the people who use it. For code, that means it must adapt by changing.

![](img/goodDesign.PNG)
### 13. DRY—Don't Repeat Yourself
Every piece of knowledge must have a single, unambiguous, authoritative representation within a system.
### 14. Make It Easy to Reuse
If it’s easy to reuse, people will. Create an environment that supports reuse.
### 15. Eliminate Effects Between Unrelated Things
Design components that are self-contained, independent, and have a single, well-defined purpose.
### 16. There Are No Final Decisions
No decision is cast in stone. Instead, consider each as being written in the sand at the beach, and plan for change.
### 17. Choose architectures based on fundamentals, not fashion.
Yesterday’s Best Practice Becomes Tomorrow’s Antipattern.
### 19. Prototype to Learn
Prototyping is a learning experience. Its value lies not in the code you produce, but in the lessons you learn.
### 20. Program Close to the Problem Domain
Design and code in the language of the problem domain.


>## The Basic Tools
### 21. Use the Power of Command Shells
Use the shell when graphical user interfaces don’t cut it.
### 22. Achieve Editor Fluency
An editor is your most important tool. Know how to make it do what you need, quickly and accurately.
### 23. Always Use Version Control
Version control is a time machine for your work; you can go back.
### 24. Fix the Problem, Not the Blame
It doesn’t really matter whether the bug is your fault or someone else’s—it is still your problem, and it still needs to be fixed.
### 25. Failing Test Before Fixing Code
Create a focussed test that reveals the bug before you try fixing it.
### 26. Read the Damn Error Message
Most exceptions tell both what failed and where it failed.
### 27. “select” Isn't Broken
It is rare to find a bug in the OS or the compiler, or even a third-party product or library. The bug is most likely in the application.
### 28. Don’t Assume It—Prove It
Prove your assumptions in the actual environment—with real data and boundary conditions.


>## Pragmatic Paranoia
### 29. You Can’t Write Perfect Software
Software can’t be perfect. Protect your code and users from the inevitable errors.
### 30. Crash Early
A dead program normally does a lot less damage than a crippled one.
### 31. Use Assertions to Prevent the Impossible
If it can’t happen, use assertions to ensure that it won’t. Assertions validate your assumptions.
### 32. Take Small Steps—Always
Small steps always; check the feedback; and adjust before proceeding.
### 33. Avoid Fortune-Telling
Only look ahead as far as you can see.
### 34. Listen to Your Inner Lizard
When it feels like your code is pushing back, it’s really your subconscious trying to tell you something’s wrong.

>## Bend or Break
### 35. Decoupled Code Is Easier to Change
Coupling ties things together, so that it’s harder to change just one thing.
### 36. Tell, Don’t Ask
Don’t get values from an object, transform them, and then stick them back. Make the object do the work.
### 37. Don’t Chain Method Calls
Try not to have more than one dot when you access something.
### 38. Avoid Global Data
It’s like adding an extra parameter to every method. If It’s Important Enough To Be Global, Wrap It in an API
### 39. Programming Is About Code, But Programs Are About Data
All programs transform data, converting an input into an output. Start designing using transformations.
### 40. Don’t Hoard State; Pass It Around
Don’t hang on to data within a function or module. Take one down and pass it around.
### 41. Don't Pay Inheritance Tax
Consider alternatives that better fit your needs, such as interfaces, delegation, or mixins
### 42. Prefer Interfaces to Express Polymorphism
Interfaces make polymorphism explicit without the coupling introduced by inheritance.
### 43. Use Mixins to Share Functionality
Mixins add functionality to classes without the inheritance tax. Combine with interfaces for painless polymorphism.
### 44. Parameterize Your App Using External Configuration
When you application will run in different environments, and potentially for different customers, keep the environment and customer specific values outside the app.
### 45. Analyze Workflow to Improve Concurrency
Exploit concurrency in your user’s workflow.
### 46. Shared State Is Incorrect State
Shared state opens a large can of worms that can often only be fixed by rebooting.
### 47. Use Actors For Concurrency Without Shared State
Use Actors to manage concurrent state without explicit synchronization.


>## While You Are Coding
### 48. Don’t Program by Coincidence
Beware of accidental complexity, and don’t confuse a happy coincidence with a purposeful plan.
### 49. Refactor Early, Refactor Often
Fix the root of the problem.
### 50. Testing Is Not About Finding Bugs
A test is a perspective into your code, and gives you feedback about its design, api, and coupling.
### 51. A Test Is the First User of Your Code
Use its feedback to guide what you do.
### 52. Build End-To-End, Not Top-Down or Bottom Up
Build small pieces of end-to-end functionality, learning about the problem as you go.
### 53. Design to Test
Start thinking about testing before you write a line of code.
### 54. Test Your Software, or Your Users Will
Test ruthlessly. Don’t make your users find bugs for you.
### 55. Keep It Simple and Minimize Attack Surfaces
Complex code creates a breeding ground for bugs and opportunities for attackers to exploit.
### 56. Apply Security Patches Quickly
Attackers deploy exploits as quick as they can, you have to be quicker.
### 57. Name Well; Rename When Needed
Name to express your intent to readers, and rename as soon as that intent shifts.
![alt text](img/naming.PNG)


>## Before the Project
### 58. No One Knows Exactly What They Want
They might know a general direction, but they won’t know the twists and turns.
### 59. Programmers Help People Understand What They Want
Software development is an act of co-creation between users and programmers.
### 60. Requirements Are Learned in a Feedback Loop
Understanding requirements requires exploration and feedback, so the consequences of decisions can be used to refine the initial ideas.
### 61. Work with a User to Think Like a User
It’s the best way to gain insight into how the system will really be used.
### 62. Policy Is Metadata
Don’t hardcode policy into a system; instead express it as metadata used by the system.
### 63. Use a Project Glossary
Create and maintain a single source of all the specific terms and vocabulary for a project.
### 64. Don’t Think Outside the Box—Find the Box
When faced with an impossible problem, identify the real constraints. Ask yourself: “Does it have to be done this way? Does it have to be done at all?”
### 65. Don't Go into the Code Alone
Programming can be difficult and demanding. Take a friend with you.
### 66. Maintain Small Stable Teams
Teams should be small and stable, where everyone trusts each other and depends on each other.
### 67. Organize Fully Functional Teams
Organize Around Functionality, Not Job Functions. Don’t separate UI/UX designers from coders, frontend from backend, testers from data modelers, design from deployment. Build teams so you can build code end-to-end, incrementally and iteratively.
### 68. Do What Works, Not What’s Fashionable
Don’t adopt a development method or technique just because other companies are doing it. Adopt what works for your team, in your context.
### 69. Deliver When Users Need It
Don’t wait weeks or months to deliver just because your process demands it.
### 70. Use Version Control to Drive Builds, Tests, and Releases
Use commits or pushes to trigger builds, tests, releases. Use a version control tag to deploy to production.

>## Pragmatic Projects
### 71. Test Early, Test Often, Test Automatically
Tests that run with every build are much more effective than test plans that sit on a shelf.
### 72. Coding Ain’t Done ’Til All the Tests Run
### 73. Test State Coverage, Not Code Coverage
Identify and test significant program states. Testing just lines of code isn’t enough.
### 74. Find Bugs Once
Once a human tester finds a bug, it should be the last time a human tester finds that bug. Automatic tests should check for it from then on.
### 75. Don't Use Manual Procedures
A computer will execute the same instructions, in the same order, time after time.
### 76. Delight Users, Don’t Just Deliver Code
Develop solutions that produce business value for your users and delight them every day.
