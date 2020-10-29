# Test Commons
This project belongs to following client projects:

* [restrictions-client](https://github.com/eliasnogueira/restrictions-client)
* [simulations-client](https://github.com/eliasnogueira/simulations-client)

## What does this project do?
This is the base project for the client projects with shared `RestClient` class where is responsible for the URL composition used to send the request.

It also contains the configuration class used for the test projects to set the `baseUri`, `basePath` and `port`.

The libraries used in the client are also here, so there's no necessity to import one by one.