# Solo Doc: Getting Started with GitHub Documentation

This guide explains the basic workflow for creating, publishing, and collaborating on a simple documentation project using VS Code, GitHub Desktop, GitHub, and GitHub Pages.

## Install the Tools

Install [Visual Studio Code](https://code.visualstudio.com/) and [GitHub Desktop](https://desktop.github.com/). VS Code is used to create and edit project files, while GitHub Desktop provides a graphical way to manage Git changes without relying entirely on terminal commands.

I also installed the [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) extension for VS Code because it adds useful shortcuts and formatting tools for Markdown.

## Create a Repository

Create a public GitHub repository and open it through GitHub Desktop. A repository stores the files in a project and keeps a record of changes made to them over time.

## Create and Commit Files

Create an `index.html` file at the top level of the repository. In this project, the page contains a link back to the public repository.

After making changes, use GitHub Desktop to stage and commit them. A commit records a version of the project. Push the commit to the remote repository so the changes also appear on GitHub.

## Publish with GitHub Pages

Use [GitHub Pages](https://pages.github.com/) to publish the `index.html` file as a live webpage. GitHub Pages is useful because it can turn files already stored in a repository into a public website without requiring separate hosting.

In the repository settings, choose **Pages**, select **Deploy from a branch**, and publish from the `main` branch and `/root` folder.

## Collaborate with a Pull Request

Invite another GitHub user as a collaborator. That person can suggest a change and open a pull request.

A pull request allows a proposed change to be reviewed before it becomes part of the main project. Once the change is acceptable, approve and merge it into the repository.

## Document the Process

Use `README.md` to explain the project and its workflow. Markdown headings, lists, links, bold text, and code formatting make documentation easier to scan and use.