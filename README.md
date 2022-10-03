
# HW2 EE538
## University of Southern California
## Instructor: Arash Saifhashemi

Please clone this repository, edit README.md to answer the questions, and fill up functions to finish the homework.

- Please find each question in a separate folder under [files](/files).
- For non-coding questions, fill out the answers in the README file.
- For coding questions, edit the files and check them in.
- For coding questions unless specified, you should add unit tests to the student_test.cc. We will clone and test your repo using your tests and some other tests (that are not provided). Your code should pass all of them.
- For submission, please push your answers to Github before the deadline.
- Deadline: Monday Oct 3rd by 12:00 pm (noon)
- Rubrics:
  
| Question | Points |
| -- | -- |
| 1  | 10 |
| 2  | 25 |
| 3  | 20 |
| 4  | 10 |
| 5  | 20 |
| 6  | 25 |
| 7  | 10 |
| 8  | 15 |

- Total: 135 points. 100 points is considered full credit.


See [cpp-template](https://github.com/ourarash/cpp-template) for help on installing bazel and debugging.


Question 1: Why did we have to provide size_1, size_2 as an input?
Array_1 and array_2 are dynamic arrays. If we do not provide size_1 and size_2, we cannot know the size of array_1 and array_2 and cannot concatenate them together.

Question 2: How can we know the size of the output?
The size of the output equals to size_1 + size_2. Or we can change the type of function to int and add the array pointer of the output concatenated array to the function input value, so that the return value can be set as size of concatenated array.

Question 1: Why didn't we provide the sizes?
We can get the size of vectors.

Question 2: We have two functions with the name of Concatenate. Is this ok?
Yes, it is ok. Function overloading is available in C++. If functions is differ by the arity or types of their parameters, it is ok.# EE538-HW2-1
