# **How to use the system**

In this section, we'll explore the practical aspects of utilizing our key systems at Avkalan Labs. You'll learn how to navigate and leverage tools like Slack, Obsidian, Git, and GitHub to enhance communication, collaboration, and project management.

## **Slack**

Slack is a dynamic communication platform that streamlines team collaboration and information sharing. It organizes conversations into channels, making it easy to find discussions on specific topics or projects. With its intuitive messaging features, you can easily send direct messages, create threads to keep conversations organized, and share files seamlessly.

### **How to use slack for communications**

At Avkalan Labs, we highly value teamwork and encourage the use of channels for communicating with your team members, regardless of the size of the task or query.

**Here are some tips for effective communication on Slack:**

- **Use Channels**: Channels are organized spaces for conversations related to specific topics or projects. They help keep discussions focused and accessible to all relevant team members. Use channels to share updates, ask questions, and collaborate on tasks. We have channels divided into categories like admin, team, project, help, and social, each with specific prefixes to indicate their purpose.
    - **Admin Channels**: For administrative-related discussions.
    - **Team Channels**: For discussions within specific teams, such as hardware, software, design, or marketing.
    - **Project Channels**: For members from different teams working on common projects.
    - **Help Channels**: For seeking assistance and asking queries.
    - **Social Channels**: For interacting, exploring hobbies and interests, and sharing relatable content.
    - **Use Direct Messages**: For personal or private communications that don't require the attention of a whole group, use direct messages (DMs) to reach out to individual team members.
- **Use Threads**: To keep conversations organized and avoid cluttering the main channel view, use threads to respond to specific messages. This keeps related messages grouped together and makes it easier to follow the conversation.

### **What is Canvas in Slack and How to Use It**

Canvas is a feature in Slack that allows you to create and collaborate on documents directly within the platform. It's particularly useful for setting and tracking milestones to ensure that you're moving in the right direction toward your goals. Here's how to use Canvas in Slack for this purpose:

- **Defining Milestones:** The first step in achieving any goal is to break it down into achievable milestones. Typically, this is done by the Project's Point of Contact (PoC). The milestones are defined every Monday morning. The PoC outlines the project's milestones based on its goals.
- **Actionable Items**: Break down these milestones into actionable items for each day. This helps in organizing your tasks and keeping track of what needs to be done to reach your weekly milestones.
- **Updating Canvas**: It's crucial to keep your Canvas consistently updated with any changes or progress in your actions and milestones. This ensures that you and your team are always on the same page and can adjust your plans as needed. By using the Canvas feature in Slack, you can effectively track your milestones, organize your tasks, and keep your team informed about your progress.



## **Obsidian**

Obsidian is a powerful note-taking and knowledge management application that uses Markdown for formatting. It allows you to create a network of interconnected notes, making it an ideal tool for organizing thoughts, ideas, and information. With its unique linking feature, you can easily navigate between related notes, creating a web of knowledge that grows over time.

**Here's how to use Obsidian for your projects:**

1. **Open the folder as vault**: Launch Obsidian and open the folder containing your project as a vault.
2. **Open the cloned project template**: Use the project template cloned in the previous step as your working directory in Obsidian.
3. **Use default settings**: Follow all the default settings of the project template to maintain consistency.
4. **Use linked notes feature**: Utilize Obsidian's linking feature to connect related notes within the project. This helps in maintaining a clear structure and easy navigation throughout the project's documentation.
5. **Collaborate and commit changes**: Work on your notes and files in Obsidian, then use GitHub Desktop to commit and push changes to the repository. This ensures that everyone in the team has access to the latest updates and can contribute to the project.

By integrating Obsidian with GitHub, you can enhance collaboration on projects, combining the power of note-taking and version control for effective project management. Whether it's notes or any other writing content, everything in Obsidian is written in Markdown. Knowing the basics of Markdown is crucial to use Obsidian effectively, as it allows you to format your notes quickly and efficiently.

