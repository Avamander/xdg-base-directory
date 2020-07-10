# xdg-base-directory

The enviroment variables set by `exports.sh` will help making a lot of software more compliant with the XDG base directory specification. However, please keep in mind that not all software allows such configuration and this list is not comprehensive. If you know software that is missing from this list or spot an error, please open a PR.

## Other cleanup

You might also wish to look into creating a global gitignore that doesn't let you commit junk files to different repositories. `.directory` files in repositories aren't very useful.
