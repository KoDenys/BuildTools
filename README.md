To build the project, use command `gradle build` or `mvn package`
for Gradle and Maven respectively.

To run tests, use command: `gradle test` or `mvn test` 
for Gradle and Maven respectively.


1 Download archive with sources of multi module project with the following structure: jar <-- admin \ |----services --- utils war <-- web /

2 Create Maven and Gradle build scripts to build the project. Two artifacts – war (for web module) and jar (for admin module) should be generated as a result of script running. Also, you need to create README file with build instructions.

Task details:

2.1. Only one project should be in your repository. Build scripts for different build tools should be in the root directory of the project.

2.2. Repository MUST not contain result artifacts (jar, war).

2.3. README file should contain instructions to build project via Maven, Gradle tools. Instructions must contain command line to start build project.

2.4. Build script should allow test running. Details about how to run tests should be written in README.

2.5. Task will not be accepted if you generate scripts by any generation tools (for example, Gradle from Maven script).

