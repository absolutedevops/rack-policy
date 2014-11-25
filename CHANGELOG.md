0.4.1 (April 25, 2013)

* Fix failing to load view extension in Rails 2.3.x - #2

0.4.0 (July 8, 2012)

* Add helpers module to hold common rack apps extensions together with tests.
* Add extensions loader.
* Add view extensions for Rails 2, 3 & Sinatra.
* Add specs for finish method to verify headers removal.
* Add specs to test for consent token and environment variable setup.

0.3.0 (June 30, 2012)

* Add thread safety.
* Update documentation with usage examples for sinatra, rackup.
* Ensure information type requests don't have body.
* Add sinatra app to code examples.

0.2.0 (June 24, 2012)

* Fix bug when checking allowed cookie.
* Refactor cookie clearing to work off request and response cycle.
* Add cookie deletion.
* Add response headers handling and fix bug with cache revalidation.
* Add code comments.
* Improve documentation with sinatra and rackup examples.
* Add code example for rails 3 app.

0.1.0 (June 23, 2012)

* Add cookie limiter middleware.
* Add spec tests.
