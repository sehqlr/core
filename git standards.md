# Standards for using git for CftP projects

We're a diverse group of skillsets at varying levels of skill, completely spread out and working in whatever free time we can. Organization is _king_ in this scenario - otherwise we will end up with drastically approaches to git and messy repos as a result.

## All repositores must have all non initial commits done by pull-request
All pull requests must be reviewed. Deployed projects can have minor hotfixes deployed by admins at critical times, but if this is abused the group may change this rule as it sees fit.

Pull requests should be thoroughly reviewed and discussions on them are encouraged.

## git commits MUST be small, oriented towards a single feature or bug fix
No commits with 200 files for five different features, please.

## All git commits must follow a standard title

Git commits must follow the format of 

```
category: Short title

Optional, but highly encouraged, explaining text of any length talking about what went down.
```

This will keep commits organized and easier to read/categorize for importance.

### Category options

* feature - When a new feature is being created
* fix - For a fixing of a bug. Referencing an issue is a bonus, but not required if not opened
* style - for CSS and HTML styling fixes
* doc - For documentation
* content - for static content adjustment
* deploy - for deploy changes and adjustments
* merge - for merging in branches/pull requests
* init - The initial commit or project setup
* tool - For adjustment or addition of any backend tooling required for the project
* format - For CODE style changes and cleaning
