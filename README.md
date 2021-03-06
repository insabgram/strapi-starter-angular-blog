# Strapi Starter Angular Blog

Angular starter for creating a blog with Strapi.

This starter allows you to try Strapi with Angular.js with the example of a simple blog. It is fully customizable and due to the fact that it is open source, fully open to contributions. Do not hesitate to add new features etc ...

You may want to know how to develop such a starter by your own! This starter is actually the result of this [tutorial](https://strapi.io/blog/build-a-blog-with-angular-js-strapi-and-apollo)

![screenshot image](/screenshot.png)

### Deploy the backend

To deploy this Strapi instance you'll need:

- [An Heroku account](https://signup.heroku.com/) for free
- [A Cloudinary account for saving images](https://cloudinary.com/users/register/free) for free

Once you have created these accounts you can deploy your instance by clicking on this button

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/strapi/strapi-starter-angular-blog)

### Features

- 2 Content types: Article, Category
- 2 Created articles
- 3 Created categories
- Permissions set to `true` for article and category
- Responsive design using UIkit

### Pages

- "/" display every articles
- "/article/:id" display one article
- "/category/:id" display articles depending on the category

### Getting started

**Clone the repository and install dependencies**

```bash
git clone https://github.com/strapi/strapi-starter-angular-blog.git
cd strapi-starter-angular-blog
```

### Start the backend server

```bash
cd backend

# Using yarn
yarn
yarn develop

# Using npm
npm install
npm run develop
```

### Start the frontend server

```bash
cd frontend

# Using yarn
yarn
yarn develop

# Using npm
npm install
npm run develop
```

Angular server is running here => [http://localhost:4200](http://localhost:4200)
Strapi server is running here => [http://localhost:1337](http://localhost:1337)

Enjoy this starter
