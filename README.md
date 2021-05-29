# jdbc-tester

A simple command line application to test JDBC connection to a Database.

## How to run

Clone this repository and then run:

```
mvn clean package
```

Add database JDBC jar files to lib folder.

Execute the JAR file:

```sh
java -cp target/jdbc-tester-1.1-jar-with-dependencies.jar:lib/* App
```

## How it works

The application connects to the database using JDBC and executes the provided query and prints the output. 

If it cannot connect for whatever reason, it will fail by logging an error message.

## JDBC Jars

* BigQuery: https://cloud.google.com/bigquery/docs/reference/odbc-jdbc-drivers
    * com.simba.googlebigquery.jdbc.Driver
* Others: https://mvnrepository.com/search?q=jdbc

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

Original source: https://github.com/aimtiaz11/jdbc-tester

## License

(The MIT License)

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
