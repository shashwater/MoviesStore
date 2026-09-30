# MoviesStore

A Django movie-store application with user accounts, reviews, a session-based shopping cart, and order history.

## Features

- Browse movies and search the catalog by name.
- Sign up and sign in with Django authentication.
- Create, edit, and delete your own reviews.
- Add movies to a cart and view a calculated total.
- Create an order and view previous orders from your account.

The purchase flow records an order locally. It does not process payments.

## Stack

Python · Django · SQLite · HTML templates

## Structure

| App | Responsibility |
| --- | --- |
| `movies` | Catalog, search, movie detail pages and reviews |
| `accounts` | Authentication and order history |
| `cart` | Session cart, totals and order creation |
| `home` | Home pages |
| `moviesstore` | Settings, URLs and shared templates |

## Status

This is a development project, not a production-ready storefront. Setup instructions and a reproducible dependency file are being checked before publication.
