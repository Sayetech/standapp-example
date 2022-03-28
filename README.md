# StandApp Example

# Git Strategy

Never commit and push to main directly.

Always work on the <develop> branch.

## How to use the develop branch

1. Create the develop branch
   `git branch develop`

2. Switch to the develop branch
   `git checkout develop`

## Commit to develop

3. Test your changes

4. Add your files to the staging area.
   `git add .`

5. Commit your changes with a meaningful commit message
   `git commit -m "added <specific work you added>"

## Push Changes

6. Push your changes.
   `git push`
   For your first push, git will ask you to use `git push --set-upstream origin develop`

## Create a Pull Request

Use [this video](https://youtu.be/rgbCcBNZcdQ?t=207) or any like it
