# Crafting User-Centric Software with Design Patterns & Best Practices

#### User Stories: The Heart of Agile Development

Purpose: User stories capture the desired behavior of an application from the user's perspective.
Format: Concise sentences (e.g., "As a [user role], I want [goal] so that [benefit].").
Tools: 3x5 index cards or online trackers like Pivotal.
Benefits:
Focus on user needs, not implementation details.
Facilitate collaboration and prioritization.
Serve as the basis for acceptance tests.
SMART User Stories:

##### User stories should be:

Specific
Measurable
Achievable
Relevant
Timeboxed
Example:

"As an e-commerce website user, I want to log in easily so that I can complete my purchase quickly. The login UI should be so intuitive that 80% of customers can log in within 20 seconds."

From BDD to Acceptance Tests with Cucumber and Capybara:

Cucumber: A tool that allows you to write acceptance tests in plain language (Gherkin).
Capybara: A library that simulates user interactions with web applications.
Example Test:
Gherkin
Scenario: Add item to cart
    Given I am on the product detail page for "Ready Player One"
    When I click the "Add to Cart" button
    Then the novel "Ready Player One" should be in my cart
Use code with caution.
content_copy
Capybara: A powerful tool for automating browser interactions, making it easier to write robust acceptance tests.

Happy Path vs. Sad Path Testing:

Happy Path: Tests the expected, successful flow of user interactions.
Sad Path: Tests how the application handles errors, unexpected input, or edge cases.
Best Practices for Step Definitions:

Generalize step definitions whenever possible to promote reusability.
Use capture groups in matchers to extract values and assign them to variables.
Design Patterns: Building Blocks for Software Architecture

#### What Are They? Reusable solutions to common software design problems.
Benefits: Promote code reuse, maintainability, and flexibility.
Types: Creational, Structural, Behavioral.
Unified Modeling Language (UML) and Class Diagrams:


#### UML:
UML: A visual language for modeling software systems.
Class Diagrams: Used to represent the structure of a system's classes, their attributes, methods, and relationships.
LCOM (Lack of Cohesion of Methods): A metric used to measure the degree to which a class's methods are related to each other.

Open-Closed Principle:  Classes should be open for extension but closed for modification, meaning you can add new functionality without changing existing code.

Dependency Injection:  A technique for decoupling objects by injecting their dependencies from external sources, promoting flexibility and testability.

Demeter's Law (Principle of Least Knowledge): An object should only talk to its immediate neighbors, not to distant objects, to reduce coupling and increase maintainability.

Plan-and-Document Perspective on Design Patterns:

In a Plan-and-Document lifecycle, design patterns are typically chosen and documented during the design phase. They provide a shared vocabulary for designers and developers and can help ensure that the software is well-structured and maintainable.
