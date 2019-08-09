# java-console-app
A repository template for Java console application.

It includes picocli and slf4j with simple configuration setup.

# Using the template
- [ ] On the repo page, click "Use the template" and generate a new repository.
- [ ] In the new repository, replace the `TEMPLATE` placeholder in the files.
- [ ] Rename the project source package and the entry point.
- [ ] Update the `mainClassName` in `build.gradle`.
- [ ] Remove these usage instructions :)

```
git ls-files | grep template
git grep TEMPLATE
```

# Building console application
1. Run Gradle: `./gradlew distTar`.
2. Pick up the TAR file from `build/distributions/TEMPLATE.tar`.

## Usage

```bash
Usage: TEMPLATE
```

### Development notes

* Run the application in development: `./gradlew run --args="-i input -o output"`
* Gradle application plugin docs - https://docs.gradle.org/current/userguide/application_plugin.html 
