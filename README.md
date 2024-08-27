To manually create a new release using the [gitflow-maven-plugin](https://github.com/aleksandr-m/gitflow-maven-plugin):

1. If a `release` branch does not exist yet, create it based on the current `main` branch.
2. Run `./mvnw -B gitflow:release`.