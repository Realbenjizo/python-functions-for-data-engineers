Python Functions for Data Engineers

Supporting code examples, Jupyter notebooks, and datasets for the book Python Functions for Data Engineers: Write Cleaner, Faster, Safer Pipelines by Benjamin Bennett Alexander.

This repository accompanies the book and provides practical examples of how to apply software engineering principles when building Python data pipelines.

The goal is not simply to write Python code that works. It is to write code that is readable, reusable, testable, maintainable, and reliable.

What You'll Find Here

The repository contains the supporting materials used throughout the book:

Jupyter notebooks: Practical code examples that demonstrate the concepts covered in each chapter.

Datasets: Sample CSV files and other data used in the exercises.

Code examples: Python implementations of the techniques discussed in the book.

Exercises: Opportunities to experiment with the concepts and adapt the examples.

The materials are organized by chapter so you can follow along as you read.

Getting Started

You can work with the examples using Google Colab, Jupyter Notebook, Visual Studio Code, or another Python development environment.

You do not need to use a particular IDE or development platform. Choose the environment you are most comfortable with.

1. Get the Repository

Clone the repository:

git clone https://github.com/Realbenjizo/python-functions-for-data-engineers.git

Alternatively, select Code → Download ZIP on GitHub and extract the files to your computer.


2. Set Up Python

Make sure you have Python installed. Python 3.10 or later is recommended, unless a particular example specifies a different requirement.

You can create a virtual environment to keep the book's dependencies separate from other Python projects:

python -m venv .venv

Activate it:

Windows:

.venv\Scripts\activate

macOS and Linux:

source .venv/bin/activate

Install the required packages:

pip install -r requirements.txt

If you are using Google Colab, you can install the required packages directly in a notebook using:

%pip install pandas requests pandera

Some chapters may require additional libraries. Follow the installation instructions provided in the relevant notebook.

3. Open the Notebooks

Navigate to the notebooks directory and open the notebook for the chapter you are studying.

For Jupyter Notebook, you can start the environment with:

jupyter notebook

You can also upload the notebooks to Google Colab or open them directly in Visual Studio Code.

4. Access the Datasets

The datasets used in the examples are provided in the data directory.

Make sure the datasets are accessible from your notebook or Python script. Some examples use relative file paths, so you may need to adjust the path depending on where you store the files.

For example:

# Update this path if your dataset is stored elsewhere
transactions = "data/transactions_2.csv"

Repository Structure

The repository is organized as follows:

python-functions-for-data-engineers/
│
├── README.md
├── requirements.txt
│
├── notebooks/
│   ├── chapter_01.ipynb
│   ├── chapter_02.ipynb
│   ├── chapter_03.ipynb
│   └── ...
│
├── data/
│   ├── transactions_2.csv
│   ├── customers.csv
│   └── ...
│
└── LICENSE

The exact contents may change as examples and supporting materials are updated.

How to Use This Repository

I recommend following the chapters in the order presented in the book. Each notebook is intended to reinforce the concepts introduced in its corresponding chapter.

Don't just run the code and move on. Experiment with it.

Change function arguments and observe the results.

Introduce errors and see how the exception-handling mechanisms respond.

Modify functions and test whether their behaviour changes.

Try applying the patterns to your own datasets and projects.

The objective is to understand the reasoning behind the code, not simply reproduce it.

Requirements

The examples use Python and commonly used data engineering and data processing libraries, including:

pandas

requests

Pandera

SQLite

Python standard library modules

Not every chapter requires every library. The relevant notebooks contain additional instructions where necessary.

Updates and Corrections

Programming libraries and tools evolve. If an example needs correcting or updating, the repository may be updated independently of the printed or electronic edition of the book.

If you find an error, have a suggestion, or encounter an issue running an example, please open a GitHub issue with:

The chapter and notebook involved.

The error message or unexpected behaviour.

Your Python version and relevant package versions.

This will make it easier to investigate and address the problem.

About the Author

Benjamin Bennett Alexander is a Python enthusiast and author of books on Python programming, data analysis, and practical programming challenges.

He enjoys breaking down technical concepts, solving problems, and helping people develop the programming skills needed to build useful software.

Related Book

Python Functions for Data Engineers: Write Cleaner, Faster, Safer Pipelines

This repository is a companion to the book. The book provides the explanations and learning path; these notebooks and datasets give you the opportunity to work through the examples yourself.

If you find the materials useful, consider sharing the repository with other Python developers and aspiring data engineers.
