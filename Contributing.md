# Contributing

Hello team,

We'd be working in teams or mini groups sooner than later and I deemed it fit to give us a heads up sort of on git flow from a forked repo point of view. 
The aim is just so we avoid or at least cut-down unnecessary conflicts that usually herald working in teams.

Core to all I'm saying is the need to always pull before pushing, for obvious reasons; you're not working on the repo alone irrespective of the fact that you forked.
To do this effectively, you'd have to set the repo you forked from as an upstream. Run

```git remote -v```

 to show URLs of remote repositories. This would ideally list your remote fork. Then run:

 ```git remote add upstream https://github.com/original_owner/original_repository.git```

 This is to add the original repository as an upstream. To ensure its added, run this again:

 ```git remote -v ```

 This time the original remote repository should be listed.

 Now you can pull changes made to the remote repository to be up-to-date with yours.
However, to ensure you don't lose your changes Always commit before pulling.


## Pull Request Process



