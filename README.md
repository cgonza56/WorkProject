# music-works-api

## Setup

### Local
####Docker

* Run `docker-compose up`
* Run `docker-compose exec web python manage.py migrate`

_Running Management Commands on the Dev Environment_    

* Run `docker-compose exec web python manage.py reconcile <PATH_TO_CSV_FILE>`

### Endpoint
* `GET /music_works/<iswc>/` Retrieve information about the specific iswc.
