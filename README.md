# How to Create a Static Site for Your Resume

<img src="https://github.com/aivee-teodocio/aivee-teodocio.github.io/blob/main/resume-demo.gif" width='600' height='600'>

## Purpose
This document provides instructions on how to generate a static website using Jekyll and GitHub Pages to display your resume.

## The Principles of Modern Technical Writing
Andrew Etter describes the principles of writing good software documentation in his book, *Modern Technical Writing*. Some of the key principles mentioned are:
- ***Use a lightweight static website generator like Jekyll to format documentation.*** Lightweight static websites are secure and easy to maintain as they don't need a server and database to function. Additionally, tools like Jekyll also allow us to quickly change the appearance of our documentation by applying different themes.
- ***Write documentation in a markup language like Markdown.*** As we are writing and editing documentation, markup languages allow us to control the layout and styling of our text. It gives us the ability to create lists, add headers, bold or italicize text, and more, by following a simple set of syntax rules.
- ***Use a distributed version control tool like GitHub.*** Platforms like GitHub make it easy for people to collaborate and write documentation together. Authors can keep their shared work together in repositories, allowing them to contribute to others' writing, keep track of new changes, and see what others are working on.

Together, we will apply these principles by hosting a resume written in Markdown in a lightweight static website created using Jekyll and GitHub Pages. 

