# Ten Thousand Game 1

## Random Module

* How can the random module be utilized in Python to generate random numbers or make selections from a list, and what are some common functions available within the module?
  * randInt(a, b) - returns an int value \(a, b\]
  * random() - returns a value \[0,1\)
  * choice([array]) - picks a random index and returns the value
  * shuffle([array]) - shuffles the list

## Risk Analysis

* In the context of software development, what is risk analysis, and what are the key steps involved in conducting a risk analysis for a software project?
  * Risk analysis is the process of identifying the risks in applications and writing tests which focus on said risks
  * Risk identification
    * Buisness Risks
    * Testing Risks
    * Premature Release Risks
    * Software Risks
  * Risk assessment
    * Likelihood it'll happen
    * What type of impact it'll have (effect)
    * Determining the cause and the costs of doing so

## Test Coverage

* What is test coverage and why is it an important (or potentially misleading) metric in software testing?
  * Just because there are a number of tests written doesn't mean that the overall quality of the tests are sufficient

## Big O

* What is Big O notation, and how is it used to describe the performance of an algorithm? Give and example of an everyday task (not software related) that demonstrates O(n) time complexity.
  * Big O notation gives a rough estimate of how many cycles a computer will be using (basically order of magnitude) in relation to the growth of an input. It only gives relational information and does not reflect how long a piece of code will actually take
  * An example of O(n) would be how many miles a person is driving compared to how long it'll take to get there (assuming no traffic)

## Reading and Media

* [How to use Random Module](https://www.pythonforbeginners.com/random/how-to-use-the-random-module-in-python)
* [What is Risk Analysis](https://www.edureka.co/blog/risk-analysis-in-software-testing/)
* [Test Coverage](https://martinfowler.com/bliki/TestCoverage.html)
* [Big O Notation](https://www.youtube.com/watch?v=v4cd1O4zkGw)
* [Python Random](https://docs.python.org/3/library/random.html)
* [What is Dependency Injection](https://www.freecodecamp.org/news/a-quick-intro-to-dependency-injection-what-it-is-and-when-to-use-it-7578c84fa88f/)