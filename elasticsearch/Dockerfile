# Use the official Elasticsearch base image
FROM docker.elastic.co/elasticsearch/elasticsearch:8.4.3

# Set environment variables for Elasticsearch
ENV discovery.type=single-node
ENV ES_JAVA_OPTS="-Xms512m -Xmx512m"

# Expose ports for HTTP and internal communication
EXPOSE 9200 9300

# Automatically start Elasticsearch when the container launches
CMD ["elasticsearch"]
