# kotlin tutorials

https://kotlinlang.org/docs/tutorials/command-line.html

# Install kotlin compiler
```
$ sudo snap install --classic kotlin
```

# Run
```
$ vim hello.kt

fun main(args: Array<String>) {
        println("Hello, World!")
}

$ kotlinc hello.kt -include-runtime -d hello.jar 
$ java -jar hello.jar
Hello, World!
```