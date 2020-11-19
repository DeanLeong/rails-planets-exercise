# RAILS PLANETS!!!

![orbits](https://iwsmt-content-ok2nbdvvyp8jbrhdp.stackpathdns.com/2282013232750iAtC2afkODS6U.gif)

### Overview

Tonight you'll be making a little baby rails app about PLANETS!

### Getting Started

Fork and clone this repo.

Create a new rails project called planets with a postgresql database, skipping test files, and skip making a git repo.

```
rails new . -MT --skip-active-storage --api --database=postgresql
```

`cd` into the rails app.

Create the database:

```
rails db:create
```

### Assignment


[Here is your planet object!](./planets.rb) Use it wisely...

You'll be creating a bunch of routes using this object!

- `/planets`: Has a list of all the planets!
- `/planets/:planet`: Returns information about that specific planet
- `/planets/random`: Returns a random planet
