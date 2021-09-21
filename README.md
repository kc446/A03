# A03
*for IS 117*

<u>How to Use Git</u>
1. Create a **repository**
2. Copy the repository to your local network/computer -- this is called **cloning**
3. Open the repository in webstorm or whatever IDE you're using (you can do this directly from github's desktop app)
4. Change and add files in the repository as you will (these changes are called **commits**)
   - Think *'Ctrl+S'* or saving changes an actual file, only with extra steps.
5. (optional) Create a **branch** of the central repository with all your commits bundled into it
   - It's easier to do this in GitHub, but if you're doing it from the browser it also requires starting a **pull** request to **merge** your branch into the repository.
   - If commits are like a *"Save..."* command, branches are somewhat like the less common *"Save New Version"*, except you can merge the new version into the original when you're ready to do so. Like a temporary copy, maybe.
6. **Push** your commits to the remote repository (in our case, it's here on GitHub)
   - Apparently GitHub has a desktop app so you can clone and push changes to the remote repo. The only thing it can't really do (I don't think) is edit them directly.

<u>Glossary</u>

- **GIT** - A free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency (description on the official website, https://git-scm.com/)
- **GitHub** - The website where central/remote git repositories are stored, shared, and distributed -- you're already here!
- **Repository** - Essentially a Git/Github project folder with all sorts of files inside, sometimes shortened to "repo"
- **Clone** - A duplicate of an existing repository that is downloaded to your local system
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