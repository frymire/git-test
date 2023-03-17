Proof that I can use git.

Here's a great git log alias (git lg)...<br>
git config --global alias.lg 'log --graph --pretty=format:"%C(auto)%h%d%Creset %C(cyan)(%cr)%Creset %C(green)%cn %Creset %s"'

Previously, it was...<br>
git config --global alias.lg "log --graph --decorate --pretty=oneline --abbrev-commit --all"
