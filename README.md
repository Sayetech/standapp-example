# StandApp Example

# Git Strategy

Never commit and push to main directly.

Always work on the <develop> branch.

## How to use the develop branch

1. Create the develop branch

   ```cmd
   git branch develop
   ```

2. Switch to the develop branch
   ```cmd
   git checkout develop
   ```

## Commit to develop

3. Test your changes

4. Add your files to the staging area.

   ```cmd
   git add .
   ```

5. Commit your changes with a meaningful commit message
   ```cmd
   git commit -m "added <specific thing you added>"
   ```

## Push Changes

6. Push your changes.
   ```cmd
   git push
   ```
   For your first push, git will ask you to use
   ```cmd
   git push --set-upstream origin develop
   ```

## Create a Pull Request

Use [this video](https://youtu.be/rgbCcBNZcdQ?t=207) or any like it

7. Go to the `Pull requests` tab

8. Click on `New pull request`

9. You should see `base:main` and `compare:main` buttons. On the `compare:main` button and set it to `compare:develop`

10. After checking your changes, click on `Create pull request`

11. Fill in the details in `Title`. The title should be what the pull request is about

12. Set reviewer to `Emmanuel Nkrumah Sarpong`

13. Click create pull request.

And that is it! you are done!
