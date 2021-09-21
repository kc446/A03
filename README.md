# A03
*for IS 117*

<u>How to use WebStorm</u>

1. WebStorm is an IDE, so once you have it fully installed (with a license, of course) on your computer, you can integrate Git and your GitHub account to edit **repositories**!
2. Open/Clone a **repository** -- you can do both directly from the GitHub Desktop App.
3. You should see all the files in your repository in the left sidebar, under (next to??) the 'Project' tab)
4. Open a file and make changes to it, or add a new file (I'm pretty sure you just drag and drop; I never actually did that because I had no need to this time but that sounds about right to me)
5. In the top right corner, you should see some little arrows and a checkmark. These buttons will allow you to **Commit** (checkmark) or **Push** (green arrow) your changes to GitHub.
6. Selecting Commit will allow you to review all the changes made before you push -- or you can just push them directly (more on these terms below, in the Git tutorial!)

<u>How to Use Git</u>
1. Create a repository
2. Copy the repository to your local network/computer -- this is called **cloning**
3. Open the repository in WebStorm or whatever IDE you're using (you can do this directly from github's desktop app)
4. Change and add files in the repository as you will (these changes are called **commits**)
   - Think *'Ctrl+S'* or saving changes an actual file, only with extra steps.
5. (optional) Create a **branch** of the central repository with all your commits bundled into it
   - It's easier to do this in GitHub, but if you're doing it from the browser it also requires starting a **pull** request to **merge** your branch into the repository.
   - If commits are like a *"Save..."* command, branches are somewhat like the less common *"Save New Version"*, except you can merge the new version into the original when you're ready to do so. Like a temporary copy, maybe.
6. **Push** your commits to the remote repository (in our case, it's here on GitHub)
   - Apparently GitHub has a desktop app so you can clone and push changes to the remote repo. The only thing it can't really do (I don't think) is edit them directly (That's what WebStorm is for!.

<u>Glossary</u>

- **Git** - A free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency (description on the official website, https://git-scm.com/)
- **GitHub** - The website where central/remote git repositories are stored, shared, and distributed -- you're already here!
- **Repository** - Essentially a Git project 'folder' with all sorts of files inside, sometimes shortened to "repo"
- **Clone** - A mirror copy of an existing repository that is downloaded to your local system
- **Remote** - Connections to other repositories on the server (e.g. GitHub) that you can reference with an alias to rather than a direct link
- **Commit** - A package of changes made to a file in a repository
- **Push** - Sending a commit to a remote repository.
- **Branch** - S deviation of an existing repository. these are especially common when a repository has multiple collaborators making multiple commits to the same repo
- **Fork** - A clone of an existing repository on github that you can edit without affecting the original (or "upstream") repository. you can start a pull request to merge it with the upstream repo
  - commit = *"Save"*, branch = *"Save New Version"*, fork = *"Save As/Duplicate"*
- **Pull** - Merging a remote repository into your local repository, as if you were 'downloading' any changes made -- on github you need to make a pull request to do that
- **Merge** - Integrating a branch into the main repository
- **Merge Conflict** - merging branches with different commits and you need to decide which commits will be pushed
- **Fetch** - Downloading a remote repo into a local repo, without affecting the former
  - Basically a reverse fork

<u>References</u>

- https://git-scm.com/
- https://docs.github.com/en/
- https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud
- https://www.git-tower.com/learn/git/faq/difference-between-git-fetch-git-pull/
