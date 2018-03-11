# COMP 692 - Independent Study - Academic Writing Tools
Jamie Czerwinski [\<jamie.czerwinski@gmail.com\>](jamie.czerwinski@gmail.com)  
Athabasca University

As per the [Independent Study syllabus](http://www.athabascau.ca/syllabi/comp/comp692_3.php).

# Assignment 2 -- Implementation

Assignment 2 will comprise an implementation of prototype academic writing system. It should implement the design set out in [Assignment 1](assignment-1.md).

## Grading

Assignment 2 will be graded out of a total of 100 marks.

| Element                          | Marks |
|----------------------------------|------:|
| Completeness                     |    40 |
| Test Coverage                    |	30 |
| Maintainability                  |    30 |
| TOTAL                            |   100 |

### Completeness

Fourty (40) marks are to be given for the completeness of the implementation relative to the design. Completeness is to be calculated as follows:

1. Let the number of features in the [Documentation](assignment-1.md#documentation) = NumFeatures. Recursively include sub-features.
2. Let the number of passing tests in the test suite = PassingTests.
3. Let Completeness = 40 * PassingTests / NumFeatures

That is, the available marks are uniformly distributed over the designed features.

### Test Coverage

Thirty (30) marks are to be given for test coverage over the implementation's code base as measured by [Code Climate](https://codeclimate.com/). Marks are to be awarded as 30 * Coverage Ratio.

### Maintainability

Thirty (30) marks are to be given for code maintenability as measured by [Code Climate](https://codeclimate.com/).

Code Climate returns a Maintenability Rating from A to F. Marks are to be awarded as follows:

| Letter Grade | Marks |
|--------------|------:|
| A            |    30 |
| B            |    23 |
| C            |    16 |
| D            |     9 |
| F            |     0 |