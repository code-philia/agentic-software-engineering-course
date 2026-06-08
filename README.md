# Overview

This course is designed for Agentic Software Engineering in the School of Computer Science (CS3604) and Global College (CS4810) at Shanghai Jiao Tong University.

The course aims to help students understand the general workflow of software engineering and learn how to implement this workflow in an agentic manner. Rather than treating large language models merely as code-generation tools, the course emphasizes how software requirements, tests, code, version history, traceability, and deployment pipelines can be organized into an executable engineering workflow for agents.

Students will first experience how an agent can help build a minimum viable web system from requirements. As the system becomes more complex, the course will gradually introduce key software engineering mechanisms, including requirement engineering, test-driven development, version control, traceability, software testing, software evolution, and continuous integration/deployment. By the end of the course, students are expected to transform a non-trivial requirement document into a runnable, testable, traceable, and evolvable web system with agentic workflows.

# Outline

1. **Agentic Software Engineering and Requirement Compilation**:
This lecture introduces why software engineering is more than programming, especially in the era of large language models. Students will learn the motivation of agentic software engineering and understand how agents can be used to automate different stages of the software engineering workflow.
The lecture also introduces the concept of Requirement Compilation, namely how human-written requirements can be transformed into executable software artifacts, including tests, code, documents, and traceability links.

2. **Building a Minimum Viable Web System**:
This lecture introduces the basic structure of a modern web system, including frontend, backend, database, and APIs. Instead of requiring students to master all implementation details from scratch, the course will provide a running example or starter system.
Students will use agents to understand, modify, and extend this system. The goal is to let students quickly experience how a non-trivial web system can be built or evolved from requirements with agentic assistance.

3. **LLM, RAG, Tool Calling, and MCP**:
This lecture introduces the basic working principles of large language models and explains why hallucination occurs in software engineering tasks.
Students will learn how retrieval-augmented generation, enriched project context, tool calling, and MCP-style mechanisms can help agents interact with external tools, code repositories, testing frameworks, databases, and development environments. The focus is not only on using LLMs, but also on designing reliable agentic workflows around them.

4. **Requirement Engineering and Test-Driven Development**:
This lecture introduces how to write sufficient and precise software requirements, not only for human developers but also for agents; and test-driven development and discusses how requirements can be compiled into executable tests.
Students will learn how to identify ambiguity, incompleteness, inconsistency, and missing constraints in natural language requirements. They will also learn how to transform informal requirements into structured artifacts, such as user stories, scenarios, acceptance criteria, and agent-readable requirement documents.
Students will also learn how to generate acceptance tests, API tests, and end-to-end tests from requirements. The lecture emphasizes that tests are not merely post-hoc validation tools; they can also serve as executable specifications that guide agentic code generation and repair.

5. **Version Control System (Git)**:
This lecture introduces how Git works and why version control is essential for software engineering.
Students will learn the concepts of repository, commit, branch, merge, conflict, issue, pull request, and code review. The lecture emphasizes that Git is not only a collaboration tool, but also a foundation for tracking agentic software evolution.

6. **Requirement Compilation and Traceability**:
This lecture introduces how to enhance the requirement compilation workflow by incorporating Git and software traceability.
Students will learn how to connect requirements, tests, code changes, commits, and system behaviors. The goal is to make agentic development more controllable, inspectable, and evolvable, so that each code change can be traced back to its corresponding requirement and validation evidence.
A mid-term presentation will be arranged around this stage. Students are expected to demonstrate their preliminary system and explain how requirements, tests, code changes, and agent interactions are organized.

7. **Software Testing**:
This lecture introduces fundamental software testing techniques, including black-box testing, white-box testing, unit testing, integration testing, API testing, GUI testing, and regression testing.
Students will learn how testing supports agentic software engineering by detecting hallucinated code, unintended behavior, regression bugs, and incomplete implementations.

8. **Software Evolution**:
This lecture introduces how software systems evolve when requirements change in a non-trivial way.
Students will learn how agentic requirement compilation can support feature enhancement, bug fixing, refactoring, regression prevention, and change impact analysis. The lecture emphasizes that the real challenge of agentic software engineering is not only to generate a system from scratch, but also to continuously evolve an existing system under engineering constraints.

9. **Continuous Integration and Deployment**:
This lecture introduces continuous integration and deployment, with practical facilities such as GitHub Actions.
Students will learn how automated checks can detect erroneous commits, how tests can be integrated into the development pipeline, and how a system can be deployed and updated continuously. The lecture emphasizes the role of CI/CD as an execution environment for reliable agentic software engineering.

10. **Practice (Feature Enhancement)**:
Students will implement a new feature in an existing system.
They are expected to update the requirement document, generate or revise tests, use agents to modify the system, inspect the code changes, run the test suite, and record the traceability between requirements, tests, code, and commits.

11. **Practice (Feature Enhancement)**:
Students will continue to enhance the system with a more complex feature.
Compared with the previous practice, this task may involve multiple components, such as frontend interaction, backend logic, database schema, API behavior, and regression tests. The goal is to help students experience how agentic workflows handle increasing system complexity.

12. **Practice (Testing, Debugging, and Repairing)**:
Students will be given an existing system with one or more defects.
They are expected to reproduce the bug, write or generate failing tests, use agents to localize the potential cause, repair the system, and validate the fix through regression testing. The focus is not only on fixing the bug, but also on building a disciplined agentic debugging and repair workflow.

13. **CA (Feature Enhancement, with score)**:
Students will complete a graded feature enhancement task.
They are expected to demonstrate their ability to use agentic workflows to understand requirements, modify an existing system, generate or update tests, manage code changes with Git, maintain traceability, and validate the system through CI.

In addition, we expect a mid-term presentation and final presentation during the course.


