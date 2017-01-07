#
Installation

## Clone

Clone the official repository and cd into the directory

```
git clone https://github.com/6aika/issue-reporting.git
cd issue-reporting
```

## Run

A `docker-compose.yml` file is supplied that will start up a 
PostGIS-backed instance on `localhost:8000`.

Simply run

```
env SECRET_KEY=SOMETHING_UNIQUE_AND_SECRET_HERE docker-compose up
```

Watch the process and take note of the SUPERUSER CREDENTIALS. You need 
this for the first log in.

```
web_1 | ===== SUPERUSER CREDENTIALS =====
web_1 | # Username: adminowJ #
web_1 | # Password: Qx0AqJkS #
web_1 | #################################
```

An instance will be available at 
[http://localhost:8000](http://localhost:8000)



