## Building Spring Boot Web Applications Samples

NOTE: You can open this sample inside an IDE using the [IntelliJ native importer](https://www.jetbrains.com/help/idea/gradle.html#gradle_import_project_start) or [Eclipse Buildship](https://projects.eclipse.org/projects/tools.buildship).

This sample shows how a Spring Boot Web application can be built with Gradle.
The application was generated using the [Spring Initializr](https://start.spring.io/#!type=gradle-project).

To build and run the application:

```
./gradlew bootRun
```

```
> Task :app:bootRun

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::        (v2.2.1.RELEASE)

2019-11-12 22:14:43.819  INFO 1389 --- [           main] o.g.samples.SpringBootDemoApplication    : Starting SpringBootDemoApplication on localhost with PID 1389 (/home/user/build/classes/java/main started by user in /home/user)
2019-11-12 22:14:43.820  INFO 1389 --- [           main] o.g.samples.SpringBootDemoApplication    : No active profile set, falling back to default profiles: default
2019-11-12 22:14:44.108  INFO 1389 --- [           main] o.g.samples.SpringBootDemoApplication    : Started SpringBootDemoApplication in 5.537 seconds (JVM running for 5.8)

BUILD SUCCESSFUL
3 actionable tasks: 3 executed
```

For more information, we suggest reading link:[Getting_started](https://docs.gradle.org/current/userguide/getting_started.html).
You can also find [Spring Boot related information inside the guides provided by the Spring team](https://spring.io/guides).
