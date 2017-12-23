# Color coded timestamped logger for Scala

A basic Scala logger with color coding and timestamping. 
Under the [MIT License](https://raw.githubusercontent.com/nsjames/EOS-Scala-RPC-API/master/license)

--

##Install
In your `build.sbt` file
```
libraryDependencies ++= Seq(
    "org.nsjames" %% "scala-logger" % "1.0-SNAPSHOT"
)
```

##Usage

```
Logger.line()
Logger.debug("debug")
Logger.info("info")
Logger.warn("warn")
Logger.print("print")
Logger.info(s"Uncolored | ${Logger.colorText("Colored", Logger.Colors.YELLOW)}")
Logger.info(s"Uncolored | ${Logger.colorText("Colored", Logger.Colors.RED)}")
Logger.info(s"Uncolored | ${Logger.colorText("Colored", Logger.Colors.GREEN)}")
Logger.block(List("block", "text"))
```

![](https://raw.githubusercontent.com/nsjames/scala-logger/master/example.jpg)
