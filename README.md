# airflow-dev-env
Simple dev env to run Airflow

## Dependencies

Airflow doesn't support Python 3.7 yet, 3.6 is recommended.

### Mac: 
Add `export SLUGIFY_USES_TEXT_UNIDECODE=yes` to your `.bash_profile`

### Windows
Set environment variable `SLUGIFY_USES_TEXT_UNIDECODE` to 'yes'

## Setup
Run:
```
docker-compose run --rm app ./bin/setup
```

## Usage

Start Airflow UI
```
docker-compose up app scheduler
```

UI should be available on http://localhost:8080

Run Airflow via CLI just enter a container

```
docker-compose run --rm app bash
```
