# *README BELEN V N: evaluation of module three*
## Exercise on a customer data set within an airline loyalty program. ##

<h1 align="center" id="title">Exploratory Data Analysis (EDA)</h1>

<p align="center"><img src="https://png.pngtree.com/png-clipart/20220823/original/pngtree-thinking-hard-about-all-the-data-kawaii-illustration-png-image_8451303.png" alt="project-image"></p>

<p id="description">To complete the evaluation of module three of the Data Analyst Bootcamp I am doing at Adalab, I must perform an Exploratory Data Analysis (EDA) putting into practice the knowledge acquired.</p>

## INDEX

- [Introduction](#Introduction)
- [Files](#Files)
- [Requirements](#Requirements)
- [The process](#the-process)
  - [Built with](#built-with)
  - [Structure](#quiz-structure)
- [Useful resources](#useful-resources)
- [License](#license)
- [Author](#author)

## Introduction

This project focuses on exploratory data analysis (EDA) of flight activity and customer loyalty history. The objective is to explore and understand patterns in flight data and how they relate to different customer variables.
  
## Files

Files required for project review:

*    Customer Flight Activity.csv: Contains data on customer flight activity.
*    Customer Loyalty History.csv: provides a detailed profile of customers as well as includes data on the customer loyalty program.
*    airline_data.ipynb: Jupyter notebook including exploratory data analysis (EDA).



## Requirements

Make sure you have the following libraries installed in your Python environment:

1. pandas
2. numpy
3. matplotlib
4. seaborn
5. scikit-learn

If you do not have these libraries, you can install them using *pip install* 

## The process 
### Built with

Technologies used in the project:

*   Operating system: Windows 10 Home
*   Development Environment: Jupyter Notebook, Visual Studio Code
*   Programming Language: Python
*   Libraries specified above
*   Version Control: Git, GitHub
*   Dependency Management: Pip

### Quiz structure

``` Swift
// Question struct
struct Question {
  let question: String
  let answers: Array<String>
  let correctAnswer: String
  
  init(q: String, a: Array<String>, b: String){
      question = q
      answers = a
      correctAnswer = b
  }
}
```

``` Swift
// Question collection
let quiz = [
  Question(
      q: "¿Quién pintó Las meninas?",
      a: ["Francisco de Goya", "Diego Velázquez", "Salvador Dalí"],
      b: "Diego Velázquez"),
  Question(
      q: "¿Cuál es la capital de Hungría?",
      a: ["Viena", "Praga", "Budapest"],
      b: "Budapest")
]
```

## Useful resources

* [Canva](https://www.canva.com) - Used to create graphics.
* [Classes and Structures](https://docs.swift.org/swift-book/LanguageGuide/ClassesAndStructures.html) - A guide to Structures and Classes.

## License:

> This project is licensed under the MIT License

## Author

Made with 💜 by [alexcamachogz](https://twitter.com/alexcamachogz)
 
