# My React Vite Template

This repo template will help you generate a React app using Vite.

## How to clone

Run your preferred method to clone the repo:

```sh
npx tiged <YOUR-GH-USERNAME>/my-react-vite-template#main <new-project-name>
```
```sh
git clone --branch main --single-branch https://github.com/<REPO-CLONE-LINK.git>
```

(Substitute your GitHub username for `<YOUR-GH-USERNAME>` or repo link for `<REPO-CLONE-LINK.git>`)

This command will create a clone of the repo' `main` branch under the name
<new-project-name> in the directory where it is run.

## Initialize your Vite template

After cloning the repo, open the folder in your code editor using `code .`

In your VSCode (or equivalent) terminal, open the server folder and install dependencies:

```sh
cd my-react-vite-template
npm install
```

Then start your Vite server by running `npm run dev`

To convert the template into your own project, update these fields to your project name:

* the `title` in __index.html__
* the `"name"` in __package.json__*

## README.md
A good README will typically explain:

* The purpose of the code / repo
* How to download, clone, or otherwise access the codebase
* How to set up / install the project
* How to use the project
* How to contribute or make changes to the codebase

Update your README file accordingly in your project root.

Before pushing, make sure your local repo's remote is pointed to your Github origin using:

`git remote add origin <your-Github-link>`

Commit your changes using:

`git add .` , `git commit -m "commit message"` , and `git push -u origin main`