You can go through the following short tutorial to learn the basics of Obsidian-



### Markdown the language of internet

Markdown is a lightweight markup language used for formatting text. It's the language used in Obsidian for creating and editing notes.

**Here are some basics:**

- **Headers**: Use `#` for headers. For example, `# Header 1`, `## Header 2`, `### Header 3`.
- **Bold**: Use `**text**` or `__text__` to make text bold. For example, `**bold text**`.
- **Italic**: Use `*text*` or `_text_` to italicize text. For example, `*italic text*`.
- **Lists**: Use `-` or `*` for unordered lists, and `1.`, `2.`, `3.` for ordered lists.
- **Links**: Use `[text](URL)` to create hyperlinks. For example, `[Google](https://www.google.com)`.
- **Images**: Use `![alt text](image URL)` to insert images. For example, `![logo](https://example.com/logo.png)`.

Learning Markdown is essential for using Obsidian effectively, as it allows you to format your notes quickly and efficiently. You can go through the following short tutorial to learn the basic syntax of the makrdowns - [Markdown Tutorial](https://www.markdowntutorial.com/)

## Git and GitHub

Git is a version control system that tracks code changes and enables collaboration among developers. GitHub, built on Git, is a platform for hosting, reviewing, and managing code, offering features like pull requests and issue tracking. Together, they provide a comprehensive ecosystem for efficient and precise software development.

### How to use Git/version control

Git is a version control system that allows you to track changes in your code and collaborate with others.

**Here's how to use Git for version control:** - **Initialize a Repository**: Start by creating a new directory for your project and initializing it as a Git repository using the command `git init`. - **Track Changes**: As you make changes to your files, use `git add` to stage them for commit, and `git commit` to save the changes to your repository's history. - **Branching**: Create branches using `git branch` to work on new features or bug fixes without affecting the main codebase. Switch between branches with `git checkout`. - **Merging**: Once your changes are complete, merge them back into the main branch using `git merge`. - **Viewing History**: Use `git log` to view the commit history and see what changes have been made.

The following course gives a brief overview of the Version Control or Git -


Once your course is complete try to make your first pull request here. [First Contribution](https://github.com/firstcontributions/first-contributions)
### **How to Use GitHub and GitHub Desktop for Collaborative Projects**

GitHub is a platform for hosting Git repositories and collaborating on projects.

**Here's how to use GitHub and GitHub Desktop for collaboration:**

- **Create a Repository**: Use the project template from “[](https://github.com/iitrabhi/project-template%E2%80%9D)[https://github.com/iitrabhi/project-template”](https://github.com/iitrabhi/project-template%E2%80%9D) to start a new research project. Make sure you are logged into your GitHub account to use the template. This repository will be the central location where your code is stored and managed.
- **Clone the Repository**:
    - Click on the `Use this template` button on the template repository page.
    - Select `Create a new repository` and give your project a specific name.
    - Open GitHub Desktop and choose `File` > `Clone Repository`.
    - Select the newly created repository from the list.
    - Choose a local path where you want to clone the repository.
    - Click the `Clone` button to start cloning the repository.
- **Collaborate**: Invite team members to collaborate on the repository. They can clone the repository, make changes, and push their commits.
- **Pull Requests**: Use pull requests to propose changes to the codebase. Team members can review the changes, provide feedback, and merge the changes into the main branch.
- **Issues**: Use GitHub issues to track bugs, feature requests, and tasks. Assign issues to team members and track their progress.

You can go through the following short tutorial to learn the basics of GitHub-
[![Video Title](https://img.youtube.com/vi/dQw4w9WgXcQ/0.jpg)](https://www.youtube.com/watch?v=PQsJR8ci3J0&ab_channel=edureka%21"Watch the Video")



By using Git for version control and GitHub for collaboration, you can effectively manage your code and work together with your team on projects.

