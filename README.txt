[INFO] Error stacktraces are turned on.
[INFO] Scanning for projects...
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Build Order:
[INFO] 
[INFO] com.io7m.jacoco.20171030
[INFO] com.io7m.jacoco.20171030.core
[INFO] com.io7m.jacoco.20171030.tests
[INFO] 
[INFO] ------------------------------------------------------------------------
[INFO] Building com.io7m.jacoco.20171030 0.0.1
[INFO] ------------------------------------------------------------------------
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ com.io7m.jacoco.20171030 ---
[INFO] 
[INFO] ------------------------------------------------------------------------
[INFO] Building com.io7m.jacoco.20171030.core 0.0.1
[INFO] ------------------------------------------------------------------------
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ com.io7m.jacoco.20171030.core ---
[INFO] Deleting /home/someone/git/com.github/io7m/jacoco-20171030/core/target
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ com.io7m.jacoco.20171030.core ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/someone/git/com.github/io7m/jacoco-20171030/core/src/main/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:compile (default-compile) @ com.io7m.jacoco.20171030.core ---
[INFO] Changes detected - recompiling the module!
[WARNING] File encoding has not been set, using platform encoding UTF-8, i.e. build is platform dependent!
[INFO] Compiling 1 source file to /home/someone/git/com.github/io7m/jacoco-20171030/core/target/classes
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ com.io7m.jacoco.20171030.core ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/someone/git/com.github/io7m/jacoco-20171030/core/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:testCompile (default-testCompile) @ com.io7m.jacoco.20171030.core ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ com.io7m.jacoco.20171030.core ---
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-jar-plugin:2.4:jar (default-jar) @ com.io7m.jacoco.20171030.core ---
[INFO] Building jar: /home/someone/git/com.github/io7m/jacoco-20171030/core/target/com.io7m.jacoco.20171030.core-0.0.1.jar
[INFO] 
[INFO] ------------------------------------------------------------------------
[INFO] Building com.io7m.jacoco.20171030.tests 0.0.1
[INFO] ------------------------------------------------------------------------
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ com.io7m.jacoco.20171030.tests ---
[INFO] Deleting /home/someone/git/com.github/io7m/jacoco-20171030/tests/target
[INFO] 
[INFO] --- jacoco-maven-plugin:0.7.9:prepare-agent (jacoco-agent) @ com.io7m.jacoco.20171030.tests ---
[INFO] argLine set to -javaagent:/home/someone/.m2/repository/org/jacoco/org.jacoco.agent/0.7.9/org.jacoco.agent-0.7.9-runtime.jar=destfile=/home/someone/git/com.github/io7m/jacoco-20171030/tests/target/jacoco.exec
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ com.io7m.jacoco.20171030.tests ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/someone/git/com.github/io7m/jacoco-20171030/tests/src/main/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:compile (default-compile) @ com.io7m.jacoco.20171030.tests ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ com.io7m.jacoco.20171030.tests ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/someone/git/com.github/io7m/jacoco-20171030/tests/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:testCompile (default-testCompile) @ com.io7m.jacoco.20171030.tests ---
[INFO] Changes detected - recompiling the module!
[WARNING] File encoding has not been set, using platform encoding UTF-8, i.e. build is platform dependent!
[INFO] Compiling 1 source file to /home/someone/git/com.github/io7m/jacoco-20171030/tests/target/test-classes
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ com.io7m.jacoco.20171030.tests ---
[INFO] Surefire report directory: /home/someone/git/com.github/io7m/jacoco-20171030/tests/target/surefire-reports

-------------------------------------------------------
 T E S T S
-------------------------------------------------------
Running com.io7m.example.tests.CoreTest
Hello
Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.019 sec

Results :

Tests run: 1, Failures: 0, Errors: 0, Skipped: 0

[INFO] 
[INFO] --- jacoco-maven-plugin:0.7.9:report (jacoco-report) @ com.io7m.jacoco.20171030.tests ---
[INFO] Skipping JaCoCo execution due to missing classes directory.
[INFO] 
[INFO] --- maven-jar-plugin:2.4:jar (default-jar) @ com.io7m.jacoco.20171030.tests ---
[WARNING] JAR will be empty - no content was marked for inclusion!
[INFO] Building jar: /home/someone/git/com.github/io7m/jacoco-20171030/tests/target/com.io7m.jacoco.20171030.tests-0.0.1.jar
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Summary:
[INFO] 
[INFO] com.io7m.jacoco.20171030 ........................... SUCCESS [  0.231 s]
[INFO] com.io7m.jacoco.20171030.core ...................... SUCCESS [  2.184 s]
[INFO] com.io7m.jacoco.20171030.tests ..................... SUCCESS [  1.660 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 4.245 s
[INFO] Finished at: 2017-10-30T17:19:40Z
[INFO] Final Memory: 20M/66M
[INFO] ------------------------------------------------------------------------
