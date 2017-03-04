## Kata of a simple web application package as a docker using docker-maven-pluging

## Commands for test it

#### Build the docker image  
    mvn clean package -DskipTests=true

#### Start the docker container
    mvn io.fabric8:docker-maven-plugin::start

#### Remove the docker container	
    mvn clean