This is a Simple Todo App where user can create a new Todo.
We have used **ReactJS** and **HTML5** to implement that application.

User can also Edit the Todo and Delete aswell.


This a check list item of todos. If one task completed User can mark as completed with Red color.
Or else default it will be a Green color to indicate its not completed yet.


There is validation aswell to prevent it from Blank input.


## Folder Structure

After creation, your project should look like this:

```
my-app/
  README.md
  node_modules/
  package.json
  public/
    index.html
    favicon.ico
  src/
    components/
      App.js
      create-todo.js
      todo-list.js
      todo-list-header.js
      todo-list-items.js
    index.css
    index.js

```

For the project to build, **these files must exist with exact filenames**:

* `public/index.html` is the page template;
* `src/index.js` is the JavaScript entry point.

You can delete or rename the other files.

You may create subdirectories inside `src`. For faster rebuilds, only files inside `src` are processed by Webpack.<br>
You need to **put any JS and CSS files inside `src`**, or Webpack won’t see them.

Only files inside `public` can be used from `public/index.html`.<br>
Read instructions below for using assets from JavaScript and HTML.

You can, however, create more top-level directories.<br>
They will not be included in the production build so you can use them for things like documentation.

## Clone The App

 git clone https://github.com/tbagchi85/todo-app.git

## Project Setup

In the project directory, you can run:

### `npm install`

This command installs a package, and any packages that it depends on. If the package has a shrinkwrap file, the installation of dependencies will be driven by that.


### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.



