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
