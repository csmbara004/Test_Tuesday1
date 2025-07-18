# Ant Build Instructions

## Requirements
- Java JDK
- Apache Ant
- JUnit JAR (place in `lib/` directory)

## Usage

1. Place JUnit JAR (e.g., `junit-4.13.2.jar` and `hamcrest-core-1.3.jar`) in the `lib/` directory.
2. Run the following commands:

```
ant clean jar
```

- This will compile the code, run all unit tests (regardless of pass/fail), and package the main classes into `build/jar/semester-project.jar`.

## Notes
- Do **not** commit the contents of `build/`, `lib/`, or any generated JARs to version control.
- All source, configuration, and hand-edited data files should be committed.
- For future phases, see `build.xml` for how to add more libraries or custom build steps.
