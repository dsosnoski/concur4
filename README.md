concur4
============

This gives sample Scala code for the
[fourth article in my JVM Concurrency series](http://www.ibm.com/developerworks/library/j-jvmc4/index.html) on IBM
developerWorks. The project uses a Maven build, so just do the usual `mvn clean install` to get
everything to a working state. The code is all in the `com.sosnoski.concur.article4` package, within
the *main/scala* tree.

To run the demonstration code from the command line use
`mvn scala:run -Dlauncher={name}`, where {name} selects the test code:

1. `happypath` - Demonstrate code with only successful completions
2. `unhappypath` - Demonstrate code with exceptions thrown

You can import the project into ScalaIDE with the standard Maven project import handling.
