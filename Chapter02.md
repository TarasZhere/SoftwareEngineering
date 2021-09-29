# Chapter 2

### Some realities about software development

1. Effort needs to be made to understand the problem
2. Design is central and essential
3. Software shoud show good quality
4. Software should be mantainable

### The seminal definition:

> Software engineering is the establishment and use of sound engineering principles in order to obtain economically software that is reliable and works efficiently on real machines.

### IEEE definition

-   Software Enginering:
    1. Application of a systematic, disciplined, quantifiable approach to the development, operation, and maintenance of software: that is, the application of engineering to software.
    2. Study the approach as in (1)

### Layered Technology

![Layered technology](./assets/img1.png)

### Process framework

Overview:

-   Framework activities:
    -   work task
    -   work products
    -   milestone & deliverables
    -   QA checkpoints
-   Umbrella Activities

### Framework activities Depth

1. Communication
2. Planning
3. Modeling
    - Analysis of requirements
    - Design
4. Construction
    - Code generation
    - Testing
5. Deployement

### Umbrella Activities Depth

-   Software project tracking and control
-   Risk management
-   Software quality assurance
-   Technical reviews
-   Measurement
-   Software configuration management
-   Reusability management
-   Work product preparation and production

### Adapting a process model

A process model influences:

-   flow of activities, action, and task
-   degree to which actions and task are defined within each framework activity (Communication, Planning, ...)
-   work progress that are identified and requierd
-   manner [1] which quality assurance activities are applied
-   manner in which project tracking and conrfol activites are applied
-   precision in the documentation (details and rigor)
-   degree which the the customers and stake holders are involved
-   the level of autonomy given to the software team
-   degree to which team organization and roles are prescribed

[1]: intended as a way in which a thing is done or happens.

Polya suggestes:

1. Understand the problem (communication and analisis)
2. Plan a solution (modeling and software design)
3. Carry out the plan (Code)
4. Examine the result for accuracy (testing and quality)

### How to understand the problem

-   **Who has a stake in the solution to the problem?** Who are the stakeholders
-   **What are the unknowns** What are the required data or functions
-   **Can the problem be divided into smaller problems** Divide and conquer
-   **Can the problem be represented graphically?** analysis model

### How to plan a solution

-   **Any similar problems** Recognize similar patters. Is that a usable software
-   **Has it been solved?** Are elements of the solution reusable?
-   **Can sub problems be defined** Are smaller problems easy to find a solution
-   **Can represend a solution that leades to an effective implementation?** Design model created visually

### Carry out the plan

-   **Does the solution conform to the plan?** Is source code traceable to the design model?
-   **Is each component part of the solution provably correct?** Has the design and code been reviewed, or better, have correctness proofs been applied to algorithm?

### Examine the result

-   **Is it possible to test each component part of the solution?**
-   **Does the solution produce result required?**

### Hooker's General Principles

1. The reason it all exist
2. Keep it super simple (KISS)
3. Mantain the vision
4. What you produce, others will consume
5. Be open to the future
6. Plan ahead for reuse
7. Think a lot before!
