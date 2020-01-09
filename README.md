# Laravel Auth0 Integration Demo

This demo application shows how you can integrate Auth0 authentication into a simple Laravel application. It's based on [this tutorial where we build a GOT character list](https://auth0.com/blog/creating-your-first-laravel-app-and-adding-authentication/) with Laravel and Auth0.


## Installation

**Clone the repo**

```bash
git clone https://github.com/auth0-blog/laravel-got
```

**Switch into the newly created repo folder**

```bash
cd laravel-got
```

**Install the dependencies**

```bash
composer install
npm install
```

**Create the `.env` file**

```bash
mv .env.example .env
```

**Generate encryption key**

```bash
php artisan key:generate
```

**Sign up for Auth0 account**

This application requires users to login. To do this, you need to [sign up for a free Auth0 account](https://auth0.com/signup).

There are three Auth0 values you'll need to fill in in your `.env` file. You can find the in the Auth0 dashboard.

```
AUTH0_DOMAIN=your-auth0-domain.auth0.com
AUTH0_CLIENT_ID=your-client-id
AUTH0_CLIENT_SECRET=your-client-secret
```

## Run the application

```
php artisan serve
```
