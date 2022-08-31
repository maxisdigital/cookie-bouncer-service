# Cookie Bouncer

This is a dockerised clone of [Simo Ahava's](https://www.simoahava.com/google-cloud/create-cookie-rewrite-web-service-google-cloud/) ["Cookie Bouncer"](https://github.com/sahava/cookie-bouncer-service/) web service.

Its purpose is to provide a POST API endpoint that writes back a first party HTTP cookie.

These cookies are not subject to Safari ITP 2.4 7 day expiry for cookies. Cookies set via this endpoint will be retained for up to 2 years.

## Getting Started

These instructions will cover usage information and for the docker container 

### Usage

#### Environment Variables

* `BASEURL` - A pathname the API will response on. Default is `/cookies`

#### Volumes

* `/usr/src/app` - Path the express app. Potential you could bind to a local folder.

## Built With

* Node 1.22.19
* Yarn 16.17.0

## Find Us

* [Maxis Digital](https://www.maxisdigital.com.au)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

* [Simo Ahava](https://www.simoahava.com)
* Guide: [Create a cookie rewrite web service using the google cloud platform](https://www.simoahava.com/google-cloud/create-cookie-rewrite-web-service-google-cloud/)
* Github: [Cookie Bouncer Service](https://github.com/sahava/cookie-bouncer-service/)