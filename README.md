# Introduction

Hi, I'm Lukas.
I'm 35 years old and I like coding.

LIVE LINK of deployed project:
[AquaScape E-Commerce Homepage](https://lrharlekin.github.io/fs17-ecom-static-public/)

## Week 1 Assignment

This assignment aims to practice HTML, CSS and SASS

### Requirement

Create an e-commerce website

1. Git/GitHub

- [x] create a simple `README` file to introduce yourself
- [x] submit the assignment by open a pull request (PR)
- [x] make the repository public
  - [x] Create new public repo on GH
  - [x] Add public repo as 2nd remote to local repo `git remote add <public repo namespace> <public repo URL>`
  - [x] Push to public remote `git push <public repo namespace> <branchname>`
  - [x] **OR** (optional): Set up [multiple push URLs for the same namespace](https://jeffkreeftmeijer.com/git-multiple-remotes/#:~:text=You%20can%20push%20to%20multiple,remote%20with%20multuple%20Push%20URLs.&text=If%20the%20repository%20doesn't,of%20renaming%20an%20existing%20remote.) (e.g. `origin`)
- [x] add label to your PR

2. HTML and Accessibility

- [ ] Make use of different tags: headings, paragraphs, link, italic, ordered list, unordered list,table, form
- [ ] Check out more tags that might be helpful: address, section, article, audio

3. CSS

- [ ] add styling to the HTML file using Flexbox and Grid
- [ ] add basic animation (hover effect, active link styles, typing effect)
- [ ] the web page does not need to be fully responsive, but at least you should have responsive scaling for Flexbox and Grid system.

4. SASS

- [ ] apply SAAS to current project. Make sure to at least use variables and mixins

5. Other

- [ ] Deploy the project
- [ ] Write a readme file to describe your project with few more details

### Sass Folder Structure

A simplified version of the popular 7-1 pattern for structuring SCSS directories was implemented:

Due to the limited scope of the project, the usual 3 sub-folders _/pages_, _/themes_ or _/vendors_ were not necessary, resulting in the following **4-1 structure**:

- **main.scss:** File _only_ contains imports for below partials
- **/abstracts**: Folder contains SASS abstractions, such as variables, mixins, functions, and other utilities
- **/base**: Folder contains resets and typography rules
- **/layout**: Folder contains layout for navigation, header, containers, footer and any grid systems.
- **/components**: Folder contains resusable components, such as buttons, navbars, cards, etc.

```
sass/
|
|- \main.scss
|
|– abstracts/
| |– \_variables.scss // Sass Variables
| |– \_functions.scss // Sass Functions
| |– \_mixins.scss // Sass Mixins
| |– etc.
|
|– base/
| |– \_reset.scss // Reset/normalize
| |– \_typography.scss // Typography rules
|
|– components/
| |– \_buttons.scss // Buttons
| |– \_cards.scss // Cards
| |– etc.
|
|– layout/
  |– \_navigation.scss // Navigation
  |– \_grid.scss // Grid system
  |– \_header.scss // Header
  |– \_footer.scss // Footer
  |– etc.
```
