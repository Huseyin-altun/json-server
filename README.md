# Template JSON Server

This repository provides ready to use mock data server. All you need to do is update the [db.json](db.json) file as per your requirements. It utilizes the [json-server](https://www.npmjs.com/package/json-server) package for creating the mock server. You can explore it's [documentation](https://github.com/typicode/json-server#readme) to customize the server.

## Setup

- Set up node:

```
nvm use
```

- Install the dependencies:

```
yarn install
```

- Start the server in development environment:

```
yarn run dev
```

- Goto [http://localhost:8000/](http://localhost:8000/) to verify if the server is working.

- Start the server in production environment (Database State remains unaffected):

```
yarn start
```

- By default the server runs on port 8000. You can add the port in your environment variable as well.

## Deployment

Here are the deployment steps for [Vercel](https://vercel.com), you may use any deployment service as per your need.

- Sign Up or login into Vercel.

- From the Vercel dashboard, click **+ New Project** and then **Import** your repository by providing necessary permissions.

- On the **Configure Project** screen, leave everything default and click **Deploy**.

- Wait until deployment is done, and your own JSON server is ready to serve.

- Vercel supports automatic deployment when a new commit is pushed to the project's default branch.
