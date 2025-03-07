# Introduction to Machine Learning with Python

Welcome to my tutorial!

The goal is to provide you with an introduction to Machine Learning (ML) concepts through the Python programming language. This material is designed to be *interactive* and *supplementary*, preferably used alongside a rigorous course that covers the mathematical concepts referenced here in detail. As a **disclaimer**: This tutorial will not show you how to train a LLM, or a neural network for that matter. Instead, it will focus on some fundamentals of ML, or rather, pattern recognition. While we will cover several algorithms designed for classification, regression, as well as control, the examples provided will be on toy datasets and require relatively little computation power.   

## I. Setup Instructions

### Prerequisites
#### *Knowledge*: 
While there is no strict prerequisite for the content provided here, the mathematical concepts discussed will assume you are comfortable with **probability theory, linear algebra, and calculus**. As aforementioned, this tutorial should be *supplementary*, and your coverage may vary based on your prior knowledge. In regard to computer programming, I believe that if you made it this far, you will be fine, assuming **some prior experience with programming**. Python is a relatively intuitive language, and I provide a short overview for those unfamiliar with the syntax.  

#### *Hardware*:
There are no strict compute requirements, and this lab will not require the use of a GPU. A relatively modern laptop (2015+) should suffice, and students can feel free to use [Google Colab](https://colab.research.google.com/) for their resources. 

#### *Software*:
While I highly recommend using a UNIX-based OS (macOS or Linux) for your ML journey, a Windows computer will suffice. As all labs will run from a single interactive notebook file, the only requirements are: (1) have a virtual python environment which contains the packages used in this tutorial. (2) be able to execute *.ipynb* files which can read *.csv* files found in this *repository*. To accomplish this with the least resistance, I suggest using a popular IDE such as [vscode](https://code.visualstudio.com/). The [setup instructions](#setup-instructions) below will reference *Bash* commands, which should be straightforward for macOS or Linux users. For Windows users, I recommend using [Windows Subsystem for Linux](https://learn.microsoft.com/en-us/windows/wsl/about), where these [instructions](https://code.visualstudio.com/docs/remote/wsl-tutorial) will help you setup remote WSL through vscode for convenience.  

### Setup Instructions
#### For macOS/Linux users:
From your desired location, simply [clone this repository](https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories) to your local machine, and open it using vscode (optional):

```bash
git clone https://github.com/mbeliaev1/ml_tutorial.git # clone the repository to your current directory
code ml_tutorial # open the cloned directory with vscode
```

Now create the [virtual environment](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/) we will use for this lab. Note if using WSL, you will need to manually [install python](https://www.python.org/downloads/) (any version 3.3+) beforehand:

```bash
python3 -m venv .venv # python3.3+ needs to be installed
source .venv/bin/activate # activate your venv
which python # check that you are referencing to the binned version
python -m pip install --upgrade pip # make sure pip is up-to-date
python -m pip install -r requirements.txt # install the packages required for this tutorial!
```

**NOTE**: I do not list any versions in the *requirements.txt* file as this is simply a tutorial, and I do not want to require installing a matching version of Python through some package manager. As this was created with the intent of teaching undergraduates ML basics, this will help avoid confusion as anyone running python 3.3+ will be able to reproduce the contents here. 

## II. Overview
This tutorial will be broken into several self-contained *labs* found in the **/content** directory. Each lab will contain an interactive python notebook (*.ipynb* file), along with optional data that is necessary for completing the lab. While each lab will provide a general overview of the topic covered, your assignment is to *complete* the lab by providing (code) solutions in the designated cells, which will be highlighted at the start of the lab. In most cases, it should be clear if your solution is acceptable based on the content generated when running the interactive notebook. To encourage utilizing this content as an opportunity to test your understanding of the concepts covered, I chose to forego providing the solution set. However, the **SOLUTION SET** does exist and will be provided to you if you [contact me](#v-contact).
 
## III. Table of Contents
- **Lab 0**: *Introduction to Python and NumPy*
- **Lab 1**: *Introduction to Supervised Learning*
- **Lab 2**: *Introduction to Unsupervised Learning*
- **Lab 3**: *Introduction to Reinforcement Learning*

# IV. Resources
While the lab assignments will provide resources to code documentation, most of the prerequisite knowledge is your responsibility. Since the labs serve as introductory material meant to supplement a full course, we will not dive deep into any of the topics here. For those interested in learning further, I highly recommend the following *free* sources:

- [Deep Learning Book](https://www.deeplearningbook.org/) (Part I) by Ian Goodfellow and Yoshua Bengio and Aaron Courville.
- [Stanford CS229 - Machine Learning](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU) by Andrew Ng. 
- [Stanford CS234 - Reinforcement Learning](https://www.youtube.com/playlist?list=PLoROMvodv4rOSOPzutgyCTapiGlY2Nd8u) by Emma Brunskill.

## V. Contact

Mark Beliaev

email: concat first and last name at gmail dot com

webpage: [markbeliaev.com](https://markbeliaev.com/)