
# Git handbook


![Logo](https://mevn-public.s3-ap-southeast-1.amazonaws.com/marketenterprise.vn/wp-images/2023/11/27145446/2color-lightbg%402x.png)


## Fetch branch

```bash
git checkout -b local_branch_name origin/remote_branch_name
```

## Delete local branch

```bash
git branch --delete <branchname>
```

## Clean commit histories.

```bash
git checkout --orphan new-branch
```

```bash
git add .
git commit -m "your commit"
```

```bash
git branch -D main
git branch -m main
git push -f origin main
```

## Change remote origin

```bash
git remote set-url origin new.git.url/here
```

