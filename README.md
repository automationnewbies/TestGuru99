This is an automation test project TestGuru99. It includes 5 features:
Site test [HERE](http://demo.guru99.com)

1. Signup (by random email)
2. Login (by user created from the random email at suite 01)
3. Create a new Customer (by the user from suite 01)
4. Create a new bank Account (by the customer from suite 03)
5. Add new Deposit (to Bank account from suite 04)

# Getting started

* Clone this project
* Open terminal then run this command

```
$ cd TestGuru99/
$ mvn clean install
```

# Check the report result

* Goes to test-report/ folder in the current project.
* Check latest folder report time and open file ExtentReport.html
* The report will show all statuses passed or failed.

See the [Video Record Here](https://youtu.be/kF8e2zshU6c)
for how to run and check the extent report result.

## Requirements

* [Java 8 JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
* `java` and `jar` on the PATH (make sure you use `java` executable from JDK but not JRE)

## Environment

This code is tested with
* Jdk build 1.8
* chromedriver 2.40
* OS X (High Siera) 10.13.6

## References

* Java 
* Selenium
* Maven 
* TestNG
* Extent Report
