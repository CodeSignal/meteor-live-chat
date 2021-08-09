# Live Chat with Meteor!
A simple live chat app written in Meteor

See the [live demo](http://chat.pitchly.net/). Just be nice!

## How to Run
Clone this repo. If you don't already have Meteor, see https://www.meteor.com/install or just run:

```
curl https://install.meteor.com/ | sh
```

Then in your project directory, run:

```
meteor npm install
meteor
```

Open up http://localhost:3000/ and see the result. Trying opening in two different windows!

---

This app was largely made in just two hours, styling aside, and shows the power of Meteor and its real-time capabilities. This sample app covers a few key principles:

- How to use Blaze Templates
- How to publish/subscribe to data from the server
- How to call methods on the server
- How to insert data into MongoDB
- How to deal with data reactively
- How to use Meteor helpers
- How to use Meteor events
- How to import Meteor and NPM third-party packages
- Basic backend validation using Meteor check
- Restricting data access with Meteor.publish

Extra: In this app, we also deal with

- Dates using the moment.js NPM package
- Cookies using the Meteor mrt:cookies package

What this app does not cover:

- Saving local state (aside from cookies)
- Login or auth flows
