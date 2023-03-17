Proof that I can use git.

Here's a great git log alias (git lg)...<br>
git config --global alias.lg 'log --graph --date=format-local:"%a %m-%d-%Y %I:%M %p" --pretty=format:"%C(auto)%h%d%Creset %C(cyan) %cd (%cr)%Creset %C(green)%cn %Creset %s" --decorate --abbrev-commit --all'

Previously, it was...<br>
git config --global alias.lg "log --graph --decorate --pretty=oneline --abbrev-commit --all"
