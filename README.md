meteor-react-todos
==================

> Official Meteor/React Todo App tutorial, with Travis CI, ESLint and deployable
> on Heroku

[Live Demo](https://amercier-meteor-react-todos.herokuapp.com/)

Prerequisites
-------------

- [NodeJS](https://nodejs.org/en/) 8+
- [Meteor](https://www.meteor.com/install) 1.7+

Installation
------------

```
npm install
```

Start application
-----------------

```
npm start
```

Open http://localhost:3000/

Run tests
---------

```
npm test
```

Deployment
----------

### Heroku

1. Create a new Heroku app
2. In **Settings** tab: set `https://github.com/AdmitHub/meteor-buildpack-horse.git` as the only buildpack
3. In **Resources** tab: add [mLab MongoDB](https://elements.heroku.com/addons/mongolab) add-on
4. Set `ROOT_URL` config var to `https://<APP NAME>.herokuapp.com`
5. Deploy your app (`git push heroku master` if you are [deploying with Git](https://devcenter.heroku.com/articles/git))

### Others

Please refer to official [Meteor Deployment and Monitoring](https://guide.meteor.com/deployment.html) guide.

License
-------

[ISC](./LICENSE.md)
