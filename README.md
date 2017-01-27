# Callbacks vs. Promises

Starter exercise, to be used during live code

Contains starter static data, run with a simple http server, access via `/api` route

ex:

```sh
live-server
```

## Setup

create `index.html`

1. create an html5 document
1. in the body, add an empty div with id `output`
1. in the body, add a button with id `get_users` and inner text `Get All Users`
1. in the body, add a button with id `get_user` and inner text `Get Single User`
1. in the body, import the jQuery library
1. in the body, import `./js/callbacks.js`
1. in the body, import `./js/promises.js`

create `js/callbacks.js` source file
create `js/promises.js` source file

## Goals

1. get user from `/api/user.json`
2. get first id of user friend ids
3. get friend from api
4. get image for friend
5. render image to page
