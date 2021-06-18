# Simple Code Published Repo

This repo was created from VS Code.

1) I opened VS Code (it already has git and node and npm installed)
2) I created a new folder named `simpleCodeRepo`
3) I added this README.md file to the folder
4) I selected the `Source Control` feature of Code
5) I chose the Publish to GitHub option from the panel
6) I entered the name of the repo in the field at the top/center of Code, `simpleCodePublishedRepo`
7) I selected the README.md file listed under the empty text box
8) VS Code created the repo on GitHub and pushed the README.md file there
9) A snackbar appeared in the bottom/right corner of VS Code
10) I selected `Open the repo on GitHub` option

And that's all there was to it.

## Part II

This technique makes a private repo. I needed this repo to be public, so I:

1) opened <https://github.com/mcorning/simpleCodePublishedRepo/settings>
2) scolled to the bottom of the page until I saw the `Danger Zone`
3) Selected `Change repository visibility`
4) copy/paste the repo name in the field
5) Clicked the enabled button

Now you can see this repo, too.

## Part III

Next step is politically correct. In honor of Juneteenth Day tomorrow, I changed the default branch name, `master`, to the new default name (in providers like Heroku and Netlify), `main`.

1) from the home page, <https://github.com/mcorning/simpleCodePublishedRepo>
2) I clicked on the `1 branch` button next to the `master` dropdown
3) I clicked the `edit` icon on the right side of the branch list
4) I entered `main` as the new name
5) I clicked the enabled `Rename branch` button
6) returning to the repo home page, 
   1) you will see a message about the new default branch
   2) use the `copy` button on the right of the dialog box
   3) paste them into VS Code terminal


Alternatively, you can accomplish the same thing with mouse clicks:

1) select the `master*` button in the bottom/left corner of VS Code
2) select `origin/main` from the bottom of the list of branches
3) now you can commit changes to the new branch
