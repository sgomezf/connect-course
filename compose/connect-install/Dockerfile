FROM cnfldemos/cp-server-connect-datagen:0.3.2-5.5.0
# install connect for elasticsearch and mongodb
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-elasticsearch:5.5.1
RUN confluent-hub install --no-prompt jcustenborder/kafka-connect-twitter:0.3.33

