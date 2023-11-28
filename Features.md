

## Git Flow
Git Flow is a well established workflow for git repositories made popular by [a post by Vincent Driessen](https://nvie.com/posts/a-successful-git-branching-model/). Support for Git Flow operations in Fork 1.17 streamlines the development process by introducing a set of context menu items for common Git Flow actions.

Initialize Git Flow in your repo using the Repository application menu. You will then be able to choose custom branch name prefixes if needed:
![fork-win-1.17--gitflow](/resources/fork-win-1.17-gitflow.png)

Creating and finishing features, releases and hotfixes is available via the commit or branch context menu.
![fork-win-1.17-gitflow-menu](/resources/fork-win-1.17-gitflow-menu.png)


Source: [Fork for Windows 1.17](https://fork.dev/blog/page/4/)
---

## Automatic background fetch
Gone are the days when you had to press ⇧⌘F every time to get the latest changes from a repository. Fork will now perform an automatic fetch of all remotes in open tabs every 20 minutes. This option can be disabled in the contextual menu of a remote, or globally in Fork preferences. [35]

## Cancel Fetch/Pull/Push/Clone operations
You might have often found yourself in dire need of canceling some of the longer git operations. Fork 1.0.67 adds the ability to cancel fetch, pull, push, and clone – the button to do so is located in the status bar.

![fork-1.0.67-cancel.gif](/resources/fork-1.0.67-cancel.gif)

Source: [Fork 1.0.67](https://fork.dev/blog/page/4/)
---