## Prerequisites
- Have a registered account on GitHub. Sign up [here](https://github.com/join) to create an account.
- Have a Markdown file containing the content of your resume formatted the way you like. Please check this [tutorial](https://www.markdowntutorial.com/) if you are new to Markdown.

## Instructions
### Create a GitHub repository
1. Log into your GitHub account.
2. Click on the green button that says *New* on the left hand side of your GitHub homepage. <img src="https://github.com/aivee-teodocio/aivee-teodocio.github.io/blob/main/screenshots/1.png" width='60'>
3. Enter a repository name with the format `[your-github-username].github.io`. (Ex: *mr-krabs*.github.io)
4. Enter a short description that describes what the repository is for. This could be as simple as: "*My resume.*"
5. Keep the visibility of the repository *public*.
6. Tick off the box that says *Add a README file*. This will create a Markdown file called *README* and create the repository's `main` branch. By default, this *README* file will contain the name of the repository and the description you entered.
7. Select the *MIT License* option in the *Choose a license* dropdown.
8. Click the green *Create repository* button at the bottom of the page.

You have now created a repository where you can upload and store your files!

### Set up GitHub Pages
1. Inside the repository you just created, click on the *Settings* tab in the top navigation bar. <img src="https://github.com/aivee-teodocio/aivee-teodocio.github.io/blob/main/screenshots/2.png" width='60'>
2. Click on *Pages* on the left-hand side under the *Code and automation* section. <img src="https://github.com/aivee-teodocio/aivee-teodocio.github.io/blob/main/screenshots/3.png" width='60'>
3. Select the `main` option in the first dropdown under the *Branch* section.
4. Keep the second dropdown under the *Branch* section to `/(root)`.
5. Click on the *Save* button in the *Branch* section.
6. Open a new tab in your browser.
7. Enter `https://[your-github-username].github.io` in the address bar of the new tab.
8. At this point, check that you can see the content of your *README* file on your website. You should see your repository's name and description.

You have successfully created a simple static website!

### Displaying Your Resume
1. Find the Markdown file that has your resume content on your computer.
2. Rename that file as `index.md`.
3. Go back to your GitHub repository.
4. Click on `+` symbol next to the green dropdown button that says *Code*. <img src="https://github.com/aivee-teodocio/aivee-teodocio.github.io/blob/main/screenshots/4.png" width='85'>
5. Select the *Upload files* option from that dropdown. This will redirect you to the upload file page.
6. Drag your `index.md` file to the designated box on the screen.
7. Click on the green *Commit changes* button at the bottom of the page. You will be redirected back to the main page of your repository.
8. Go to the *Actions* tab in the top navigation bar. <img src="https://github.com/aivee-teodocio/aivee-teodocio.github.io/blob/main/screenshots/5.png" width='70'>
9. Check that an item in the list of workflows with an orange dot was just added. This means that your changes are currently being uploaded to your website. <img src="https://github.com/aivee-teodocio/aivee-teodocio.github.io/blob/main/screenshots/6.1.png" width='60'>
10. Wait until the orange dot turns into a green checkmark. This indicates that your changes are now live on your website.
![](https://github.com/aivee-teodocio/aivee-teodocio.github.io/blob/main/screenshots/6.png)
11. Go to your website at `https://[your-github-username].github.io`.
12. Check that your resume content is now showing instead the content in your *README* file.

You are now showing your resume on your website! Next, let's apply a theme to make  nicer!

### Applying a Theme Using Jekyll
In this section, we will go over how to apply one of the GitHub Pages supported Jekyll themes.

1. Go to the list of GitHub supported Jekyll themes [here](https://pages.github.com/themes/).
2. Click on the name of the theme you would like to use from the list. This should redirect you to a GitHub repository for that theme.
3. Scroll down until you find the *README* in that repository.
4. In the *README* file, find the *Usage* section.
5. Under the *Usage* section, click on the symbol circled in red to copy the text in the first code block. ![](https://github.com/aivee-teodocio/aivee-teodocio.github.io/blob/main/screenshots/7.png)
6. Go back to your own GitHub repository.
8. Click on the `+` symbol next to the green *Code* button on the main page of your repository.
9. Select the *Create new file* option. This will redirect you to a page with a text editor.
10. Enter `_config.yml` in the box that says `Name your file...` at the top of the text editor. ![](https://github.com/aivee-teodocio/aivee-teodocio.github.io/blob/main/screenshots/8.png)
11. Click anywhere inside the large text box on screen.
12. Paste the text you copied in step 5 into the text box.
13. Hit enter on your keyboard to start a new line.
14. Type `title: Resume` to add a page title to your website.
15. Hit enter on your keyboard to create a new line again.
16. Type `description: [A short description about yourself]`. The description could be as simple as *Hello, my name is [your-name].*
Your `_config.yml` file should look something similar to this (I used the *Minimal* theme in this example): ![](https://github.com/aivee-teodocio/aivee-teodocio.github.io/blob/main/screenshots/9.png)
17. Click on the green *Commit changes* button on the top right of the text editor.
18. In the popup that appears, click the green *Commit changes* button.
19. Go to the *Actions* page in your repository to see the new workflow added.
20. Wait for the workflow to show a green checkmark.
21. Once the workflow is done, go to `https://[your-github-username].github.io`. You should see that your resume now has your chosen theme applied to it.

You are now hosting your resume on GitHub pages with a Jekyll theme!👏

## More Resources
- [Markdown tutorial](https://www.markdowntutorial.com/)
- [Markdown Reference Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [How to add Jekyll Theme to GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll)
- [How to host your site locally](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)

## Authors
- Aivee Teodocio, [aivee-teodocio](https://github.com/aivee-teodocio)
## Acknowledgements
- Agape Seo, [gapy04](https://github.com/gapy04) - Helped review this guide
- Eseosa Ataga, [Marie-Lenora](https://github.com/Marie-Lenora) - Helped review this guide
- Katherine Oelsner, [octokatherine](https://github.com/octokatherine) - Created the README Template used in this project

## FAQs

#### Why are lightweight static websites recommended for hosting documentation?
Lightweight static websites are websites that don't need server-side processing to work, making them a fast and secure way to host documentation. This type of website is good to use when your main interest is sharing information with others and don't need to incorporate a lot of user interactions, such as simply sharing your resume.

#### Why are my new changes not showing on my website?
Check that all workflows in the *Actions* page in your repository have finished. Workflows completed will have a green checkmark next to them. If you see that a workflow has an orange dot next to it, this means that GitHub is still working on updating your website with your changes.
