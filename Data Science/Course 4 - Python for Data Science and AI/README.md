## IBM- Data Science

### [Python for Data Science and AI](https://www.coursera.org/learn/python-for-applied-data-science-ai/home/info)  
Upon its completion, I'll be able to write Python scripts and perform basic hands-on data analysis using Jupyter-based lab environment. 

### [Week 1](https://github.com/kk289/IBM-Data-Science/tree/master/Course%204_Python%20for%20Data%20Science%20and%20AI/Week%201)        
#### Python Basics
In this module, I learned about Python Basics which are useful in data science field.   

- Types 
- Expressions and Variables 
- String Operations 

##### Key Concepts:   
- Demonstrate an understanding of types in python by converting/casting data types: strings, floats, integers.
- Interpret variables and solve expressions by applying mathematical operations.
- Describe how to manipulate strings by using a variety of methods and operations.

### [Week 2](./Week%202)    
#### Python Data Structures   
In this module, I learned about Python Data Structures. 

- Lists and Tuples
- Sets
- Dictionaries    

##### Key Concepts    
- Understand tuples and lists by describing and manipulating tuple combinations and list data structures.
- Demonstrate understanding of dictionaries by writing structures with correct keys and values.
- Understand the differences between sets, tuples, and lists by creating sets.

### [Week 3](./Week%203)   
#### Python Programming Fundamentals
In this module, I learned about the fundamentals of Python programming. 

- Conditions and Branching
- Loops
- Functions
- Objects and Classes   

##### Key Concepts    
- Classify conditions and branching by identifying structured scenarios with outputs.
- Understand loops by using visual examples and comparing them to tuples and lists.
- Understand functions by building a function using inputs and outputs.
- Explain objects and classes by identifying data types and creating a class.

### [Week 4](./Week%204)   
#### Working with Data in Python

- Reading files with open
- Writing files with open
- Loading data with Pandas
- Working with and Saving data with Pandas
- Numpy

##### Key Concepts
- Demonstrate an open function to create and identify a file object.
- Understand how to use pandas for library and data analysis by using commands.
- Demonstrate how to create a text file by using the open function.
- Demonstrate how to use NumPy to create multi-dimensional arrays.    

### [Week 5](./Week%205)   
#### Final Project

##### Key Concepts
- Create a dashboard that shows key economic indicators from a specific data set.

```
def make_dashboard(x, gdp_change, unemployment, title, file_name):
    output_file(file_name)
    p = figure(title=title, x_axis_label='year', y_axis_label='%')
    p.line(x.squeeze(), gdp_change.squeeze(), color="firebrick", line_width=4, legend="% GDP change")
    p.line(x.squeeze(), unemployment.squeeze(), line_width=4, legend="% unemployed")
    show(p)
    
make_dashboard(x = x, gdp_change = gdp_change, unemployment = unemployment, title = title, file_name = file_name)
```

![dashboard](https://github.com/kk289/IBM-Data-Science/blob/master/Course%204_Python%20for%20Data%20Science%20and%20AI/Week%205/Graph.png)



