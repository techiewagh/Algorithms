# Algorithms

Starting to Code
----------------
- Good style to write code
- Use clear variable names
x Avoid names that are single letters, unless they are for iteration.
- On whiteboard use concise names, verbose variable names
- Talk about high level code design, explain why it is written as such and what it is trying to achieve.

After coding
------------
x Don’t immediately announce done.
- Fix bugs or syntax errors.
- Look at code as if it was written by someone else.
- Review and fix any issues you may find.
- small test cases and step through code
- emulating a debugger, Jot own or tell values of certain variables.
- time and space complexities of your code, explain why.
- Explain any tradeoffs in current approach.
- Think Big <Large Scale input/what if input can’t be fit into memory>
     >> answer is usually a divide-and-conquer approach —
        perform distributed processing of the data and only read certain chunks
        of the input from disk into memory, write the output back to disk and combine them later

Practice with Mock Interviews
Practical Tips
--------------
Have more techniques in your arsenal.
1. Always validate input first, check for invalid, empty, negative or different.
2. Never assume you are given valid parameters.
3. Alternatively clarify with the interviewer whether you can assume valid input.
4. Check for time and space complexity requirement or constraints.
5. Use a mix of functional and imperative programming paradigms:
     - Write pure functions as often as possible.
     - Use pure functions because they are easier to reason with and can help reduce bugs in your implementation.
     - Avoid mutating the parameters passed into your function, especially if they are passed by reference,
       unless you are sure of what you are doing.
     - Achieve a balance between accuracy and efficiency. Use the right amount of functional and imperative code where appropriate.
       Functional programming is usually expensive in terms of space complexity because of non-mutation and the repeated allocation of new objects.
       On the other hand, imperative code is faster because you operate on existing objects.
     - Avoid relying on mutating global variables. Global variables introduce state.
     - Make sure that you do not accidentally mutate global variables, especially if you have to rely on them.
6. To improve speed of a program, choose appropriate DS/Algo or use more memory. Classic space and time trade off.
7. Know the strengths of each data structure and the time complexity for its various operations.
8. Data structures can be augmented ( having been made greater in size/value ) to achieve efficient time complexity across different operations.
     - For example, a HashMap can be used together with a doubly-linked list to achieve O(1)
       time complexity for both the get and put operation in an LRU cache.
