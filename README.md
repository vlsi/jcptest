# jcptest
Test project for java preprocessor

As you execute `mvn clean package` you get pre-processed sources in the source jar.

Note:
1) `jar-no-fork` should be used for `maven-source-plugin` to avoid reexecution of `generate-sources` phase
2) Pre-processed sources are placed to custom `target/gen-src` folder, so IDEA does not warn you on "duplicate classes" 
