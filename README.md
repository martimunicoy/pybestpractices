# Best Practices for Python
A collection of best practices, tips and tools for any Python project

_Work in progress_

## Coding

### Docstrings
All Python objects rely on a special attribute called
`doc` which is used to describe them. To properly set this `doc` attribute,
we need to describe each object with the corresponding docstrings. Python
is able to automatically initialize the `doc` attribute with the
comments it finds in the first line of each object. So, this is the place
where we need to describe them with docstrings.

Docstrings are essential if we want our code to be inteligible and
self-explanatory. They will be helpful for both, developers that need to
go through the code and understand it, and users that need to use the API
of our package. They will be able to call the `help()` method in their
Python interpreter to display the docstrings of any object.
Besides, when correctly formatted, docstrings can be employed to
build the documentation of our API with
[Sphinx](https://www.sphinx-doc.org/en/master/), for instance.

There are different formats to follow when writing docstrings. It is
important to follow standard formats to ensure that our documentation will
be correctly interpreted by Python or any external tool that can be used
to display it. One format that offers both good human readability and
machine interpretation is
[Numpy docstring standard](https://numpydoc.readthedocs.io/en/latest/format.html#docstring-standard)


# Acknowledgements
Inspired by: https://github.com/choderalab/software-development
