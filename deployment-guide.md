---
description: Follow the steps listed on this page to deploy your version of DIY Portfolio.
---

# 🚚 Deployment Guide

1. **Fork the DIY Portfolio Repository:** Go to the GitHub page for the DIY Portfolio repository at [https://github.com/ManishReddyN/diy-portfolio](https://github.com/ManishReddyN/diy-portfolio). Click the "Fork" button in the top right corner to create a fork of the repository under your GitHub account.
2. **Create a Vercel Account:** If you don't have a Vercel account, sign up for one at [Vercel](https://vercel.com/).
3. **Connect Your GitHub Account to Vercel:**
   * Log in to your Vercel account.
   * In the Vercel dashboard, click on the "Add New…" button to create a new project.
   * Choose "Import Git Repository" and select your forked version of DIY Portfolio repository from the list.
   * Connect your GitHub account to Vercel if prompted.
4. **Configure Project Settings:**
   * Vercel will automatically detect that your project is a Next.js application.
   * Configure the build settings if necessary. The default build command for Next.js is usually `npm run build`, and the output directory is `./out`.
5.  Setup Environment Variables:

    * Follow the steps in [Creating env variables](creating-env-variables.md) page and add 3 env variables with keys as NOTION\_API\_KEY, NOTION\_DB\_ID, NOTION\_USER\_ID. Replace the values with your values.

    <figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>
6. **Deploy Your Project:**
   * Click on the "Deploy" button to start the deployment process.
   * Vercel will build and deploy your DIY Portfolio application.
7. **Access Your Deployed Site:**
   * Once the deployment is complete, Vercel will provide you with a URL for your deployed site (e.g., `https://diy-portfolio.vercel.app`).
   * Visit this URL in your web browser to see your live DIY Portfolio.
8. **Optional: Configure Domain and Settings:**
   * If you have a custom domain, you can configure it in the Vercel settings.
   * Explore Vercel settings for additional configuration options based on your project's requirements.

***

## Next Steps ⏭️

1. Clone your repository locally or go to your GitHub repository page to edit the `data.json` file - follow steps in [Configuring 'data.json'](configuring-data.json.md) page to do the necessary changes to the file.
2. Test your changes locally by installing the requirements using `nmp ci` command and then using `npm run dev` command from the command line of your local repository folder. (Requires latest LTS version of Node.js to be installed locally)
3. Commit and push your changes to reflect in the GitHub repository. The changes will be picked up by Vercel and your site will be redeployed with your details.

***

## Future Updates 🔮

1. **Navigate to Your Forked Repository:**
   * Go to your forked repository on GitHub (e.g., https://github.com/your-username/diy-portfolio).
2.  **Click on the "Sync Fork" Button:**

    * On your repository page, look for the "Sync" or "Sync fork" button.
    * Click on this button to synchronize your fork with the latest changes from the original repository.

    The "Sync" action combines the steps of fetching upstream changes and creating a pull request into a single button for convenience.
3. **Review Changes:**
   * GitHub will automatically fetch changes from the original repository and display them in the "Syncing" section.
   * Review the changes to ensure they are what you want to update in your fork.
4. **Confirm Sync:**
   * After reviewing the changes, confirm the synchronization or merging process.
5. Make the required changes according to changelog locally and push for a new deployment.

