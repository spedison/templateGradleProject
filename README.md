# This Simple App have a details for create new project with Gradle

### Create a new Directory
`
$ mddir  simpleHelloWithGradle/
`

### And enter it
`
$ cd simpleHelloWithGradle/
`

### Execute Gradle init
`
 ~/git/simpleHelloWithGradle 
$ gradle init
`

### The initializer starts with any questions. In this point select the more simple type : basic
`
Select type of project to generate:
  1: basic
  2: application
  3: library
  4: Gradle plugin
Enter selection (default: basic) [1..4] 1
`

### DSA is a language then you work with gradle. We user Groovy Language.
### Do don't worry, this language is more simple then Java ;-)
`
   Select build script DSL:
     1: Kotlin
     2: Groovy
   Enter selection (default: Kotlin) [1..2] 2
`

### This is a project name. The default is a name of directory and
`
Project name (default: simpleHelloWithGradle): 
`

### Do not compile with APIs
`
Generate build using new APIs and behavior (some features may change in the next minor release)? (default: no) [yes, no] 
`

### The gradle will make a new project
`
   > Task :init
   To learn more about Gradle by exploring our Samples at https://docs.gradle.org/8.6/samples

   BUILD SUCCESSFUL in 21s
   1 actionable task: 1 executed
`

### Ok, in this point we have a empy project with Gradle.


## Creade Directory to put your source code.

### In linux or unix like with bash shell.
`
   mkdir -p  ./src/{main,test}/{java,resources}/<your package base>

`
For example: 
 * My Package is br.com.spedison. (My Domain in reverse order : spedison.com.br) 
 * My command is:
`
   mkdir -p  ./src/{main,test}/java/br/com/spedison/
   mkdir -p  ./src/{main,test}/resources
`

### in windows

Using the same package br.com.spedison :

`
  mkdir ./src
  mkdir ./src/main
  mkdir ./src/main/java
  mkdir ./src/main/java/br
  mkdir ./src/main/java/br/com
  mkdir ./src/main/java/br/com/spedison
  mkdir ./src/main/resources
  mkdir ./src/test
  mkdir ./src/test/java
  mkdir ./src/test/java/br
  mkdir ./src/test/java/br/com
  mkdir ./src/test/java/br/com/spedison
  mkdir ./src/test/resources
`

## Read the build.gradle file, in this repository, because he have more examples and details in comments.


## Have Good Fun !
