# git_configuration

This tutorial is about configure the git environment.

The related files are downloaded from the Udacity Course [How to Use Git and GitHub](https://www.udacity.com/course/how-to-use-git-and-github--ud775).

## Downloading necessary files

The three necessray files are in the onlines repository: `git-completion.bash`, `git-prompt.sh`, and `bash_profile_course`.

* If you already have a file in your home directory named `.bash_profile` in mac or `.bashrc` in linux, copy the content from `bash_profile_course` and paste it at the bottom of `.bash_profile`. Otherwise, move `bash_profile_course` to your home directory and rename it to `.bash_profile` in mac or `.bashrc` in linux.
* Move the `git-completion.bash` and `git-prompt.sh` to the home directory `~`.
* Restart the bash.

## Making Git Configurations

Run the following Git configuration commands. Assume I am use `vim`.

```
git config --global core.editor "vim -n -w"
git config --global push.default upstream
git config --global merge.conflictstyle diff3
```


