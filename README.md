<p align="center">
  <img width="150" src="https://probot.github.io/assets/logo.png">
</p>
<h2 align="center">How to build your first GitHub App</h2>

<p align="center">
  <a href="#workshop-pre-requisites">Workshop Pre-requisites</a> •
  <a href="#useful-links-throughout-the-workshop">Useful links</a> •
  <a href="#workshop-steps">Workshop steps</a> •
  <a href="#extend-and-improve-your-app-further">Extend your app further</a>
</p>

<p align="center">
  <a href="https://glitch.com/edit/#!/remix/satellite-workshop-github-apps-start">
    <img src="https://cdn.glitch.com/2703baf2-b643-4da7-ab91-7ee2a2d00b5b%2Fremix-button.svg" alt="Remix With Glitch">
  </a>
</p>

Check back soon for workshop materials :eyes:

---

### Workshop Pre-requisites

- A GitHub.com account

### Useful links throughout the workshop
- Creating an issue
  - API documentation: https://developer.github.com/v3/issues/#create-an-issue
  - Node SDK: https://octokit.github.io/rest.js/#octokit-routes-issues-create
- Creating a check run
  - API documentation: https://developer.github.com/v3/checks/runs/#create-a-check-run
  - Node SDK: https://octokit.github.io/rest.js/#octokit-routes-checks-create
- Getting a single file
   - API documentation: https://developer.github.com/v3/repos/contents/#get-contents
   - Node SDK: https://octokit.github.io/rest.js/#octokit-routes-repos-get-contents
- Page where you can view and re-deliver webhooks: https://github.com/settings/apps/your-app-name/advanced

Follow along live: [Link to come in the workshop]

### Workshop steps
1. Fork the [satelliteworkshops/app-playground](https://github.com/satelliteworkshops/app-playground) repo to your personal account
1. Enable "Issues" for the forked repo via the repo settings
2. Create your Glitch app by following this link: https://glitch.com/edit/#!/remix/satellite-workshop-github-apps-start
3. Wait for Glitch to load and for it to install all the dependencies. You can see progress by clicking on "Tools" and then "Logs" in the bottom left corner
4. Click the "Show" button at the top of the page. A new tab should open and the page should have a "Register GitHub App" button
4. Click the "Register GitHub App" button and choose a name for your GitHub App. A GitHub app will be created for you in the background. Once it is complete you will see a new page that asks you where you want to install your new app.
5. On this page, select the "Only select repositories" and in the dropdown choose the "app-playground" repository that you forked in step 1.
6. In your current tab, go to the app-playground repository. It should be at github.com/your-username/app-playground
7. Then head back to Glitch, it's time to write some code!

### Extend and improve your app further
- Add support for multiple changing dependencies in a single pull request
- Show license information as part of the annotation
- Customise warning/notices
- Add an [action button](https://developer.github.com/changes/2018-05-23-request-actions-on-checks/) to "approve the dependency changes"
- Modify the check “conclusion” based on the changed dependencies
- Experiment further with all the other APIs and build something completely different
