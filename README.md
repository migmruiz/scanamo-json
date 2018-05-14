# Scanamo Json
Scanamo Json provides `DynamoFormat`s for popular Scala Json libraries. The format will serialize directly to DynamoDB `AttributeValue`s, allowing full use of DynamoDB while allowing arbitrary Json objects to be stored.

# Getting started

### Circe

First, add the dependency:

```scala
    libraryDependencies += "io.github.howardjohn" %% "scanamo-circe" % "0.1.0"
```

Finally, the format can be imported with:

```scala
    import io.github.howardjohn.scanamo.CirceDynamoFormat._
```

This provides a `DynamoFormat[Json]`