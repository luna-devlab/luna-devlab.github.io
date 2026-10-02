# Exercise 02: Creating own GitHub Page from HTML and CSS

**Name:** Mira Aliyah Pumario Luna

**Degree Program:** BS Computer Science

**Live Website:** https://luna-devlab.github.io

## Steps on How to Create a GitHub Page

1. Created a public repository on GitHub named `luna-devlab.github.io`.
2. Placed `index.html`, `style.css`, and the `images` folder in a local folder with the same name.
3. Initialized the folder as a Git repository using `git init` and renamed the branch to `main` using `git branch -M main`.
4. Set the local username and email using `git config --local user.name` and `git config --local user.email`.
5. Linked the local repository to the remote using `git remote add origin <repo URL>`.
6. Staged and committed the files in separate commits using `git add` and `git commit -m`.
7. Pushed the commits to GitHub using `git push origin main`, with a Personal Access Token in place of the password.
8. In the repository settings, went to Pages and set the source to the `main` branch, `/ (root)` folder.
9. Opened https://luna-devlab.github.io to check the live website.

## Key Takeaways

- Flexbox made the layout much easier to build. I used it for the navigation bar, the project cards, the skills and autobiography section, and the footer without needing floats or positioning.
- GitHub Pages is case-sensitive with file names. My photo was saved as `featured.JPG` while my HTML used `featured.jpg`, which works on my Mac but would break on the live site, so I renamed it to match.
- My first push was rejected because my commits used my private email. I fixed it by using my GitHub noreply email in `git config`.
- Committing in smaller steps keeps the history clear, since each commit shows exactly what part of the page was added.