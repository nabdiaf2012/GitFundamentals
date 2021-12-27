# git remote 

when working with git , a ** remote** is any git repository that is not on the machine you are working working on. the conterpart to this is local or the machine that is being developed on.

take github for example, while git is the technology that allows you create local repository, github is the site that will host your remote repositories. once stored remotely, you can bring that repository back down or share it with other.

**Note**: while the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

### Adding a remote

a remote can be added with the `git remote add` command, folled by the name and location of the remote.

the name is a local name, meaning it is your label and does not impact the actual remote whatsover.

```
git remote add origin https://github.com?Elevenfifty
```

### removing a remote

a remote can be removed with the `git remote remove` command, folled by the name of the remote

```
git remote remove origin
````

## Resources

- [Git remote Documentation] (https: // git: // git -scm.com/docs/git-remote)

---

[Back to home](../Readme.md)

