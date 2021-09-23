# ai-safety-tutorial

![ai-and-safety](./source/doe/AI_background_v4_4_960px.jpg)

[AI + Safety - DNV](https://ai-and-safety.dnvgl.com/)

This repo is a small tutorial based on the Design-of-Experiments section from the 
[AI + Safety](https://ai-and-safety.dnvgl.com/#sec-doe) position paper published by [DNV](https://www.dnv.com). 

## Stand-alone exploring

It can be explored as a stand-alone jupyter notebook by downloading the file
[doe-tutorial-1.ipynb](https://github.com/RaPiD-models/ai-safety-tutorial/blob/master/source/doe/doe-tutorial-1.ipynb) from ./source/doe/

## Student assignment

It can also be used as a student assignment by cloning the repo [https://github.com/RaPiD-models/ai-safety-tutorial.git](https://github.com/RaPiD-models/ai-safety-tutorial.git)
and creating a student version using [nbgrader](http://nbgrader.readthedocs.io/) to hide part of the code for the student to implement.

### Decide which code blocks the students should implement

  This is done by wrapping the relevant code in `### BEGIN SOLUTION` `### END SOLUTION` blocks like
```python
  def foo(bar):
    """Prints `bar`."""
    ### BEGIN SOLUTION
    print(bar)
    ### END SOLUTION
```

See [https://nbgrader.readthedocs.io/en/stable/configuration/student_version.html](https://nbgrader.readthedocs.io/en/stable/configuration/student_version.html) for more details on how to customize the student version.

### Generate student version (with possible autograding)

Please refer to [nbgrader](http://nbgrader.readthedocs.io/) documentaition for how to [Create and grade assignments](https://nbgrader.readthedocs.io/en/stable/user_guide/creating_and_grading_assignments.html)
