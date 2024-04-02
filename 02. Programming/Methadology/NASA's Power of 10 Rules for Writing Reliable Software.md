# Ref
- https://www.youtube.com/watch?v=GWYhtksrmhE

# Introduction
- NASA has a set of rules, known as the Power of 10, which are designed to ensure the reliability and safety of software used in space missions. These rules are derived from a set of 10 rules aimed at making code easy to statically analyze, and they are particularly important for extreme safety scenarios.

# Main Content
- NASA restricts code to **simple control flow** constructs and does not use go to statements, set jump, long jump, or recursion. This ensures that the code is easy to follow and avoids the risk of crashes, especially in embedded systems.
- **All loops are given a fixed upper bound** to prevent runaway code, and all loops are bound by a hard upper limit represented as an integer, not as a pointer end case.
- NASA recommends **not using the Heap at all**; instead, exclusively use stack memory to predict exactly how much memory a program will use. This eliminates use after freeze and memory leaks.
- **Functions** are kept relatively small (**no longer than 60 lines** or about the size of a piece of paper) to ensure readability, testability, and clear purpose.
- **Variables are declared at the lowest scope possible**, reducing the potential for error and making debugging easier.
- **All return values for non-void functions are checked**, and if ignored, they are explicitly cast to a void type to ensure code reliability.
- NASA limits the use of the C preprocessor to file inclusions and very simple conditional macros to avoid code obfuscation and maintain clarity.
- **Pointers are restricted to be dereferenced only one layer at a time**, and the use of function pointers is also limited to maintain code clarity and ease of static analysis.
- Code should be** compiled with all warnings enabled and in pedantic mode**, and it should be analyzed using multiple static code analyzers with different rule sets. Additionally, the code should be unit tested thoroughly.

# Conclusion
- NASA's Power of 10 rules provide essential guidelines for writing reliable and safe software, particularly in critical environments such as space missions. By adhering to these rules, developers can significantly reduce the risk of code-related issues and ensure the safety and reliability of their software.

# Additional Notes
- These rules embody best practices for writing code that is inherently reliable, testable, and clear in its purpose, making it an invaluable resource for software development in safety-critical applications. 
# #AI-Generated