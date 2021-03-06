In this project, I created an http-client-app in React JS, in which I implemented the following:
- Fetching the **async promise** data from **[JSONplaceholder REST API](https://jsonplaceholder.typicode.com/)** via **[axios](https://www.npmjs.com/package/axios)**.
- Creating the data by **POST** request.
- Updating the data by **PUT** request.
- Deleting the data by **DELETE** request.
- Performing a typical **pessimistic update approach**.
- Performing **optimistic update approach** (update the UI before calling the API to prevent the user from waiting for a response).
- Handling expected and unexpected errors.
- Handling unexpected errors globally.
- Extracting a reusable service and move API url in config.json file.
- Implemented **[Toastify](https://www.npmjs.com/package/toastify-js)** instead of typical JS alert.
- Implemented **[Sentry](https://www.npmjs.com/package/@sentry/browser)** for Logging.
- Complete code refactoring.
 
I used these concepts to implement an end-to-end **[movie management application](https://github.com/Ubaid45/ReactJS_movie-management)** which is deployed **[here](https://desolate-headland-28492.herokuapp.com/movies)**.
