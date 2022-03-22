# How to Format and Host Your Resume

## Purpose
This README is intended to serve as an instructional guide for formatting and 
hosting a resume (or other markdown file) on GitHub Pages. This guide is comprehensive
and covers all steps from uploading files to a GitHub repository to hosting a static
webpage containing the resume, along with formatting instructions.  

*Relate steps (Markdown, Markdown Editor (VS Code), GitHub Pages, Jekyll) to Etters general principles

## Prerequisites
- Markdown-formatted resume
- A markdown editor (this tutorial will use [Visual Studio Code](https://code.visualstudio.com/) along with the [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) extension)
- A GitHub account

## Instructions

### Hosting Your Resume on GitHub Pages

#### Creating the Repository
1. Go to [GitHub](https://github.com/) and sign in to your account
2. Click on your profile picture in the top right of GitHub and click on "Your Repositories"
3. Click on the green "New" button
4. Under the text field "Repository name" enter *username*.github.io where *username* is your account username
    - This is needed for hosting your repository's contents on GitHub Pages
5. Ensure that the repository is set to Public and not Private (it should be set to Public by default)
6. Click "Create repository"

#### Adding Files
- **Adding Your Resume**
    1. Open your file explorer and locate your markdown-formatted resume
    2. Rename it to "index.md"
    3. Navigate to your repositories on GitHub and click on your newly created repository
    4. Click the "Add file" dropdown, and then select "Upload files"
    5. Click the blue "choose your files" button, locate/select your markdown-formatted resume, and click open in the file explorer window
- **Adding a Configuration File**
    1. Navigate to your repositories on GitHub and click on your new repository
    2. Click the "Add file" dropdown, and then select "Create new file"
    3. Name the file "_config.yml", this will be the file you use to configure the theme of your static website
    4. Type "theme: jekyll-theme-slate" in the contents of the file (this can be changed later)
    5. At the bottom of the page, write a brief description, and click "Commit new file"
        - E.g., "Added configuration file for jekyll theme"

### Viewing Your Resume on GitHub Pages
Viewing your resume on GitHub Pages is simple as long as you satisfy these requirements:  
1. The name of your repository containing your resume follows the format *username*.github.io
2. The markdown file that is your resume is named index.md
When the above requirements are met, you can enter *username*.github.io into your browser to view your website

## More Resources
Below are several resources that you can (and should!) utilize:
- A good [Markdown tutorial](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- Learn more about technical writing with Andrew Etter's [Modern Technical Writing: An Introduction to Software Documentation](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- AOPSDIASP"ODI **Add a third resource here**

## Authors and Acknowledgements
- Thanks to Ben Balter (and [contributors](https://github.com/pages-themes/slate/graphs/contributors)) for creating the Slate theme used in this tutorial
- Thanks for group 7 from COMP 3040 for reviewing and editing this tutorial

## FAQ
- Why is Markdown better than a word processor?
- I updated my resume, why can't I see the changes?
    - If you updated the contents of your index.md file and committed the changes and cannot see them on the static website, just wait! 
    Github can take several minutes to display new changes when viewed from a static website. If problems persist after 10 minutes, check the
    website from a different device and contact GitHub support if necessary.

**Audience Analysis (To be done in assignment2 submission box)**
Audience: CS Student
Venue: README in GitHub Pages
Purpose: Explain how to host a resume on GitHub Pages.
Additional Purpose: Introduce and demonstrate the principles of Andrew Etter's book Modern Technical Writing
Desired Reaction: Reader (meeting the preprequisites) gains the ability to upload, format, and host a resume using GitHub Pages without requiring external help
Vocabulary: Technical
Tone: Objective, informative, instructional
