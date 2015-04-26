# Journal App (fullstack project)

### This project is built with Backbone on the frontend and rails on the backend.

A model and controller are built for post in the backend and Backbone model and collection for posts built on the frontend.
Along with Backbone model and collection, Post have index view, index item subview, show view, and form view. Each view is
associated with a backbone route. Views contain an events hash that sends appropriate request to the backend post controller.
Users can create, edit, and view posts. 

To use the app:
  1. `>>rails server`
  2. go to `localhost:3000`
