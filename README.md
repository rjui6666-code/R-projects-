# R-projects-
## 📂 Topics Covered  ### 1️⃣ R Data Types - **Vector** – collection of same type values   - **List** – collection of different types   - **Matrix** – 2D same type elements   - **Data Frame** – 2D with mixed types (like Excel)   - **Factor** – categorical variables  
1️⃣ R Data Types
- **Vector** – collection of same type values  
- **List** – collection of different types  
- **Matrix** – 2D same type elements  
- **Data Frame** – 2D with mixed types (like Excel)  
- **Factor** – categorical variables  
- **Vector** – collection of same type values
- 1. Vectors

The most basic data type in R.

A vector contains elements of the same type (numeric, character, or logical).

👉 Example:

# Numeric vector
numbers <- c(1, 2, 3, 4, 5)

# Character vector
names <- c("Noor", "Romana", "Ali")

# Logical vector
values <- c(TRUE, FALSE, TRUE)


2. Lists

A list can contain elements of different types (numbers, strings, even other vectors/lists).

👉 Example:

my_list <- list(
  name = "Romana",
  age = 25,
  marks = c(90, 85, 88)

)

3. Matrices

A matrix is a 2D collection of elements, but only of the same data type (numeric, character, etc.).

👉 Example:

# Create a matrix
m <- matrix(1:9, nrow = 3, ncol = 3)

# Print matrix
print(m)


This will create a 3x3 matrix with numbers from 1 to 9.

4. Data Frames

A data frame is like an Excel table (rows and columns).

Each column can have different types (numeric, character, factor, etc.).

Mostly used in data analysis.

👉 Example:

students <- data.frame(
  name = c("Romana", "Noor", "Ali"),
  age = c(25, 28, 22),
  grade = c("A", "B", "A")
)

print(students)
5. Factors

A factor is used to store categorical data (like male/female, grade levels).

Internally, R stores them as numbers with labels.

👉 Example:

gender <- factor(c("Male", "Female", "Female", "Male"))
print(gender)
✨ So the flow is like this:

Vectors → Basic building blocks (same type).

Lists → Collection of different types.

Matrices → 2D (same type).

Data Frames → 2D (different types).

Factors → Categories.
📊 Comparison Table of R Data Types
Data Type	Structure	Same Type or Mixed?	Dimensions	Example	Usage
Vector	1D (line of elements)	Same type only	1 (length)	c(1,2,3,4)	Store numbers, words, or logical values in a single line
List	Collection	Can mix different types	1 (collection)	list("Romana", 25, c(1,2,3))	Store mixed information together (like a person’s profile)
Matrix	2D (rows & columns)	Same type only	2 (rows & cols)	matrix(1:9, nrow=3)	Store numeric data in tables (math operations, linear algebra)
Data Frame	2D (table, like Excel)	Columns can be different types	2 (rows & cols)	data.frame(name=c("Romana","Noor"), age=c(25,28))	Data analysis, datasets
Factor	1D (categories)	Stores categories as numbers + labels	1 (levels)	factor(c("Male","Female","Male"))	Handle categorical variables (gender, grade, region)

💡 Memory tip:

Vector = same type, 1D

List = mixed types, collection

Matrix = same type, 2D

Data Frame = mixed types, 2D

Factor = categories
✨ My Learning Goal
This repo is part of my journey to learn Data Science with R.
I will keep updating with more topics like data cleaning, visualization, and machine learning.
________________________________________

