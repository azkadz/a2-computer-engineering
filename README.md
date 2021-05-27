# Introduction to computing with Python for Engineering Science

These Jupyter notebooks provide a self-study introduction to engineering computation with Python. They are intended to be used as preparation for the A2 subpaper Introduction to Computer Engineering as part of the MEng in Engineering Science. 

## Jupyter Notebooks

The content in this repository is provided in the form of [Jupyter notebooks](https://jupyter.org). There are many good online tutorials for using such notebooks (e.g. [1](https://www.dataquest.io/blog/jupyter-notebook-tutorial/), [2](https://www.codecademy.com/articles/how-to-use-jupyter-notebooks)). In general you can work with these notebooks by installing Python and the notebook software locally, i.e. on your own computer, or you can use a cloud compute provider to work on a notebook using a service hosted in the cloud (i.e. someone else's computer).

### Local: Anaconda

If you want to use notebooks, and Python more generally, on your own machine, then I highly recommend installing everything using [Anaconda](https://www.anaconda.com/products/individual), which is an application for installing and managing Python environments. The instructions for how to use Anaconda to install Jupyter [are linked here](https://docs.anaconda.com/anaconda/user-guide/getting-started/).

A video on using Anaconda to run a Jupyter Notebook is here: https://youtu.be/x0MEaTorbtc

### Cloud: AWS SageMaker 

If you don't want to install anything on your local machine, or don't have a device capable of running Jupyter notebooks, then you can run your notebooks on a cloud server (i.e. a remote machine). I recommend using AWS SageMaker. To get free access to this tool, do the following:

1. Sign up for an AWS Educate account: https://www.awseducate.com/registration. You can sign up as a student (with a *.ox.ac.uk email) and get a student account that provides you with free access to a range of AWS services, including AWS SageMaker Studio, which is the name for the AWS version of Jupyter Lab.
2. Once you have your account activated, sign in to your AWS Educate account: https://www.awseducate.com/signin/SiteLogin
3. Once you're signed in you can access the AWS console and create a SageMaker Studio instance. This involves a fairly non-trivial sequence of steps. I will make a video to illustrate them. You should also be able to follow the instructions from here: https://docs.aws.amazon.com/sagemaker/latest/dg/onboard-quick-start.html
4. Once you have SageMaker Studio up and running you can add the tutorial sheet and lecture notes using the upload file option in the file browser. You can add the files for the self-study activities by using the git menu option and selecting git clone for https://github.com/hawesie/a2-computer-engineering.git

These steps are quite a pain the first time, but afterwards you can use SageMaker Studio as easily as you could use Jupyter Lab locally. You can also use your AWS Educate account to try other AWS products. Also note that your AWS Educate account is different to an AWS account. You access AWS via the AWS Educate organisation, who provide you with a hosted AWS account. 

A video on using AWS SageMaker Studio to run a Jupyter Notebook is here: https://youtu.be/6Jvsh85Q6AI


## Getting started


Once you have set up the infrastructure described above for working with Python you should make a start with the provided notebooks. Each notebook covers a topic, with a number of exercises for completion at the end of each notebook. Download a zip of this repository with the following link: https://github.com/hawesie/a2-computer-engineering/archive/refs/heads/master.zip

Unpack the zip file then start with the notebook [A2 Introduction to Computer Engineering](00%20A2%20Introduction%20to%20Computer%20Engineering.ipynb). 

## Accompanying exercises

For each notebook there are a set of exercises in the directory
[Exercises](./Exercises/) for completion at end the of each Activity
notebook.

## More Python 

For learning more Python than is covered by the activites linked above, I recommend the following books. The "view online" links require institutional access via your SSO.

 * *Python Crash Course: A hands-on, project-based introduction to programming* by Eric Matthes [[view online](https://www.oreilly.com/library/view/python-crash-course/9781457197185/?ar)]
 * *Think Python*  by Allen Downey [[view online](https://www.oreilly.com/library/view/think-python-2nd/9781491939406/?ar)]
 * *How to Think Like a Computer Scientist* [[view online](http://openbookproject.net/thinkcs/python/english3e/)]

# Credits

This repository was developed for the computing course in Part IA (Michaelmas Term) of the Engineering Tripos at University of Cambridge. The notebooks can be freely used, shared and modified. See the copyright
and license notice below. The original material can be found at https://github.com/CambridgeEngineering/PartIA-Computing-Michaelmas


## Feedback and corrections

These notebooks are maintained at: https://github.com/hawesie/a2-computer-engineering.

Please report suggestions or errors at: https://github.com/hawesie/a2-computer-engineering/issues


## Author

These notebooks were originally developed by Garth N. Wells (@garth-wells,
<gnw20@cam.ac.uk>). They were adapted for use at the University of Oxford by Nick Hawes (<nickh@robots.ox.ac.uk>).


## Acknowledgements

Valuable feedback during the development of the notebooks was provided
by Quang T. Ha, Hugo Hadfield, Tim Love, Chris Richardson and Joanna
Stadnik.


## License and copyright

All material is copyright of Garth N. Wells (<gnw20@cam.ac.uk>).

All text is made available under the Creative Commons
Attribution-ShareAlike 4.0 International Public License
(https://creativecommons.org/licenses/by-sa/4.0/legalcode).

All computer code is released under the MIT license.

The MIT License (MIT)
Copyright (c) 2016-2019 Garth N. Wells

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
