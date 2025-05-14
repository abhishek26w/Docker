# OS with Env ( base image )

FROM openjdk:17

# working Directory

WORKDIR /app


#code

COPY src/Main.java /app/Main.java

#Libraries

RUN javac Main.java

#Run

CMD ["java","Main"]
