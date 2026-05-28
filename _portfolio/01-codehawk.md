---
title: "CodeHawk"
excerpt: "Web-based automated grading platform for programming courses with instant feedback, plagiarism detection, and LMS integration."
collection: portfolio
---

CodeHawk is an automated grading platform designed for university programming courses. Students submit Python code, which is executed in a sandboxed environment with a 10-second timeout. The system runs test cases, scores submissions against weighted rubrics, and returns instant feedback. Faculty and TAs manage assignments and review grades through a role-scoped dashboard.

Additional features include AI-generated code detection, plagiarism checking, and grade export compatible with Canvas and other LMS platforms.

The platform was deployed and live, but has since been shut down to be transferred to the university's EC2 instance so the department can host and maintain it internally.

**Tech Stack:** Next.js, React, TailwindCSS, Spring Boot (Java 17), MySQL, Python (sandboxed execution)

[View on GitHub](https://github.com/Parker-Story/CodeHawk-ULM)
