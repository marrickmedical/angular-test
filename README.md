# Bookshelf
## Objective
This test will demonstrate your ability to:
1) Use the [Angular CLI](https://github.com/angular/angular-cli)
    - Scaffold a new project and run a development server.
    - Adding components and services.
2) Make Asynchronous Http Requests
    - [Google Books API](https://developers.google.com/books/docs/v1/getting_started)
3) Build Intuitive UI/UX Design
    - [Material Design](https://material.angular.io/) (feel free to use a CSS Framework like Bootstrap along side Material Design)
4) Use [Typescript](https://www.typescriptlang.org/)
5) Use `git` and `github.com`

## Goal
You will build a 'Bookshelf'. This is a simple one page application. The goal of the application
is to manage a UI Bookshelf that can be:
- Added to
- Deleted from
- Sorted (by at least book name)

There will also need to be a search functionality. A search bar should make requests to the Google Books API and list results to the user allowing them to select their book that will add it to their Bookshelf. The complexity of the search is up to you but it needs to at least search by book name. Listen to input into the search box and make API requests to Google (be sure to `debounce` the input so you are not sending requests on every key press).

***Your code should be clean, easy to follow, and well documented.***

*To clarify:*
- You will be adding books to the UI, not to a users Google Cloud books account.
- We don't expect this to be persistent, but if you choose to make it so, use a Redux Design Pattern with `@ngrx/store`
- You will be using Angular 2+, so be sure you are viewing Google based searches accordingly. Do not view resources that are listed for 'AngularJS'. A good trick is to add 'angular 2' to any Google searches to filter the results.

## Submitting your result
Create a repo on your personal github account that will house all of your code. Once done, let us know @ it.jobs@marrickmedical.com with a link to the repo and we will review the project and let you know from there.

### Good luck! We look forward to seeing your result!
