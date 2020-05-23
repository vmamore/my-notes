# Does TDD Really lead to good design?
#### Notes about -> https://www.youtube.com/watch?v=KyFVA4Spcgg
<!-- TOC -->
- TDD Flow:
    - Red -> Green -> Refactoring
    - Red: specify what you want the code to do.
    - Green: Make it work.
    - Refactoring: Make it better.
    - Small increments, safe steps.

- Software Development WorkFlow:

- If the TDD style is not suitable with what you're building, you're going to have problems.

- Approaches:
    - Classicist Approach (Chiacago School):
        - Do the simplest thing to go from Red to Green (Duplicate, hardcode...), refactor in the end.
          Design occurs in the end (Emergent design).
        - When to use this approach? Explore.
        
    - OutsideIn Approach (London School):

- 4RSD (4 Rules of Simple Design):
    - Pass all the tests.
    - Review intentions.
    - No duplication.
    - Fewer elements.