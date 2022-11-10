FROM flink:java11

# Copy jar file
COPY build/libs/wordcount.jar $FLINK_HOME/usrlib/wordcount.jar

# Copy words file
COPY words.txt $FLINK_HOME/words.txt
