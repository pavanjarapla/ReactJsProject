Server-Side Code:

To run server-side code, you'll need an SSH certificate. Before executing the program, ensure you run npm install as we've removed the node_modules directory.

Client-Side Code:

You can authenticate with any username and password. However, to execute the authentication API, SSH certification is required. I've commented out that code for your convenience. To view this code, navigate to src/views/auth/index.js.

For code related to recipes, explore the src/views/admin/recipe folder.

Routes are defined in routes.js.

For JWT implementation, refer to routeGuard.js.

In this project, we utilized Chakra UI, and the API we interfaced with is: https://www.themealdb.com/.
