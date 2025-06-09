# Getting Started

This repo will hold a set of jupyter notebooks to explore the capabilities of the pandas python library.

### Required Technologies
- Python version >=3.9
- Jupyter CLI OR 
- IDE with Jupyter Notebook server extension (VS Code, PyCharm, etc)


# Sources and Acknowledgements

## Fundamentals

The pandas notebook follows along with the tutorials by 
[justmarkham](https://github.com/justmarkham/pandas-videos) and is supplemented
with notes from the pandas documentation.

## Copy On Write

Memory allocation and optimization is an important part of any engineering practice and none more than Data Engineering. This tutorial is utilizing a version of pandas before 3.0. This means `Copy on Write` is not the default functionality for pandas which can lead to unintended [chained assignments](https://pandas.pydata.org/docs/dev/user_guide/copy_on_write.html#copy-on-write-chained-assignment).

More on [Copy on Write by Patrick Hoefler](https://towardsdatascience.com/a-solution-for-inconsistencies-in-indexing-operations-in-pandas-b76e10719744/), a pandas contributor.