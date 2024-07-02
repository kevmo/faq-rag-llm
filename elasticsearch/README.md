`docker build -t rag-db .`

`docker run --name rag-db-instance -p 9200:9200 -p 9300:9300 -it rag-db`

* --name my-elasticsearch-instance: Names the container for easier reference.
* -p 9200:9200 and -p 9300:9300: Maps the ports from the container to your host, allowing you to interact with Elasticsearch through your local machine’s ports.
* -d: Runs the container in detached mode, meaning it runs in the background.
