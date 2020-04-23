This is a [VS Code development container](https://github.com/microsoft/vscode-dev-containers) for the [Unison Codebase Manager](https://github.com/unisonweb/unison).

You can check that first link for the full details of how to get set up to use VS Code development containers, but the gist of it is:

1. Install [Docker](https://docs.docker.com/get-docker/).
2. Install the [Remote Development extension pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack).
3. Clone this repo.
4. In VS Code, either:
    - "Open folder..." the cloned repo, then click the "Reopen in container" button that appears in the lower right.
    OR
    - F1 and "Remote-Containers: Open Folder in Container..." the cloned repo.
5. In VS Code, open a New Terminal from the Terminal menu.
6. Run `ucm init; ucm`.

Disclaimer: I don't really know how VS Code containers work, so be sure to `push` your codebase somewhere safe as a backup!
  
Improvements, suggestions, and simplifications are welcome!
