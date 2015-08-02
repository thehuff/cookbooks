# Git - Remotes

## Get a list of all remote repos
```bash
git remote -v
```

## Move a repository to a new remote
<https://stackoverflow.com/questions/3011402/leaving-github-how-to-change-the-origin-of-a-git-repo>

```bash
git remote rename origin old_remote
git remote add origin https://new-remote.url/project.git
git remote rm old_remote
```
