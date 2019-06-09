To reproduce the issue, first deploy the `mp-library` module to the local Maven repo by running
```
./gradlew clean :mp-library:publishToMavenLocal
```
Then run
```
./gradlew sayHello
```
