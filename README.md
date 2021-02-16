# The_Pragmatic_Programmer

## Quotes
> 1. The pragmatic programmer don't shirk from responsability. Instead, we rejoice in accepting challenges and in making our expertise well known. If we are responsible for a design, or a piece of code, we do a job we can be proud of.

> 2. An investment in knowledge always pays the best interest. Benjamin Franklin

> 3. If all the routines preconditions are met by the caller, the routine shall guarantee that all postconditions and invariants will be true when it completes.

> 4. So next time something seems to work, but you don't know why, make sure it isn't a coincidence.

> 5. No one size fits all.

## Abreviations to remember
1. ETC: Easier to Change
2. DRY: Don't Repeat Yourself

## Technical Advices
1. Orthogonality: easy to design, build, test and extend.
2. Make it easy to Reuse.
3. Look for the areas where you have doubts and where you see the biggest risks. Then prioritize your development so that these are the first areas you code.
4. Estimating: Choose the units of your answer to reflect the accuracy you intend to convey
   - The first part of any estimation exercise is building an understanding of what's being asked.
   - Build a rough-and-ready mental model.
   - Break the model into componenets.
   - Give each parameter a value.
   - Calculate the answer.
   - Keep track of your estimating progress.
5. Try keeping an engineering daybook.
6. Whenever you find yourself thinking 'but of course that could never happen' add code to check it.
7. Thinking of code as a serie of (nested) transformations can be liberating approach to programming.
8. When code relies on values that may change after the application gone live, keep those values external to the app. Common things that you will probably want to put in configuration data include:
   - Credentials for external services.
   - Logging levels and destinations.
   - Port, IP address, machine, and cluster names the app uses.
   - Environment-specific validation parameters.
9. Remeber the distinction: concurrency is a software mechanism, and parallelism is a hardware concern.
10. Shared state is incorrect state.
11. Concurrency in a shared resources environment is difficult, and managing it yourself is throught with challenges.
12. Whenever we write anything containing loops or recursive calls, we subconsciously check the runtime and memory requirements.
13. Big-O notation:
    - O(1): Constant (access element in array)
    - O(lng): Logarithmic (binary search)
    - O(n): Linear (sequential search)
    - O(nlgn): Worse than linear, but not much worse (quicksort)
    - O(n^2): Square law (selection and insertion sorts)
    - O(n^3): Cubic (multiplication of two n\*n matrices)
    - O(C^n): Exponential
14. Refactoring: Disciplined technique for restructuring an existing body of code, altering its internal structure without changing its external behavior.
15. You refactor when you have leraned something: when you understand something better than you did last year, yesterday, or even just ten minutes ago.
16. We believe that the major benefits of testing happen when you think about and write the test, not when you run them.
17. Unit test: testing done on each module, in isolaton, to verify it's behavior.
18. That's when programmers come in. Our job is to help understand what they want. In fact, that's probably our most valuable attribute.
19. When given something that seems simple, we annoy people by looking for edge cases and asking about them.
20. Agile Software Development:
    - **Individuals and Interactions** over processes and tools.
    - **Working software** over comprehensive documentation.
    - **Customer collaboration** over contract nogatiation.
    - **Responding to change** over following a plan.
21. The team works on more than just new features:
    - Old system maintenance.
    - Process Reflection and Refinement.
    - New tech experiments.
    - Learning and skill improvements.
22. Being able to deliver on demand does not mean you are forced to deliver every minute of every day. You deliver when users need it, when it makes business sense to do so.

## Personal Advices 
1. Your knowledge and experience are your most day-to-day professional assets.
2. Learn at least one language every year.
3. Read a technical book each mont.
4. Read a nontechnical books.
5. Take classes.
6. Participate in local users groups and meetings.
7. Experiment with different environments.
8. Stay current.
9. Much of the time, tomorrow looks a lot like today. But don't count on it.
10. Schedule it to make it happen.

## To-do
1. Building your portfolio
   - Invest regularly
   - Diversify
   - Manage risk
   - Buy low, sell high
   - Review and rebalance
2. The Pragmatic Starter Kit:
   - Version Control
   - Regresion Testing
   - Full Automation
