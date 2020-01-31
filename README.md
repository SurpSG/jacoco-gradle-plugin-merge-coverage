# jacoco-gradle-plugin-merge-coverage

A sample project that demonstrates how to use Jacoco Gradle plugin for a multimodule Gradle project. 

Also, there is a task `jacocoRootReport` that merges modules coverage data and generates a full-coverage report.

To generate full coverage report run:
```
./gradlew clean jacocoRootReport
```

Open HTML report to observe the results
```
build/reports/jacoco/jacocoRootReport/html/index.html
```

