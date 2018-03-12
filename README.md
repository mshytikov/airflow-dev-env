# airflow-dev-env
Simple dev env to run Airflow

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
