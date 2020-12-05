# Cineast Proto & gRPC API

[![Maven Central](https://img.shields.io/maven-central/v/org.vitrivr/cineast-proto.svg?label=Maven%20Central)](https://search.maven.org/search?q=g:%22org.vitrivr%22%20AND%20a:%22cineast-proto%22)

These are the [Protocol Buffer v3](https://developers.google.com/protocol-buffers/docs/proto3) and [gRPC](https://grpc.io/) definitions
of [Cineast](https://github.com/vitrivr/cineast) 's API.
These definitions can be used to use Cineast as a (remote) retrieval engine.


---
## ALPHA STAGE

**Important notice, this is in early alpha and currently not used anywhere, please use with caution.**

---

## Usage

Use your preferred build automation tool to include the dependency.

### Maven

```xml
<dependency>
  <groupId>org.vitrivr</groupId>
  <artifactId>cineast-proto</artifactId>
  <version>VERSION</version>
</dependency>
```

### Gradle

```groovy
compile 'org.vitrivr:cineast-proto:0.1.0'
```


## Contributors

Originally, this was developed by @lucaro under the umbrella of the vitrivr organisation.

## Versioning

We use [semver](https://semver.org) to label the versions of Cineast and Cineast Proto.
Please be aware that different versions of Cineast and Cineast Proto might not be compatible.