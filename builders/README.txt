MAVEN building process:

Execute following command in the root directory:
- mvn package

----

GRADLE building process:

Execute following commands inside modules subfolders in the same order as provided below:
./utils - gradle build
./services - gradle build
./admin - gradle build
./web - gradle build