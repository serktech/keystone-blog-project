# Keystone Blog

Blog API created with KeystoneJS

Rename config.env to .env and add your database URI

Database: MongoDB Atlas - use Free Tier.
1. Create Cluster
2. Add User at Database Access
3. Allow your IP Access at Network Access
4. Use your credentials in .env

    Example:
   `MONGO_URI = "mongodb+srv://gio123:qwerty@009@cluster0.09xg9.mongodb.net/PROJECT-KEYSTONEJS-GRAPHQLDB?retryWrites=true&w=majority"`



## Running the Project.

Install dependencies with `npm install`

Run `npm run dev`

* Admin UI - `http://localhost:5000/admin`
* Graphiql Client - `http://localhost:5000/admin/graphql`
* API Endpoint - `http://localhost:5000/admin/api`


## Next steps

This example has no front-end application but you can build your own using the GraphQL API (`http://localhost:3000/admin/graphiql`).

Reference to Traversy Media

https://www.youtube.com/watch?v=3cH1BXJbfa4&t=306s
