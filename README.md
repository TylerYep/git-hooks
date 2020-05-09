# git-hooks
An easy way to import git pre-commit or post-commit hooks into a repository.

To use, simply clone this repository and then add the scripts/ folder to your project.

Run `scripts/install-hooks` to install all hooks. This will create a symbolic link to your scripts, so changing your scripts will automatically change the linked hooks.

Then, modify any of the other files in order to customize your git workflow.

If you no longer want to use these hooks, run `scripts/uninstall-hooks` and then delete the `scripts/` folder.