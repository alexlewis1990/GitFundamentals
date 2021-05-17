# git commit

the command 'git commit' will take all tracked changes (items added with [git add](./add.md)) and package them up in what is called a commit.

commits come with commit messages that are required for each commit. you add a message to a commit command by using the '-m' flag followed by a message in quotes.

a commit message can be anything, but best practice dictates that you should use that message to indicate the changes included in the commit.

For example, if we have an application we're working on where we just built out the ability to register new accounts, then you might have some variation of the following:

'''
git add .
git commit -m "added register functionality"
'''

Then when viewing the history of a git repository, you can pinpoint where the registration functionality was added.

## Resources

- [git commit documentation](https://git-scm.com/docs/git-commit)

---

[back to home](../readme.md)