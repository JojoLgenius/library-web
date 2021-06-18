# library-web

The goal is to build a small web app to manage a library, with users borrowing books, using the [library-api](https://github.com/despatates/library-api) API.

# Excercise

The goal is to create a simple CRUD app using JavaScript.  
The entities models are the following:

**User**

- id
- name

**Book**

- id
- title
- author

Create an API client to query for users and books asynchronously.

For books and users:

- Display a list of entities
- This list must be sortable
- Add an input to filter by name/title/etc.

With the model and the endpoints you created to allow users to borrow a book:

- Build a loan list, with filters on books and users
- Create a form to add new loans
- Add a button to delete a loan

# Bonus

Here are some improvements if you have remaining time. **They are not mandatory** but will be appreciated.

- Feel free to do anything you want...
- Use git and commit your progress.
- Use [bootstrap](https://getbootstrap.com/) to style the app.
- Add authentication on endpoints.
- Use the power of [Vue.js](https://vuejs.org) (v3) to create components.

## Project setup

Use this template to start your project.

If you don't already, install `npm` in your environment.

Install the dependencies of the project:

```sh
$ npm install
```

The launch the app:

```sh
npm run serve
```
