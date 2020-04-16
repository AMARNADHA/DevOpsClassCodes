FROM Open JDK:8
EXPOSE 8080
ADD target/addressbook.war addressbook.war
ENTRYPOINT ["java", "-jar","/adressbook.war"]
