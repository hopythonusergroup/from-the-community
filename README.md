# Open source projects from the community, by the community and for the community

---

## Contributing

---

1. Navigate to the [Python Ho](https://github.com/hopythonusergroup/from-the-community) website repo on GitHub. In the upper right hand corner of the repo, click the "Fork" button. Alternatively, click on an individual file and click the pencil icon. GitHub will automatically fork the repo for you.
2. Head over to your GitHub account, where you will find the forked repo. This is a copy of the official code. Your changes to this forked code will not affect the official code, unless you submit a pull request and an admin merges your pull request.
3. For changes that do not need to be tested locally, the change can be made and submitted in the browser.
4. Within your forked repo, make sure the "Branch" tab is set to the develop branch.
5. Once you are on the correct branch, navigate to the file you intend to change and click the pencil icon to open it. Make the change and click the "Commit changes" button.
6. Clone your forked repo locally via the terminal, replacing the username in the URL with your own (note: not all operating systems will use a $ as a terminal prompt).
`https://github.com/<your-username-here>/from-the-community.git`
7. Change directory into the folder
`cd from-the-community`
8. Verify that you are on the develop branch
`git branch`

### add your code and make a PR

After you have made your changes, you will need to push the local files with the changes back to GitHub in order to submit a pull request. Assuming you are still on the develop branch, you will be pushing your changes from the local develop branch to the develop branch of the forked repo at your GitHub account.

```
git add .
git commit -m "Your commit message"
git push origin develop
```

If there is anything to improve further with the contribution guide, please kindly send us a hello at <ho@pythonghana.org> or go ahead and make a PR with a fix and we will be glad to take a look :joy
