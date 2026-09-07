# Solo Doc: Getting Started with GitHub Documentation

To begin, install [Visual Studio Code](https://code.visualstudio.com/) and [GitHub Desktop](https://desktop.github.com/). VS Code is used to create and edit project files, while GitHub Desktop provides a graphical interface within which you can manage Git changes without relying entirely on terminal commands.

I also recommend installing [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one), which is an extension for VS Code that adds useful shortcuts and other tools for organizing Markdown files.

Basically, you're creating files locally, using Git to track and manage changes, and then using GitHub to store, publish, and collaborate on those files online.

## Create a Repository

Create a new repository through GitHub Desktop and publish it to GitHub. A repository stores the files that make up a project and keeps a history of changes made to them.

The repository must be public for this project. If you accidentally create it as private, open the repository on GitHub in your browser, select **Settings**, scroll to **Danger Zone**, and choose **Change repository visibility** to make it public.

## Create, Stage, Commit, and Push Files

Create an `index.html` file at the top level of the repository. For this project, the page should contain a link back to the public GitHub repository.

After editing and saving a file in VS Code, open GitHub Desktop. The changed file will appear under **Changes**. Staging means selecting which changed files will be included in the next commit; in GitHub Desktop, you do this by checking the box beside each file.

Next, enter a short summary describing the change and select **Commit to main**. A commit records that version of the project locally. Finally, select **Push origin** to send the committed changes to the copy of the repository stored on GitHub.

## Publish with GitHub Pages

***GitHub Pages is useful because it can turn files already stored in a repository into a public website without requiring separate hosting.***

To publish the site, first open the repository on GitHub in your browser. One way to get there is to right-click the repository in GitHub Desktop and choose **View on GitHub**. On the GitHub repository page, select **Settings**, then **Pages** from the left menu. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and `/root` folder, and save the settings.

GitHub will then build the site and provide a public URL. The site may take a minute or two to become available.

## Collaborate with a Pull Request

Invite another GitHub user to collaborate by opening the repository in your browser and selecting **Settings** > **Collaborators** > **Add people**. Search for the collaborator by their GitHub username, name, or email address and send the invitation.

After accepting the invitation, the collaborator can make a change to the repository and open a pull request. A pull request allows a proposed change to be reviewed before it becomes part of the main version of the project.

When the collaborator submits the pull request, return to the repository in your browser and select the **Pull requests** tab near the top of the page. Open the request, review the proposed change, select **Merge pull request**, and confirm the merge.

## Document the Project

Create a `README.md` file at the top level of the repository to document what the project does and how someone else can reproduce the process. Unlike `index.html`, which becomes the published webpage, the README appears directly on the repository page and serves as documentation for people viewing or working with the project.

Markdown formatting such as headings, lists, links, **bold text**, *italics*, and `code formatting` helps organize the instructions and makes them easier to scan.