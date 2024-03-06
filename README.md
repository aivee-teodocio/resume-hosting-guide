# How to Create a Static Site for Your Resume

## Purpose
This document provides instructions on how to generate a static website using Jekyll and GitHub Pages for your Markdown resume.

## The Principles of Modern Technical Writing
Andrew Etter describes the principles of writing good software documentation in his book, *Modern Technical Writing*. Some of the key principles mentioned are:
- **Use a lightweight static website generator like Jekyll to format documentation.** Lightweight static websites are secure and easy to maintain as they don't need a server and database to function. Additionally, tools like Jekyll also allow us to quickly change the appearance of our documentation by applying different themes.
- **Write documentation in a markup language like Markdown.** As we are writing and editing documentation, markup languages allow us to control the layout and styling of our text. It gives us the ability to create lists, add headers, bold or italicize text, and more, by following a simple set of syntax rules.
- **Use a distributed version control tool like GitHub.** Platforms like GitHub make it easy for people to collaborate and write documentation together. Authors can keep their shared work together in repositories, allowing them to contribute to others' writing, keep track of new changes, and see what others are working on.
Together, we will apply these principles by hosting our resume written in Markdown in a lightweight static website we create using Jekyll and GitHub Pages. 

## Prerequisites
- Have a registered account on GitHub. Sign up [here](https://github.com/join) to create an account.
- Have a Markdown file containing the content of your resume formatted the way you like. Check out this [tutorial](https://www.markdowntutorial.com/) if you are new to Markdown.

## Instructions
### Create a GitHub repository
1. Log into your GitHub account.
2. Click on the green button that says "New" on the left hand side of your GitHub homepage. [1]
3. Enter a repository name with the format `[your-github-username].github.io`. (Ex: *mr-krabs*.github.io)
4. Enter a short description that describes what the repository is for. This could be as simple as *My resume.*
5. Keep the visibility of the repository as *public*.
6. Tick off the box that says *Add a README file*. This will create a Markdown file called *README* and create the repository's `main` branch. By default, this *README* file will contain the name of the repository and the description you entered.
7. Select the "MIT License" option in the *Choose a license* dropdown.
8. Click the green *Create repository* button at the bottom of the page.
You have now created a repository where we can upload and store our files!

### Set up GitHub Pages
1. Inside the repository you just created, click on the *Settings* tab in the top navigation bar. [2]
2. Click on *Pages* on the left-hand side under the "Code and automation" section. [3]
3. Select the `main` option in the first dropdown under the *Branch* section.
4. Keep the second dropdown under the *Branch* section to `/(root)`.
5. Click on the `Save` button in the *Branch* section.
6. Open a new tab in your browser.
7. Enter `https://[your-github-username].github.io` in the address bar of the new tab.
8. Check that you can see the content of your *README* file. You should see your repository's name and description.
You have successfully created a simple static website!👏

## More Resources
- A quick reference sheet on Markdown syntax rules created by Adam Pritchard can be found [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). 

## Authors
- Aivee Teodocio, [@aivee-teodocio](https://github.com/aivee-teodocio)
## Acknowledgements
- Agape Seo, [@gapy04](https://github.com/gapy04) - Helped review this guide
- Eseosa Ataga, [@Marie-Lenora](https://github.com/Marie-Lenora) - Helped review this guide
- Katherine Oelsner, [@octokatherine](https://github.com/octokatherine) - Created the README Template used in this project

## FAQs
#### Question 1
Answer 1
