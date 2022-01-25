![CS121 Banner](images/CS121-BANNER.svg)
# Module 3 Lab Guide (part 2)

## Getting Started
[Lab Introduction Video](https://boisestate.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=ce75b364-88d3-4c72-980b-ae2600ca7dad&start=0)  

## Lab Activity 2 - AdGenerator
### Problem Description
Write an application that prompts for details related to an service advertisement using a Scanner and storing the entered data into appropriate variables. Once the information has been successfully read from the user and stored, generate an advertisement using the standardized format show in the expected output below. It is helpful to think of this as two separate steps: input processing and output formatting. Your program should match the expected output below.  

**Input Processing**  
- You may find it helpful to think of the phone number as a String instead of an integer value.

#### Expected Program Output (with sample user input)
```
Welcome to AdGenerator!
Please enter your profile information.
======================================
First name: Ernie
Middle name: Chip
Last name: Douglas
Job title: Cable Guy
Phone number (10 digit): 5558233765
Hourly rate: 16.50
```

**Output Formatting**
- Use string concatenation and the substring method from the String class to transform the phone number to the format (###) ###-####.
- Use the charAt method from the String class to retrieve the first letter of the middle name and concatenate first, middle initial, and last names.
- Use the currency format instance from the NumberFormat class to format the hourly rate.
#### Expected Program Output (based on above sample user input)
```
============================
Need a Cable Guy?
CALL NOW! (555) 823-3765
Ask for Ernie C. Douglas
(Rates start at $16.50/hr)
============================
```

### Implementation Guide
1. Expand the folder named AdGenerator and create a new file named AdGenerator.java
2. Design a program to satisfy the requirements in the Problem Description and enter the program code in AdGenerator.java
3. Test the program with the sample user input using the run link above the main method
4. Commit the changes to your local repository with a message stating that Activity 2 is completed.
5. Push the changes from your local repository to the github classroom repository.


## Lab Activity 3 - TriangleCalculator
### Problem Description
Write an application that reads the lengths of the sides of a triangle from the user. Compute the area of the triangle using Heron's formula (below), in which s represents half of the perimeter of the triangle, and a, b, and c represent the lengths of the three sides. Print the area to three decimal places using a DecimalFormat object. Your program should match the expected output below.  

<img src="images/heron-formula.png" alt="Heron's Formula" width="400">

#### Expected Program Output (with sample user input)
```
Enter the length of side 1: 10
Enter the length of side 2: 11
Enter the length of side 3: 12
Area: 51.521
```

### Impementation Guide
1. Expand the folder named A5-TriangleCalculator and create a new file named TriangleCalculator.java
2. Design a program to satisfy the requirements in the Problem Description and enter the program code in TriangleCalculator.java
3. Test the program the sample user input using the run link above the main method
4. Commit the changes to your local repository with a message stating that Activity 3 is completed.
5. Push the changes from your local repository to the github classroom repository.
