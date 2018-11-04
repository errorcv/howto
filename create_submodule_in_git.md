
Clone git repository:
```
git clone https://github.com/errorcv/agent
```

Add submodule and define the master branch as the one you want to track:
```
git submodule add -b master https://github.com/errorcv/frontend
git submodule add -b master https://github.com/errorcv/backend
git submodule init
```

To update submodules --remote fetches new commits in the submodules and updates the working tree to the commit described by the branch:
```
git submodule update --remote
```

Push changes:
```
git add backend
git commit -m "Add LICENSE frontend and backend submodules"
git push
```

Pull all changes in the repo including changes in the submodules:
```
git pull --recurse-submodules
```

Update agent:
```

```

