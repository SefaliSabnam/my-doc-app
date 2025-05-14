# my-doc-app

This project is a Maven-based Java application with a clear directory structure, including test cases and compiled binaries.

## Project Structure

* `src/main/java/com/sabnam/app` - Contains the main application source code (`App.java`).
* `src/test/java/com/sabnam/app` - Contains the test cases (`AppTest.java`).
* `target/` - Contains compiled classes, build reports, and the final JAR file.
* `pom.xml` - Project Object Model (POM) file that defines project dependencies, plugins, and build configurations.

## 1. Branch Explanation

* **master branch:**

  * Main development branch where active code changes occur.
  * Contains the complete source code and test cases.

* **main branch:**

  * Production-ready branch.
  * Code is merged here after successful testing and verification.

## 2. Project Setup

### Prerequisites

* Java Development Kit (JDK) installed (preferably OpenJDK 11 or above).
* Maven installed on the system.

### Installation Steps

1. **Clone the Repository:**

   ```bash
   git clone <your-repository-url>
   cd <your-repository-directory>
   ```

2. **Switch to Required Branch:**

   ```bash
   git checkout master
   # or
   git checkout main
   ```

3. **Build the Project:**

   ```bash
   mvn clean install
   ```

4. **Run Tests:**

   ```bash
   mvn test
   ```

5. **Run the Application:**

   ```bash
   java -jar target/my-doc-app-1.0-SNAPSHOT.jar
   ```

## 3. Usage

* Use the `master` branch for development and testing.
* Use the `main` branch for production deployment.
* The generated JAR file can be found in the `target/` directory.

## 4. Troubleshooting

* **Build Errors:** Verify all dependencies are defined in `pom.xml`.
* **Test Failures:** Review the test reports in `target/surefire-reports/`.
* **JAR Not Running:** Ensure you are running the correct JAR version from the `target/` directory.

## 5. Author

* Created by \[SefaliSabnam].
