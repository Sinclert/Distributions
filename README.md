# Distributions

### What is it?
This project was my final project of Software Development course, which was based on building a piece of software to classify vectors of data into 4 majors types of distributios: Binomial, Exponential, Normal or T-student.

### What is in the repository?
There are 2 main folders:

1. Lib: containing two libraries needed for the creation of the software:

  1.1 JSON-simple-1.1.1, which allowed me to work with JSON files.'\n'
  1.2 JUNIT-4.7, which allowed me to test my classification algorithms in a correct way.
  
2. src: containing the main files of the project:

  2.1 Calculations, where all files containning the calculations are stored. The main file is "calculateDisribution" because is the one which classifies the data vector performing the calculations specified in the other files.'\n'
  2.2 Tests, where all the test files are stored. The applied testing procedure was unit testing, which means a test file per each common file.
  
### Input / Output:

#### Input:
The input must be a data vector following JSON format.

#### Output:
The output will be also a JSON file, with the same name as the inut one, but containing the suffix "_distribution_<current time>". However, depending on the type of distribution that results:

* Binomial: The output will contain the "n" and "p" values, characteristic values of a binomial distribution.
* Exponential: The output will contain the value "lamda", which defines the distribution.
* Normal: The output will contain the mean and de standard devitation of the distribution.
* T-student: The output will contain the "degrees of freedom", characteristic value of a T-student distribution.
