# dataframes-scala-tutorial

## Task: 

Open the `TwitterFeed.js`. The `Tweet` component is the only one you'll need to work on.

You'll need these various parts of code to get it working:

```scala
// comment
import spark.implicits._
df.printSchema()
```


df.select("name").show()

```scala
dbutils.fs.put("/tmp/people.json", """
{"name":"Michael"}
{"name":"Andy", "age":30}
{"name":"Justin", "age":19}
""", true)
```

Create a dataframe based on json file

```scala
val df = spark.read.json("/tmp/people.json")
```

to stdout
```scala
df.show()
```

```scala
  import spark.implicits._
  df.printSchema()

  df.select("name").show()
```
<code></code>
<code></code>
<code></code>
<code></code>
<code></code>
<code></code>
<code></code>
