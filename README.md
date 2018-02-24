# Ruby on Rails Tutorial sample application

This is the sample application for [*Ruby on Rails Tutorial: Learn Web Development with Rails*](http://railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).

## License

All source code in the Ruby on Rails Tutorial is available jointly under the MIT license and the Beerware License. See [LICENSE.md](LICENSE.md) for details.

## Getting Started

To get started with the app, clone the repo and then install the needed gems: 

```apple js
$ bundle install --without production
```

Next, migrate the database: 

```apple js
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly: 

```apple js
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server: 

```apple js
$ rails server
```

For more information, see the [*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book).