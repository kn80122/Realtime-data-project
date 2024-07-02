# Realtime Data Project
Realtime Streaming Data Pipeline Engineering.

## Tech Stack
- Python 3.12
- Apache Zookeeper 7.4.0
- Apache Kafka 2.4.0
- Apache Spark 3.5.0
- Docker
- AWS: S3, Glue, Athena, Redshift

## Usage
1. Before Starting Project
```sh
# Build pipenv virtual environment through Pipfile.lock.
pipenv sync
```

2. Start Project
```sh
# Enter pipenv virtual environment.
pipenv shell
```

3. Install Packages
```sh
# Build Apache Zookeeper, Apache Kafka and Apache Spark through docker-compose.yml.
docker-compose up -d
```

4. Run Project
```sh
# Run python file.
python <python_filename.py>
```

5. Exit Project
```sh
# Shut down and delete container.
docker-compose down

# Exit pipenv virtual environment.
exit
```
