# quarkus-JsonSubTypes-annotation


Before running the test install this archive in your local repo.
Here is the cmd to do it.

mvn install:install-file \
   -Dfile=___FIX_THIS___/lib/utils-arquillian-utils-4.5.0-SNAPSHOT.jar \
   -DgroupId=org.jboss.resteasy \
   -DartifactId=utils-arquillian-utils \
   -Dversion=4.5.0-SNAPSHOT \
   -Dpackaging=jar 

Execution env.
    jdk 11.0.2
    mvn 3.6.3
    quarkus 1.3.1.Final
    
 
 The failing test is 
  org/jboss/resteasy/test/providers/jackson2/ProxyWithGenericReturnTypeJacksonTest.java   
    
  Set a breakpoint in ProxyWithGenericReturnTypeJacksonTest at line 77.  
    
  Compile project:
    mvn clean test -DskipTests=true
  
  Run tests
    mvn test -Dmaven.surefire.debug






