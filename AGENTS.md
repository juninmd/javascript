```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure the consistent, high-quality, and maintainable development of the AGENTS repository. Adherence to these principles will be crucial for maximizing productivity and reducing future maintenance effort.

**1. DRY (Don't Repeat Yourself)**

*   **Single Responsibility Principle:** Each agent should have a clearly defined, single responsibility. Avoid creating agents with overlapping functionality.
*   **Code Reuse:** Strive to reuse existing components and logic whenever possible.  If reuse is required, clearly document the reuse.
*   **Abstraction:** Define abstract interfaces for agents and their components. This promotes flexibility and easier maintenance.
*   **Single Base Class:** If a class hierarchy is necessary, ensure it's designed for a specific use case and avoids unnecessary duplication.

**2. KISS (Keep It Simple, Stupid)**

*   **Minimal Code:**  Strive to write concise and understandable code.  Avoid overly complex logic.
*   **Simple Design:** Design agents with simple, understandable structures. Favor straightforward implementation over overly clever solutions.
*   **Clear Naming:** Use descriptive variable and function names.
*   **Comments:**  Provide concise, helpful comments where clarification is needed but avoid verbose explanations.

**3. SOLID Principles**

*   **Single Inheritance:** Limit inheritance to avoid tight coupling and maintainability issues.
*   **Open/Closed Principle:** Design agents in a way that allows adding new functionality without modifying existing code.  (Focus on interfaces, not concrete classes).
*   **Liskov Substitution Principle:**  Ensure that subclasses can be substituted for their base classes without affecting the correctness of the application.
*   **Interface Segregation Principle:**  Provide clients with only the interface they need, not unnecessary implementation details.

**4. YAGNI (You Aren't Gonna Need It)**

*   **Future-Proofing:**  Don't add functionality just because you *might* need it later.  Design for the expected future use cases.
*   **Avoid Over-Engineering:**  Don't prematurely add features that are not currently required.

**5. Development Workflow & Coding Standards**

*   **Version Control:** Use Git with a well-defined branching strategy.
*   **Code Style:**  Adhere to a consistent code style (e.g., using a linter like ESLint or Black).
*   **Testing:** Comprehensive unit and integration tests are *mandatory*. Mocking should be used sparingly and exclusively for testing purposes only.
*   **Code Review:**  All code changes should undergo thorough code review before merging.
*   **Documentation:**  Provide clear and concise documentation for all agent functions, classes, and modules.
*   **Error Handling:** Implement robust error handling and logging.
*   **Modularity:**  Each agent module should be self-contained and easily reusable in other agents or projects.
*   **Dependency Management:** Implement a dependency management system to track and manage external libraries and dependencies.
*   **Static Analysis:** Utilize static analysis tools to identify potential issues early in the development process.
*   **Code Formatting:**  Consistent code formatting using a tool like Prettier.

**6. File Size Constraints**

*   **Maximum File Size:** Each file must be less than 180 lines of code.  (Adjust as needed based on project size)

**7. Test Coverage Requirements**

*   **Minimum Coverage:** 80% of the code must be covered by tests.
*   **Test Case Design:** Tests must be designed to cover critical functionality and edge cases.
*   **Test Data:** Use realistic and relevant test data.
*   **Test Driven Development:** Implement testing in a way that tests drive the development process.

**8. Code Structure & Organization**

*   **Modular Design:** All agents should be modular and easily expandable.
*   **Clear Module Boundaries:**  Each module should have a well-defined purpose and interface.
*   **Logical Grouping:** Group related functions and classes together.

**9.  Specific Considerations (Adapt as needed):**

*   [Specify any other key considerations relevant to the AGENTS.md project, e.g., specific data structures, API endpoints, or architectural patterns.]


These guidelines are intended as a starting point and may require adjustments based on project specific needs and evolving best practices.  Regularly review and update these guidelines to maintain code quality.
```