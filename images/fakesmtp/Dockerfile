FROM openjdk:18-jdk-buster

ADD http://nilhcem.github.io/FakeSMTP/downloads/fakeSMTP-latest.zip /fakeSMTP-latest.zip
RUN unzip /fakeSMTP-latest.zip && \
    rm /fakeSMTP-latest.zip

EXPOSE 25

ENTRYPOINT ["java","-jar","/fakeSMTP-2.0.jar"]
CMD [ "--background", "--output-dir", "/var/mail", "--port", "2525", "--start-server" ]