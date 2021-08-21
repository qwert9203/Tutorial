

<!-- TABLE OF CONTENTS -->
## Table of Contents
<!-- <details open="open"> -->
<!--   <summary>Table of Contents</summary> -->
  <ol>
     <li>
      <a href="#what-is-vs-code">What is VS Code</a>
    </li>
    <li>
      <a href="#inital-step-flow">Inital Step Flow</a>
    </li>
    <li>
      <a href="#doing-the-task-step-flow">Doing the Task Step Flow</a>
    </li>
    <li>
      <a href="#download-vs-code">Download VS Code</a>
    </li>
    <li>
      <a href="#getting-started">Installation Extension</a>
    </li>
    <li>
      <a href="#install-git">Install Git</a>
    </li>
    <li>
      <a href="#setup-github-account">Setup GitHub Account </a>
    </li>
    <li><a href="#copy-https-link">Copy HTTPS Link</a></li>
    <li><a href="#clone-repository">Clone Repository</a></li>
    <li><a href="#branch-repository">Branch Repository</a></li>
    <li><a href="#commit">Commit File</a></li>
    <li><a href="#push-to-the-repository">Push to the Repository</a></li>
    <li><a href="#compare-and-pull-request">Compare and Pull Request</a></li>

  </ol>

<!-- </details> -->
---
## What is VS Code

Visual Studio Code is a source-code editor made by Microsoft for Windows, Linux and macOS.Features include support for debugging, syntax highlighting, intelligent code completion, snippets, code refactoring, and embedded Git. 
Users can change the theme, keyboard shortcuts, preferences, and install extensions that add additional functionality.

---

## Inital Step Flow
Step 1. <a href="#download-vs-code">Download VS Code</a> <br/>
Step 2. <a href="#install-git">Install Git ( If you have downloaded git / git command, then skip)</a> <br/>
Step 3. <a href="#setup-github-account">Setup GitHub Account </a> <br/>
Step 4. <a href="#copy-https-link">Copy HTTPS Link</a><<br/>
Step 5. <a href="#clone-repository">Clone Repository</a><br/>
Step 6. <a href="#branch-repository">Open Branch Repository</a> <br/>
Step 7. <a href="#commit">Commit File</a><br/>
Step 8. <a href="#push-to-the-repository">Push to the Repository</a> <br/>
Step 9. <a href="#compare-and-pull-request">Compare and Pull Request</a><br/>

---

## Doing the Task Step Flow
Step 1. <a href="#branch-repository">Open Branch Repository</a> <br/>
Step 2. <a href="#commit">Commit File</a><br/>
Step 3. <a href="#push-to-the-repository">Push to the Repository</a> <br/>
Step 4. <a href="#compare-and-pull-request">Compare and Pull Request</a><br/>

