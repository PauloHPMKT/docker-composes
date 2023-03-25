## Docker composes

</hr>

<h3>Kafka default connection - confluent image</h3>
#
<p>
Note: If you're running your application into container (in Docker) context you should appoint its host into container context
Ex:
  your API is up into docker compose network: docker-network:port, your KAFKA_ADVETISED_LISTENERS should appoint to the service where Kafka is generated
  service: kafka ==> into your brokers connection use ['kafka:PORT_KAFKA_CONTAINER']
</p>
</br></br>
<h3>MongoDB - oficial mongo image</h3>
#
<p>
Note:
 * To set mongo into your API connection is important to configure your host with container' service name
 * To access your database through Compass set the IP address of your host do create a comunication

Ex: uri-mongo ## mongodb://"container-name":27017/"database-name"?authSource="collection"</p>
