PYTHON FUNDAMENTALS (Data Engineering Focus)

1. Variables & Data Types
Variables

Used to store data values.

name = "Patience"
age = 23
salary = 15000.50
is_active = True

2. Core Data Types

int → whole numbers

float → decimal numbers

str → text

bool → True/False

list → ordered collection

dict → key-value pairs

2. Control Structures
Conditional Statements
if age > 18:
    print("Adult")
elif age == 18:
    print("Just adult")
else:
    print("Minor")

Loops
For loop
for i in range(5):
    print(i)

While loop
count = 0
while count < 5:
    print(count)
    count += 1

3. Functions

Used to organize reusable logic.

def calculate_total(price, quantity):
    return price * quantity


Benefits:

Code reuse

Cleaner structure

Easier debugging

4. File Handling (Important for Data Engineering)
Reading a File
with open("data.csv", "r") as file:
    content = file.read()

Writing to a File
with open("output.txt", "w") as file:
    file.write("Processed data")

5. Working with Pandas
Importing Pandas
import pandas as pd

Loading CSV
df = pd.read_csv("data.csv")

Basic Data Inspection
df.head()
df.info()
df.describe()

Cleaning Data
df.drop_duplicates()
df.fillna(0)
df.dropna()

Saving Clean Data
df.to_csv("cleaned_data.csv", index=False)

tuple → immutable collection

set → unique values
