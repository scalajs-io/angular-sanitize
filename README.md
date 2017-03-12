Angular Sanitize API for Scala.js
================================
[angular-sanitize](https://www.npmjs.com/package/angular-sanitize) - angular-sanitize binding for Scala.js.

### Description

An `angular-sanitize` binding for Scala.js.

### Build Dependencies

* [SBT v0.13.13](http://www.scala-sbt.org/download.html)

### Build/publish the SDK locally

```bash
 $ sbt clean publish-local
```

### Running the tests

Before running the tests the first time, you must ensure the npm packages are installed:

```bash
$ npm install
```

Then you can run the tests:

```bash
$ sbt test
```

### Artifacts and Resolvers

To add the `angular-sanitize` binding to your project, add the following to your build.sbt:  

```sbt
libraryDependencies += "io.scalajs.npm" %%% "angular-sanitize" % "1.6.3"
```

Optionally, you may add the Sonatype Repository resolver:

```sbt   
resolvers += Resolver.sonatypeRepo("releases") 
```