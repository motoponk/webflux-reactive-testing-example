# Reactive TDD with spring-boot [![Build Status](https://travis-ci.org/daggerok/webflux-reactive-testing-example.svg?branch=master)](https://travis-ci.org/daggerok/webflux-reactive-testing-example)
See `reservation-service/src/test/java/com/github/daggerok` tests

Follow guide from git commits...

_run tests_

```bash
./mvnw clean test
```

_run app with embedded mongo_

```bash
./mvnw -f ./reservation-service/pom.xml -P mongoEmbedded spring-boot:run
# or
./mvnw -pl :reservation-service -Dmongo=embedded spring-boot:run
```

resources:

* [YouTube: Bootiful Testing](https://www.youtube.com/watch?v=1W5_tOiwEAc)
