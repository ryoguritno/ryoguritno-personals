<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# GitHub Pages

_Create a site or blog from your GitHub repositories with GitHub Pages._

</header>

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: previous version checked for empty pull request, changed to the correct theme `minima`.
-->

## Step 2: Configure your site

_You turned on GitHub Pages! :tada:_

We'll work in a branch, `my-pages`, that I created for you to get this site looking great. :sparkle:

Jekyll uses a file titled `_config.yml` to store settings for your site, your theme, and reusable content like your site title and GitHub handle. You can check out the `_config.yml` file on the **Code** tab of your repository.

We need to use a blog-ready theme. For this activity, we will use a theme named "minima".

### :keyboard: Activity: Configure your site

1. Browse to the `_config.yml` file in the `my-pages` branch.
1. In the upper right corner, open the file editor.
1. Add a `theme:` set to **minima** so it shows in the `_config.yml` file as below:
   ```yml
   theme: minima
   ```
1. (optional) You can modify the other configuration variables such as `title:`, `author:`, and `description:` to further customize your site.
1. Commit your changes.
1. (optional) Create a pull request to view all the changes you'll make throughout this course. Click the **Pull Requests** tab, click **New pull request**, set `base: main` and `compare:my-pages`.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.


Certainly! Here's how you can transform the content into a more user-friendly introduction and create a dropdown menu for easy navigation to daily tasks or documentation.
Welcome to My GitHub Pages Blog

✨ Create your own site or blog using GitHub Pages ✨

GitHub Pages is a powerful tool that lets you host a website or blog directly from your GitHub repository. Whether you're sharing your ideas, writing tutorials, or just keeping a personal journal, GitHub Pages makes it easy to get started.
Setting Up Your Blog

🎉 You've turned on GitHub Pages—great start! Now, let's make your site shine.
How to Configure Your Site

Your site settings are stored in a file named _config.yml. This file controls the theme, title, author name, and other important settings for your blog.

For this blog, we're going to use the "minima" theme, which is perfect for blogs. Here's how you can set it up:

    Find the _config.yml file: It's located in the my-pages branch of your repository.
    Edit the file: Add the line theme: minima to your _config.yml file.
    Customize your site: You can also add your site's title, author name, and a short description.
    Save your changes: Commit your changes to update your site.

Optional: Review Changes

If you'd like to see all the changes you've made, you can create a pull request. This will give you an overview of the modifications before they go live.
Explore More

I've added a handy dropdown below where you can find links to daily tasks, additional documentation, or anything else you'd like to include.
<details>
  <summary>Explore More</summary>
  <ul>
    <li><a href="link-to-daily-tasks">Daily Tasks</a></li>
    <li><a href="link-to-documentation">Documentation</a></li>
    <li><a href="link-to-other-resources">Other Resources</a></li>
  </ul>
</details>


<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
