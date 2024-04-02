## Gradle symlink classpath location issue

When executed using `./gradlew build` this will succeed the basic compileGroovy task.

When executed using `./gradlew build -PuseSymlinks=true` it will fail with the unexpected error.

The build should generate two locations locally using actual Groovy 4.x distribution files as
`groovy-jars` and a `groovy-symlinks` where the behavior of our system is simulated.

The failed execution will demonstrate the problem.
