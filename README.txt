Build (Java 21 required):
  gradle wrapper --gradle-version 8.12     (once, if you don't have ./gradlew)
  ./gradlew build        (Windows: gradlew.bat build)
Output: build/libs/elytra-upright-1.0.1.jar  (NOT the -sources jar)
Put it in .minecraft/mods with Fabric Loader 0.16+ for 1.21.4.

GitHub (no PC needed): upload ALL files incl. the hidden .github folder, open Actions > build > Run workflow, download "elytra-upright-jar".
