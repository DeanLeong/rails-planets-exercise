# HOMEWORK: RAILS PLANETS!!!

![orbits](https://iwsmt-content-ok2nbdvvyp8jbrhdp.stackpathdns.com/2282013232750iAtC2afkODS6U.gif)

### Overview

Tonight you'll be making a little baby rails app about PLANETS!

### Getting Started

Fork and clone this repo.

Create a new rails project called planets with a postgresql database, skipping test files, and skip making a git repo.

```
rails new planets --database=postgresql --skip-test -G
```

`cd` into the rails app.

Create the database:

```
rails db:create
```

### Assignment


[Here is your planet object!](./planets.rb) Use it wisely...

You'll be creating a bunch of routes & views using this object!

- `/`: Should have a welcome message and a link to the planets page
- `/planets`: Has a list of all the planets! (Don't hardcode this list! Just use the object. [Maybe one of our ruby methods could help...](https://ruby-doc.org/core-2.4.2/Hash.html#method-i-each))
- `/planets/:planet`: Returns information about that specific planet
- `/planets/random`: Returns a random planet

### Bonus!!

- Style it up! Flex those flexbox muscles.
