# Clone repositories
```sh
git clone git@github.com:Serveis-Neby/repository.git
```
# Get changes on any branch
```sh
git pull --all
```
# Start developing a task (the branch name must always follow the same structure)
```sh
git checkout develop
git checkout -b task/<num-task>-<name-task>
```
Example:
```sh
git checkout -b task/37-implementing-user-authentication-middleware
```
# Add changes to the stage
```sh
git add .
```
# Create commit (commits should follow always the same structure and be as small and specific as possible)
```sh
git commit -m "task #37: middleware created"
```
# Push changes on the remote branch
```sh
git push --all origin
```
# Merge changes
To merge changes, it must ALWAYS be done from GitHub through a pull request
