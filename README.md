# Git Hooks
The git hooks for Command and Data Handling :octopus:

##INSTALLATION

Download the files using:
```
git clone https://github.com/SpaceHAUC-Command-and-Data-Handling/git_hooks.git
```

Move the hook_installer script and hooks folder into your bin:
```
mv -r hooks ~/bin
mv hook_installer ~/bin
```

###Optional:
You can run
```
echo alias git_init_hooks='git init; hook_installer' >> ~/.bashrc
```
to add an alias that allows you to create a repository with the hooks in one
step.

##USAGE
After creating a new git repository with git init run:
```
hook_installer
```
to add the hooks. If you added the alias in optional installation you can
simply run the command
```
git_init_hooks
```
