Building the docs
-----------------

```
bundle exec middleman build --build-dir=docs --clean
```

Getting Started with Slate
------------------------------

### Prerequisites

You're going to need:

 - **Linux or OS X** — Windows may work, but is unsupported.
 - **Ruby, version 2.3.1 or newer**
 - **Bundler** — If Ruby is already installed, but the `bundle` command doesn't work, just run `gem install bundler` in a terminal.

### Getting Set Up

1. Fork this repository on GitHub.
2. Clone *your forked repository* (not our original one) to your hard drive with `git clone https://github.com/YOURUSERNAME/slate.git`
3. `cd slate`
4. Initialize and start Slate. You can either do this locally, or with Vagrant:

```shell
# either run this to run locally
bundle install
bundle exec middleman server

# OR run this to run with vagrant
vagrant up
```

You can now see the docs at http://localhost:4567. Whoa! That was fast!

Now that Slate is all set up on your machine, you'll probably want to learn more about [editing Slate markdown](https://github.com/lord/slate/wiki/Markdown-Syntax), or [how to publish your docs](https://github.com/lord/slate/wiki/Deploying-Slate).

If you'd prefer to use Docker, instructions are available [in the wiki](https://github.com/lord/slate/wiki/Docker).

### Note on JavaScript Runtime

For those who don't have JavaScript runtime or are experiencing JavaScript runtime issues with ExecJS, it is recommended to add the [rubyracer gem](https://github.com/cowboyd/therubyracer) to your gemfile and run `bundle` again.

Companies Using Slate
---------------------------------

* [NASA](https://api.nasa.gov)
* [IBM](https://docs.cloudant.com/api.html)
* [Sony](http://developers.cimediacloud.com)
* [Best Buy](https://bestbuyapis.github.io/api-documentation/)
* [Travis-CI](https://docs.travis-ci.com/api/)
* [Greenhouse](https://developers.greenhouse.io/harvest.html)
* [Woocommerce](http://woocommerce.github.io/woocommerce-rest-api-docs/)
* [Appium](http://appium.io/slate/en/master)
* [Dwolla](https://docs.dwolla.com/)
* [Clearbit](https://clearbit.com/docs)
* [Coinbase](https://developers.coinbase.com/api)
* [Parrot Drones](http://developer.parrot.com/docs/bebop/)
* [Fidor Bank](http://docs.fidor.de/)
* [Scale](https://docs.scaleapi.com/)

You can view more in [the list on the wiki](https://github.com/lord/slate/wiki/Slate-in-the-Wild).

Need Help? Found a bug?
--------------------

[Submit an issue](https://github.com/lord/slate/issues) to the Slate GitHub if you need any help. And, of course, feel free to submit pull requests with bug fixes or changes.

Contributors
--------------------

Slate was built by [Robert Lord](https://lord.io) while interning at [TripIt](https://www.tripit.com/).

Thanks to the following people who have submitted major pull requests:

- [@chrissrogers](https://github.com/chrissrogers)
- [@bootstraponline](https://github.com/bootstraponline)
- [@realityking](https://github.com/realityking)
- [@cvkef](https://github.com/cvkef)

Also, thanks to [Sauce Labs](http://saucelabs.com) for sponsoring the development of the responsive styles.

Special Thanks
--------------------
- [Middleman](https://github.com/middleman/middleman)
- [jquery.tocify.js](https://github.com/gfranko/jquery.tocify.js)
- [middleman-syntax](https://github.com/middleman/middleman-syntax)
- [middleman-gh-pages](https://github.com/edgecase/middleman-gh-pages)
- [Font Awesome](http://fortawesome.github.io/Font-Awesome/)
