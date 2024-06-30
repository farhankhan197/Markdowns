## ***This is a Personalised Roadmap for GSOC 2025 for the Members of the  [Byte Tribe](https://discord.gg/eqs92nbu) server.***

Welcome Everyone to The Byte Tribe Server, This Server is Currently Focused on GSOC 2025 Preparation and aims for its members to reach their best by creating an uplifting community with both experienced and beginner programmers.


### ```This Notebook is strictly for the members of the servers only. Anyone Found Distributing it will be subject to being banned from the server.```


# [Google Summer of Code Official Website](https://summerofcode.withgoogle.com/)

---
# **Fundamental Knowledge**
---
## **What is Open Source?**

### 1. **Source Code Availability:**

 The source code of the software is freely accessible. This allows anyone to inspect how the software works, modify it to suit their needs, and share those modifications with others.

### 2. **Licensing:**

 Open source software is typically distributed under licenses that comply with the Open Source Definition. These licenses grant users the rights to use, modify, and distribute the software.



[List of Free and Open Source Softwares](https://en.wikipedia.org/wiki/List_of_free_and_open-source_software_packages)

---

## **Philosophy behind Open Source:**

The main philosophy of open-source products is the freedom to think, create, learn, and share. It is a collaborative effort of many developers who are working together to create something amazing. In the early phases of technology, open source helps the technology to not become handicapped by some big entities and is developed by people who really have the passion to make that piece of technology better.

---

## **Pre-requisites for contributing in Open-Source**
---
### 1. **Basic Technical Skills**

- #### **Programming Knowledge**  
  Proficiency in at least one programming language. The language will depend on the project you want to contribute to (e.g., Python for Python projects, JavaScript for web projects).

- #### **Version Control**  
  Familiarity with Git and GitHub (or GitLab, Bitbucket) for version control and collaboration.

- #### Learn basic Git commands:  
  - `clone`, `commit`, `push`, `pull`, `branch`, `merge`. Understand how to fork a repository and create pull requests.
  - If someone wants to learn how contribution in Github works, They can contribute to this [Training Repository](https://github.com/Syknapse/Contribute-To-This-Project).
  -The aforementioned resource contains every step with screenshots to help one become familiar with the concept of pull requests and open source contributions.

- #### Development Environment  
  Ability to set up a development environment on your local machine. This includes installing necessary software, libraries, and tools.
  - Integrated Development Environment (IDE) or text editor (e.g., VS Code, PyCharm, Eclipse etc.).
  - Dependency managers (e.g., npm for JavaScript, pip for Python).
  - Containerization tools like Docker (if the project uses it).
---
## 2. **Soft Skills**

- **Communication**: Good written communication skills to interact with project maintainers and other contributors. This includes writing clear commit messages, pull request descriptions, and comments on issues.
  
- **Patience and Persistence**: Open source contributions may require multiple iterations and feedback cycles. Be prepared to iterate and improve your work based on feedback.
---
## 3. **Communicating with Mentors and Project-Leaders**

Communicating through Emails, Slack and other methods is a huge part in getting yourself recognised and being efficient in contributing to the project.
It is also a huge learning oppurtunity if you are able to work in someone with way more experience with professional programming and universal code ethics.

- **Seeking Help**: Know where to find assistance when needed.
- **Learning from Feedback**: Respond well to feedback and use it to improve.
- **Teamwork**: Capable of working both independently and collaboratively in a team.
- **Effective Communication**: Ability to communicate clearly and effectively.
- **Asking Questions**: Know when to ask questions to clarify doubts or issues.
- **Respect for Others**: Respect and consider other people's opinions and feedback.
---

## 4. **Naming Branches and Writing Commit Messages**

### Branch Naming Conventions

- **Feature Branches**: For new features or enhancements.
  - Example: `feature/add-user-authentication`
  - Example: `feature/update-dashboard-ui`

- **Bug Fix Branches**: For bug fixes.
  - Example: `bugfix/fix-login-issue`
  - Example: `bugfix/correct-calculation-error`

- **Improvement Branches**: For code improvements or refactoring.
  - Example: `improvement/refactor-user-service`
  - Example: `improvement/optimize-db-queries`

- **Hotfix Branches**: For urgent fixes.
  - Example: `hotfix/patch-security-vulnerability`
  - Example: `hotfix/update-dependencies`
---
### Writing Commit Messages

- **Structure**: Use a short summary, followed by a blank line, and a detailed description if necessary.
  - Example:
    ```
    Short summary (50 characters or less)

    Detailed explanation of the changes, reasons, and references to issues if applicable.
    ```

- **Examples**:
  - **Feature Addition**:
    ```
    Add user authentication feature

    Implement user login and registration with JWT authentication.
    Update the user model and add corresponding routes and tests.
    ```
  - **Bug Fix**:
    ```
    Fix login issue when username contains spaces

    Corrected the regex used for validating usernames to allow spaces.
    Updated the login form to trim whitespace before submission.
    ```
  - **Code Improvement**:
    ```
    Refactor user service for better readability

    Split the user service into smaller functions for better maintainability.
    Add comments and update documentation.
    ```
  - **Hotfix**:
    ```
    Patch security vulnerability in password hashing

    Upgrade the password hashing library to the latest version to address
    the identified vulnerability. Update existing tests to ensure compatibility.
    ```
---
### Best Practices For Commit Messages

- **Be Clear and Concise**: Summarize the changes in the subject line and provide additional details in the body if necessary.
- **Use the Imperative Mood**: Write the subject line as if you're giving an order, e.g., "Fix bug" instead of "Fixed bug".
- **Reference Issues**: If applicable, reference the issue number that the commit addresses, e.g., "Fix login issue #123".
- **Separate Concerns**: Make sure each commit contains related changes and is not too large. This makes it easier to review and revert if necessary.


---

## General Guide for Good Code Formatting and Linting

Proper code formatting and linting practices help maintain code quality, readability, and consistency across projects.

Some points to remember for good code consistency and quality:

### 1. Consistent Indentation

- Use spaces for indentation (typically 2 or 4 spaces per indent).
- Choose either spaces or tabs consistently throughout your codebase.
- Configure your editor to automatically convert tabs to spaces.

### 2. Naming Conventions

- Follow language-specific naming conventions (e.g., PEP 8 for Python).
- Use descriptive names for variables, functions, classes, and methods.
- Avoid cryptic abbreviations; favor clarity and readability.

### 3. Line Length and Wrapping

- Limit lines to a maximum of 80-120 characters.
- Break long lines into multiple lines to improve readability.
- Use parentheses for line continuation in languages like Python.

### 4. Code Organization

- Structure code logically with consistent spacing and blank lines.
- Group related functions and classes together.
- Use comments and docstrings to explain complex code sections and functions.

### 5. Consistent Code Style

- Adhere to a consistent code style guide (e.g., PEP 8 for Python, Google Style Guide for JavaScript).
- Use automated tools like linters and formatters to enforce style guidelines.

### 6. Linting Tools

- **Linters**: Use linters to analyze code for potential errors, bugs, and stylistic issues.
  - Examples: `pylint` for Python, `eslint` for JavaScript.
- Configure linters to run automatically on code changes or before commits.

### 7. Automated Formatting

- **Formatters**: Use code formatters to automatically enforce style guidelines and formatting rules.
  - Examples: `black` for Python, `prettier` for JavaScript.
- Integrate formatters into your editor or CI/CD pipeline for consistent formatting.

### 8. Version Control Integration

- Commit formatted code only; avoid mixing formatting changes with functional changes.
- Use Git hooks to automatically run linters and formatters before committing or pushing changes.

### 9. Code Reviews

- Incorporate linting and formatting checks into code review processes.
- Discuss and resolve style inconsistencies as part of code review feedback.

### 10. Continuous Improvement

- Regularly update and refine coding standards based on project needs and community best practices.
- Encourage team members to contribute to and follow code formatting and linting guidelines.

By following these guidelines, you can maintain clean, readable code that enhances collaboration and reduces maintenance overhead in your projects.

---
## Reading Documentation of GSoC Projects and Handling Large Codebases

Understanding the documentation of Google Summer of Code (GSoC) projects and effectively navigating large codebases are essential skills for successful contributions.

### 1. Understanding Documentation

- **Start with the README**: The README file provides an overview of the project, its purpose, installation instructions, and basic usage.
- **Contribution Guidelines**: Review the CONTRIBUTING.md file or section in the README for guidelines on how to contribute effectively.
- **Project Structure**: Understand the organization of the codebase, including main directories, modules, and important files.

### 2. Navigating Large Codebases

- **Search Functionality**: Use the search functionality in your code editor or IDE to quickly locate files, functions, and variables.
- **Directory Structure**: Familiarize yourself with the directory structure to understand where different components of the project are located.
- **Module Dependencies**: Identify dependencies between modules or packages to understand how different parts of the code interact.

### 3. Code Documentation

- **Inline Comments**: Pay attention to inline comments that explain specific sections of code or provide context for complex algorithms.
- **Docstrings**: Look for docstrings in functions, classes, and methods that describe their purpose, parameters, and return values.
- **API Documentation**: If the project includes APIs, review the API documentation to understand endpoints, request methods, and response formats.

### 4. Handling Complexity

- **Break Down Tasks**: Break down large tasks into smaller, manageable sub-tasks to tackle them incrementally.
- **Code Reviews**: Utilize code reviews to gain insights from experienced contributors and ensure code quality.
- **Version Control**: Use version control effectively to track changes, revert to previous versions if needed, and collaborate with other contributors.

### 5. Tools and Techniques

- **Debugger**: Use a debugger to step through code execution, inspect variables, and understand control flow.
- **Code Analysis Tools**: Employ static code analysis tools to identify potential issues, improve code quality, and enforce coding standards.
- **Profiling Tools**: Use profiling tools to analyze code performance and identify bottlenecks in large codebases.

### 6. Communication and Collaboration

- **Ask for Clarification**: Don’t hesitate to ask questions on project communication channels (e.g., Slack, mailing lists) to clarify doubts about project structure or functionality.
- **Collaborative Tools**: Use collaborative tools like issue trackers (e.g., GitHub Issues) and project management boards (e.g., Trello, JIRA) to coordinate efforts and track progress.

### 7. Continuous Learning

- **Stay Updated**: Regularly review project updates, new features, and changes in the codebase.
- **Expand Knowledge**: Continuously expand your knowledge of relevant technologies, frameworks, and best practices through online courses, tutorials, and documentation.

By following these guidelines, you can effectively read and navigate the documentation of GSoC projects and handle large codebases to make meaningful contributions during your GSoC journey.

-------
## Finding an Open Source Project to Contribute

Identifying a project to contribute to is a crucial step in your open source journey. Here are some effective methods to find a project that aligns with your interests:

### Identify Your Passionate Projects

- **Daily Use**: Consider projects you use frequently in your daily life. You are likely passionate about improving features or fixing issues that affect you directly.

### Utilize Online Platforms

- [**Google Summer of Code (GSoC) Website**](https://summerofcode.withgoogle.com/):
  - Explore organizations that work on technologies you're passionate about.
  - Search for projects aligned with your interests and skills.

- [**GitHub Explore**](https://github.com/explore):
  - Browse trending repositories and topics related to your passion.

- [**GitHub Issues**](https://github.com/features/issues):
  - Use GitHub's powerful issue search tool to find projects with good first issues or specific topics.
-  [**Open Source Friday**](https://opensourcefriday.com/)
-  [**First Timers Only**](https://firsttimersonly.com/)
-  [**CodeTriage**](https://codetriage.com/)
-  [**24 Pull Requests**](https://24pullrequests.com/)
-  [**Up for Grabs**](https://up-for-grabs.net/#/)
-  [**First Contributions**](https://firstcontributions.github.io/)
-  [**Source Sort**](https://web.archive.org/web/20201111233803/https://www.sourcesort.com/)
-  [**OpenSauced**](https://opensauced.pizza/)
-  [**Ovio -**](https://ovio.org/) [For finding good first issues use this link.](https://ovio.org/issues)




### Community Engagement

- **Welcoming Communities**:
  - Join communities known for welcoming new contributors, such as those listed on [Open Source Friday](https://opensourcefriday.com/), [First Timers Only](https://firsttimersonly.com/), and [CodeTriage](https://codetriage.com/).

- **Events and Initiatives**:
  - Participate in initiatives like 24 Pull Requests, Up For Grabs, and First Contributions.

### Resources

- **Open Source Guides**:
  - Visit freeCodeCamp's guide on [how to contribute to open source](https://github.com/freeCodeCamp/how-to-contribute-to-open-source) for comprehensive resources.
---


# **Timeline Roadmap**



## *1. Understanding GSoC (June - July)*
   - *Research GSoC:* Read the [Google Summer of Code Official Website](https://summerofcode.withgoogle.com/)
 to understand the program's structure, goals, and timelines.
   - *Attend the Weekly Calls and Chats:* Get yourself familiar with the server,chat with fellow members to discuss GSOC approaches and collaboration for project ideas, also attend the weekly calls to connect with past participants and mentors.

### *2. Skill Development (July - September)*
   - *Identify Your Strengths and Weaknesses:* Determine which programming languages and frameworks you need to improve.
   - *Learn the Basics:* If you're new to open source, learn about version control systems like Git and collaboration tools like GitHub or GitLab.
   - *Practice Coding:* Work on coding challenges on platforms like [LeetCode](https://www.leetcode.com), [HackerRank](https://www.hackerrank.com) , or [Codeforces](https://www.codeforces.com) to improve your problem-solving skills.

   - Advanced members can practice by participating in other open source events and projects of thier own to brush up thier skills.

   - Project ideas and people that are willing to contribute can be found in the ```#project-ideas``` channel of the server.

   - Ongoing projects include [Stream Pulse](https://github.com/ayushsharma74/stream-pulse) by Ayush.

   - Use ```#project-ideas``` to promote contribution on your own project or to propose a project idea to server members.

### *3. Explore Organizations (October - November)*
   - *List of Organizations:* Review the list of participating organizations from previous years to get an idea of which organizations might participate again.
   - A complete comprehensive list of the past programs can be found [here.](https://www.gsocorganizations.dev)
   - *Match Interests:* Identify organizations that align with your interests and skill set.
   - *Contribute to Projects:* Start contributing to the projects of these organizations. This can be through fixing bugs, adding features, or improving documentation - *(while updating the documentation, refrain from making unnecessary changes and changes that are not meaningful)*.

### *4. Deep Dive into Selected Organizations (December - January)*
   - *Understand the Projects:* Read about the projects that interest you, understand their goals, and look at their codebase.
   - *Engage with the Community:* Join the IRC channels, Slack groups,Discord servers, or mailing lists of these organizations. Introduce yourself and ask questions.
   - Use [This](https://google.github.io/gsocguides/student/communication-best-practices) Guide here to follow the best practices for professional and respectful communication in GSOC communities.
   - *Contribute Actively:* Make meaningful contributions to the projects. This will help you build a rapport with the community and potential mentors.

### *5. Proposal Preparation (February - March)*
   - *Identify Potential Projects:* Review the list of projects proposed by the organizations.
   - *Draft Proposal:* Start drafting your project proposal. Include details like project objectives, timeline (Make sure to add timeline that fits according to your scenario), milestones, and your approach.
   - *Seek Feedback:* Share your draft with mentors and the community for feedback. Refine your proposal based on their suggestions. DO NOT send your proposal without acceptance from mentors you'll be immediatly rejected
   - *Prepare Backup Proposals:* It's a good idea to have more than one proposal in case your primary proposal is not selected.

### *6. Application Phase (March - April)*
   - *Submit Application:* Submit your final proposal through the GSoC website. Make sure it’s well-polished and error-free.
   - *Follow Up:* Keep in touch with the community and mentors. Answer any questions they might have about your proposal.

### *7. Pre-Coding Period (April - May)*
   - *Community Bonding:* Use this time to bond with your organization. Understand their coding standards and workflow.
   - *Set Up Development Environment:* Ensure you have all the necessary tools and dependencies set up on your system eg. Docker, NodeJS, Python etc.
   - *Plan in Detail:* Break down your project into smaller tasks and create a detailed plan for the coding period.

### *8. Coding Period (May - August)*
   - *Regular Updates:* Provide regular updates to your mentor and community. Use version control (Git, GitHub etc) effectively to track your progress.
   - *Stick to the Timeline:* Follow the timeline you proposed. If you encounter any issues, communicate them promptly.
   - *Testing:* Write tests for your code and ensure it integrates well with the existing codebase.

### *9. Final Evaluation (August)*
   - *Complete Documentation:* Write detailed documentation for your project. This includes setup guides, user manuals, and developer guides.
   - *Final Submission:* Submit your completed project for final evaluation. Ensure all your code is merged and documented.
   - *Prepare for Demo:* Be ready to present your work to the community and mentors.

### *10. Post-GSoC (September and beyond)*
   - *Reflect:* Reflect on your experience. Note down what you learned and areas for improvement.
   - *Continue Contributing:* If possible, continue contributing to the organization. This can lead to long-term collaboration.
   - *Share Your Experience:* Write a blog post or give a talk about your GSoC journey. This can help future participants.

### *Additional Tips*
   - *Time Management:* Balance your GSoC preparations with other commitments. Set aside regular time for open-source contributions.
   - *Networking:* Build connections with fellow GSoC participants. They can provide support and feedback.
   - *Learning Resources:* Utilize online courses, tutorials, and books to enhance your skills.

And Thats it for this Roadmap, Routine improvements will be made to this notebook and contributions to this roadmap are also welcome.






