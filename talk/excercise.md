# Excercise 

1. Install github desktop. [Download](https://desktop.github.com/)

2. Create a github account. [Sign up](https://github.com/signup)

   Installation likely prompts for you to create an account, so you most likely have done this step.

3. Fork the github-demo repository. [FRC7660/github-demo](https://github.com/FRC7660/github-demo).

   You can do this in the web ui at the link above.

4. Clone the github-demo to your local system.

   * Make the repository in \users\YOURUSERNAME\src - my local path was C:\Users\scott\src\github-demo
     You'll put source code and git repositories under this directory.
   * Fork the repository ([doc](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop).)  When prompted you want "**To contribute to the parent project**".

   * At this point you have 
     * a fork of github-demo on your github accunt (mine is https://github.com/smoser/github-demo).
       * a branch 'main'
       * You can push commits to this fork or create new branches.
     * a local repository: \Users\<username>\src\github-demo) which is a clone of your fork.
       * a remote named 'origin' pointing to your  - You can push your local to this remote.
       * a remote named 'upstream' pointing to frc7660/github-demo - You cannot push to this remote.

5. Create a pull request with a change to one of the files.

   * Create a local branch based off upstream 'main'.  Name it 'feature/best-ice-cream' or something to that effect.
   * Open VSCode (or another editor)
   * Make the change
   * Commit the change with commit message describing your change.
   * Make a pull request.

6. Add your name to the list of team members in awesome-users.md
   * Create another branch named 'feature/new-awesome-user'
   * Make the change
   * Commit the change
   * Make a pull request

7. Figure out who added Notre Dame to the list of schools.  And tell Mr. Moser who it was.
