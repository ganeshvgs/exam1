Steps to Ensure Only Reviewed Code Goes to Master (GitHub + Git)
1. Admin sets branch protection
o Go to Repo → Settings → Branches → Add Rule.
o Protect master branch:
▪ Require pull request before merging
▪ Require code review approval
▪ Block direct commits.
2. Contributor clones repo
3. git clone https://github.com/org/repo.git
4. cd repo
5. Contributor creates feature branch
6. git checkout -b feature-A
7. Commit changes
8. git add .
9. git commit -m "Added feature A"
10.Push branch to GitHub
11. git push origin feature-A
12. Contributor opens Pull Request (PR)
o On GitHub: feature-A → master.
13.Admin/Reviewer reviews & merges
o Only after approval, PR is merged → master branch is updated with
reviewed code.
