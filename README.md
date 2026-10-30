# Overview

This course is designed for Agentic Software Engineering in the School of Computer Science (CS3604) and Global College (CS4810) at Shanghai Jiao Tong University.

The course aims to help students understand the general workflow of software engineering and learn how to implement this workflow in an agentic manner. Rather than treating large language models merely as code-generation tools, the course emphasizes how software requirements, tests, code, version history, traceability, and deployment pipelines can be organized into an executable engineering workflow for agents.

Students will first experience how an agent can help build a minimum viable web system from requirements. As the system becomes more complex, the course will gradually introduce key software engineering mechanisms, including requirement engineering, test-driven development, version control, traceability, software testing, software evolution, and continuous integration/deployment. By the end of the course, students are expected to transform a non-trivial requirement document into a runnable, testable, traceable, and evolvable web system with agentic workflows.

# Outline

1. **Agentic Software Engineering and Requirement Compilation**:
This lecture introduces why software engineering is more than programming, especially in the era of large language models. Students will learn the motivation of agentic software engineering and understand how agents can be used to automate different stages of the software engineering workflow.
The lecture also introduces the concept of Requirement Compilation, namely how human-written requirements can be transformed into executable software artifacts, including tests, code, documents, and traceability links.

- Lab: a visualized demo of requirement compilation [link todo]

3. **Building a Minimum Viable Web System**:
This lecture introduces the basic structure of a modern web system, including frontend, backend, database, and APIs. Instead of requiring students to master all implementation details from scratch, the course will provide a running example or starter system.
Students will use agents to understand, modify, and extend this system. The goal is to let students quickly experience how a non-trivial web system can be built or evolved from requirements with agentic assistance.

- Lab 1: SQL [link todo]
- Lab 2: Backend Programming [link todo]
- Lab 3: Frontend Programming [link todo]

4. **LLM, RAG, Tool Calling, and MCP**:
This lecture introduces the basic working principles of large language models and explains why hallucination occurs in software engineering tasks.
Students will learn how retrieval-augmented generation, enriched project context, tool calling, and MCP-style mechanisms can help agents interact with external tools, code repositories, testing frameworks, databases, and development environments. The focus is not only on using LLMs, but also on designing reliable agentic workflows around them.

- Lab 1: LLM call [link todo]
- Lab 2: tool call and MCP [link todo]
- Lab 3: GUI testing  [link todo]
- Lab 4: TDD and feedback-based loop engineering [link todo]
- Lab 5: token consumption [link todo]


5. **Requirement Compilation and Traceability**:
This lecture introduces how to enhance the requirement compilation workflow by incorporating Git and software traceability.
Students will learn how to connect requirements, tests, code changes, commits, and system behaviors. The goal is to make agentic development more controllable, inspectable, and evolvable, so that each code change can be traced back to its corresponding requirement and validation evidence.
A mid-term presentation will be arranged around this stage. Students are expected to demonstrate their preliminary system and explain how requirements, tests, code changes, and agent interactions are organized.

- Lab : minimum requirement compiler [link todo]

6. **Software Testing**:
This lecture introduces fundamental software testing techniques, including black-box testing, white-box testing, unit testing, integration testing, API testing, GUI testing, and regression testing.
Students will learn how testing supports agentic software engineering by detecting hallucinated code, unintended behavior, regression bugs, and incomplete implementations.

- Lab : coverage-based testing [link todo]

7. **Software Evolution**:
This lecture introduces how Git works and why version control is essential for software engineering.
Students will learn the concepts of repository, commit, branch, merge, conflict, issue, pull request, and code review. The lecture emphasizes that Git is not only a collaboration tool, but also a foundation for tracking agentic software evolution.

This lecture introduces continuous integration and deployment, with practical facilities such as GitHub Actions.
Students will learn how automated checks can detect erroneous commits, how tests can be integrated into the development pipeline, and how a system can be deployed and updated continuously. The lecture emphasizes the role of CI/CD as an execution environment for reliable agentic software engineering.

- Lab 1: Git operations [link todo]
- Lab 2: CI/CD operations [link todo]
- Lab 3: incremental requirement compiler [link todo]



