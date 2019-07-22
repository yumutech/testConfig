# testConfig
spring cloud config

testConfig version 0.0.1 release
1. register erueka
2. get properties config files from local classpath

#add multiple properties config files (local)
1. spring clound server visit url:
   http://localhost:5050/userservice/native
   http://localhost:5050/config-server/native
2. if spring.profiles.active=native is changed to be 'dev','pro' etc,
   the visit url above will not be visited
   