---
<!-- ABOUT THE PROJECT -->
## Download VS Code
1. Download [VS Code](https://code.visualstudio.com/download)

---
### Installation Extension
To install some library for VS Code

<!-- This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [Bootstrap](https://getbootstrap.com)
* [JQuery](https://jquery.com)
* [Laravel](https://laravel.com) -->

---

## Install Git

**If you still do not download git command on your company, Please follow the below step.** <br/>
- Git for Linux  <br/>

  Step 1. Open a terminal:
  ```
  sudo apt-get install git
  ```
  Step 2. Verify the installation was successful by typing git --version:
  ```
  apt-get install git
  ```
<br/>

- Git for Mac Installer <br/>

  Step 1. Download the latest Git for [Mac installer](https://sourceforge.net/projects/git-osx-installer/files/).

  Step 2. Follow the prompts to install Git.

  Step 3. Open a terminal and verify the installation was successful by typing git --version:
  ```
  git --version
  ```
<br/>

- Git for Window Installer <br/>

  Step 1. Download the latest Git for [Git](http://git-scm.com/download/win).
  
  Step 2. Download 32 bits / 64 bits version .exe file
  
  Step 3.1. Please tick the circled check box
      <img src="https://github.com/cityuRobocon2022/template/blob/main/readme-photos/git/git-window-install1.png"/>

  Step 3.2, You can select any text editor you want in the dropdown menu below
           <img src="https://github.com/cityuRobocon2022/template/blob/main/readme-photos/git/git-window-install2.png"/>

  Step 3.3. Select the custom options that you may want ot use

---
<!-- GETTING STARTED -->
## Setup Github Account

Configure your Git username and email using the following commands, replacing Emma's name with your own. These details will be associated with any commits that you create:

- Username

```
git config --global user.name "<Your username>"
```

- Email
```
 git config --global user.email "<Your email>"
```
---
## Copy HTTPS Link
On GitHub, navigate to the main page of the repository.

Step 1. Above the list of files, click  Code.

Step 2.To clone the repository using HTTPS, under "Clone with HTTPS", click the logo
<img src="https://github.com/cityuRobocon2022/template/blob/main/readme-photos/git/github-clone.png" />

---

## Clone Repository

Clone a repository from GitHub to your local computer to make it easier to fix merge conflicts, add or remove files, and push larger commits. When you clone a repository, you copy the repository from GitHub to your local machine.

Step 1.
- For MacBook key shortcut: </br>
    Command + shift + P

- For Window shortcut: </br>
    Ctrl + shift + P

Step 2. 
  Type git Clone
  <img src="https://github.com/lukluke/roboconPhoto/blob/main/vscode-clone.png" />

Step 3.
  Paste HTTPS Link
  <img src="https://github.com/lukluke/roboconPhoto/blob/main/vscode-clonePasteLink.png" />

---
<!-- This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ``` -->

### Branch Repository

A branch is essentially is a unique set of code changes with a unique name. Each repository can have one or more branches. <br/><br/>
  Step 1.	Click the left “network logo” </br>
  Step 2.	Click the Branches </br>
  Step 3.	Click the “+” </br>
  Step 4.	Type the message ( Please follow the format ) 
  <img src="https://github.com/lukluke/roboconPhoto/blob/main/vscode-branch.png" />
  <br/>
  Step 5. Click “Create Branch and Switch”!
  <img src="https://github.com/lukluke/roboconPhoto/blob/main/vscode-branch-swtich.png" />
  <br/>
  Step 6. You will see the new branch in the branches
  <img src="https://github.com/lukluke/roboconPhoto/blob/main/vscode-branch-result.png" />

---
<!-- 


1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```JS
   const API_KEY = 'ENTER YOUR API';
   ```
 -->


<!-- USAGE EXAMPLES -->
## Commit
***Git commit*** creates a commit, which is like a snapshot of your repository. These commits are snapshots of your entire repository at specific times. You should make new commits often, based around logical units of change. Over time, commits should tell a story of the history of your repository and how it came to be the way that it currently is. Commits include lots of metadata in addition to the contents and message, like the author, timestamp, and more.

***Unstaged changes*** exist in your working directory, but Git hasn’t recorded them into its version history yet. You’ll usually want to stage them (mark them to become part of your next commit) or discard them by restoring the last committed version of the file.

***Staged changes*** are a lot like unstaged changes, except that they’ve been marked to be committed the next time you run git commit. Upon your next commit, your staged changes become part of your Git history. git status will no longer list them as changes since they’re part of your last commit now.

Step 1.	Click the left “network logo” <br/>
Step 2.	Click the Source Control <br/>
Step 3.	Click the “+” from Changes to Staged Changes <br/>
Step 4.	Type the message ( Please follow the format ) <br/>
<img src="https://github.com/lukluke/roboconPhoto/blob/main/vscode-commit.png" />
 <br/>
Step 5. Click the logo
<img src="https://github.com/lukluke/roboconPhoto/blob/main/vscode-commit-click.png" />


---
<!-- Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_ -->



<!-- ROADMAP -->
## Push to the Repository
Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch , but whereas fetching imports commits to local branches, pushing exports commits to remote branches.
<br/>

Step 1.	Click the Branches  <br/>
Step 2.	Click the “cloud logo “  <br/>

<img src="https://github.com/lukluke/roboconPhoto/blob/main/vscode-pushtorepso.png" />
 <br/>
Step 3. Choose your benches to publish to the repository

<img src="https://github.com/lukluke/roboconPhoto/blob/main/vscode-pushtorepsoChoose.png" />

---
<!-- See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a list of proposed features (and known issues). -->


<!-- CONTRIBUTING -->
## Compare and pull request
Create a pull request to propose and collaborate on changes to a repository. These changes are proposed in a branch, which ensures that the default branch only contains finished and approved work. <br/>

Step 1.	Go to Github Repository <br/>
Step 2.	Click “Compare & pull request” <br/>

<img src="https://github.com/lukluke/roboconPhoto/blob/main/github-compareAndRequest.png" />
<br/><br/>

Step 3. Code review and Click Assignees <br/>

<img src="https://github.com/lukluke/roboconPhoto/blob/main/github-compareAndRequestDetails.png" /> 
<br/><br/>
Step 4. If ok , click the “create pull request”

<img src="https://github.com/lukluke/roboconPhoto/blob/main/github-compareAndRequestOk.png" /> <br/>

---


<!-- 
Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
<!-- ## License

Distributed under the MIT License. See `LICENSE` for more information. -->



<!-- CONTACT -->
<!-- ## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)
 -->


<!-- ACKNOWLEDGEMENTS -->
<!-- ## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [Sticky Kit](http://leafo.net/sticky-kit)
* [JVectorMap](http://jvectormap.com)
* [Font Awesome](https://fontawesome.com) -->





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
<!-- [contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png -->
