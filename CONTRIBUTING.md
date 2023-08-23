# Contributing
Guidelines for contributing to the Initium project

## Submitting Code
There are two ways to submit your contribution:

* A normal pull request
* Sending your contribution to Reperak#4918 in the form of a patch generated by `git format-patch` including your GitHub noreply email so that I can mark you as the author

## Code Conventions
Code should follow the style demonstrated in the original Java documentation (e.g. modified K&R style, proper spacing), with the following exceptions:

* No lines after a class starts

```java
public class Foo extends Bar {
    public void fooBar() {
        // Do stuff
    }
}
```

* Inline comments should have two spaces after code

```java
int number = 5;  // This is a very awesome integer
```