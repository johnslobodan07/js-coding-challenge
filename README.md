## Overview

To complete this challenge, you will need to write a simple [React](https://facebook.github.io/react/) or [Angular](https://angular.io/) or [Vue JS](https://vuejs.org/) based web app, and provide us the source files to be built.

The purpose of this challenge is to assess your **skills and approach to composing a simple web app** given a set of screens, and an API feed. We will also assess the **generated HTML, CSS, and JS** output.

This challenge is expected to take about 12 hours.

## The Challenge

Using the provided screens as a reference, you'll need to build a set of React/Vue/Angular components to render the app. You'll also need to request a JSON feed, filter that data, and use the relevant fields.

We'll be looking for **simple, well-designed, performant, and tested code** in the submission.

Please include a `README` with setup instructions, and any other document you created as part of your solution.

Also, add the following info to your `README`:

- How did you decide on the technical and architectural choices used as part of your solution?
- Are there any improvements you could make to your submission?
- What would you do differently if you were allocated more time?

## Details

You will need to build the following 3 pages with React/Angular/Vue:

- A "Home" page
- A "Series" page
- A "Movies" page

The deployable solution should be built in a folder named **`dist`** with an entry point file of **`index.html`**.

Please create components for each part of the page (eg. header, content/store, footer, etc).
Assets are provided in the `assets` folder.

The pages should also be responsive on desktop, mobile and tablet devices.


### "Home" Page

Refer to the [screens/1-home.jpg](./screens/1-home.jpg) screen.

This will be your `index.html` screen.

You will need to display 2 tiles, which link to the "Series" page and the "Movies" page.

### "Series" and "Movies" Pages

Refer to the [screens/2-series.jpg](./screens/2-series.jpg) and [screens/3-movies.jpg](./screens/3-movies.jpg) screens.

For each page you will need to consume this API (https://raw.githubusercontent.com/amawalla/js-coding-challenge/master/feed/sample.json), then:

- Display the first 21 `entries`
- Where the entry has a `releaseYear` attribute value >= `2010`
- Sorted by the `title` attribute value in ascending alphanumeric order

For the "Series" page filter on:

- Where the entry has a `programType` attribute value of `series`

For the "Movies" page filter on:

- Where the entry has a `programType` attribute value of `movie`

The attributes you should use to display the entries are:

- `title`
- `images` → `Poster Art` → `url`

You will also need to handle the loading and error states of fetching the JSON feed from API:

- "Loading" state [screens/1.1-loading.jpg](./screens/1.1-loading.jpg)
- "Error" state [screens/1.2-error.jpg](./screens/1.2-error.jpg)

## Note
Please deploy the app to the server and share the url. Server details have been shared via email.

## FAQ

### What language, framework, build tool... should I use?

You may use whatever you like as long as the solution is built using [React](https://facebook.github.io/react/), [Angular](https://angular.io/) or [Vue JS](https://vuejs.org/).

You can use any CSS framework you wish ie Bootstrap, Tailwind etc.

## Other Notes

Please send through any other code or projects that you're proud of and would like to share with us.

