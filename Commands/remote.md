# git remote

When working with git, a **remote** is any git repository that is not on the machine you're working on. the counterpart to this is **local**, or the machine that is being developed on.

Take github for example. while git is the technology that allows you to create local repositories, github is the site that will host your remote repositories. once stored remotely, you can bring that repository back down or share it with others.

**note**: while the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

### Adding a remote

A remote can be added with the 'git remote add' command, followed by the name and location of the remote.

The name is a local name, meaning it's your label and does not impact the actual remote whatsoever.

'''
git remote addd origin https://github.com/elevenfiftyacademy/gitfundamentals.git
'''

### Removing a remote

a remote can be removed with the 'git remote remove' command, followed by the name of the remote.

'''
git remove origin
'''

## Resources

- [git remote documentation](https://git-scm.com/docs/git-remote)

---

[back to home](../readme.md)