# Vulnerable Application Deployment - OWASP Juice Shop

## 1. Objective
Deploy OWASP Juice Shop locally.


## 2. Environment
- Operating system: macOS
- Version control: GitHub
- Runtime: Docker Desktop
- Application URL: http://localhost:3000


## 3. Steps followed
1. Forked the GitHub repository : https://github.com/juice-shop/juice-shop
2. Cloned my fork locally.
3. Started the application using Docker.
4. Verified that the homepage loaded.
5.Captured requried screencaps.
6.Branch protection ruleset to mandate PR before merge

##4.Direct Commits and Branch Protection

1. Is there anything wrong with committing directly to the master branch?

Committing directly to the master branch can bypass code review and security checks. 
This increases the risk of introducing bugs, insecure code, or accidental secrets into the main codebase. 
It can also make changes harder to review and manage in a collaborative development environment.

2. How can direct commits be prevented?

GitHub branch protection rules or repository rulesets can be configured to require pull requests before changes are merged into the master branch.
 Developers can push changes to feature branches and submit pull requests for review before merging.

3. Repository settings configured

An active GitHub branch ruleset was configured to target the master branch and require pull requests before merging.


## 5. Homepage screenshot
![Juice Shop homepage](docs/juice-shop-homepage.png/Users/dipikasingh/Documents/GitHub/juice-shop/screenshots/JS\ homepage.png )

