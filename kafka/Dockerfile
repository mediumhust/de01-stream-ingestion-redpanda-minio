FROM debezium/connect

RUN curl -O https://hub-downloads.confluent.io/api/plugins/confluentinc/kafka-connect-s3/versions/10.3.1/confluentinc-kafka-connect-s3-10.3.1.zip \
    && unzip confluentinc-kafka-connect-s3-10.3.1.zip \
    && mv confluentinc-kafka-connect-s3-10.3.1 /kafka/connect/ \
    && rm confluentinc-kafka-connect-s3-10.3.1.zip
