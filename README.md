# Dependency Project

    $ ./gradlew clean cTG

    FAILURE: Build failed with an exception.

    * What went wrong:
    A problem occurred configuring root project 'hibernatedependencyissue'.
    > Could not resolve all dependencies for configuration ':runtime'.
       > Could not find org.grails:grails-datastore-simple:6.1.10.RELEASE.
         Searched in the following locations:
             file:/Users/jeffbrown/.m2/repository/org/grails/grails-datastore-simple/6.1.10.RELEASE/grails-datastore-simple-6.1.10.RELEASE.pom
             file:/Users/jeffbrown/.m2/repository/org/grails/grails-datastore-simple/6.1.10.RELEASE/grails-datastore-simple-6.1.10.RELEASE.jar
             https://repo.grails.org/grails/core/org/grails/grails-datastore-simple/6.1.10.RELEASE/grails-datastore-simple-6.1.10.RELEASE.pom
             https://repo.grails.org/grails/core/org/grails/grails-datastore-simple/6.1.10.RELEASE/grails-datastore-simple-6.1.10.RELEASE.jar
         Required by:
             project : > org.grails.plugins:hibernate4:5.0.4

    * Try:
    Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output.

    BUILD FAILED

    Total time: 1.855 secs
