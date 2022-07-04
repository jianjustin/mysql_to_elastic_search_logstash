# mysql_to_elastic_search_logstash
Using Logstash pipeline to sync MySQL to Elasticsearch

# Clone this project and cd into it
git clone https://github.com/srajan-agarwal/mysql_to_elastic_search_logstash.git && cd mysql_to_elastic_search_logstash

# Start the whole architecture
docker-compose up # add -d for detached mode

# To keep an eye on the logs
docker-compose logs -f --tail 111 <service-name>
