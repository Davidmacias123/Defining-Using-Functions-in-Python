# functions_practice.py — Python Functions Practice (Cybersecurity Analyst Automation)

## On-the-Job Scenario (what this is simulating)
A cybersecurity analyst needs to run the same kinds of checks over and over (welcome messages, login checks, quick math, etc.).  
Instead of copy/pasting the same code repeatedly, we use **functions**—small reusable “mini-programs”.

**Why functions help (in one sentence):**  
Functions keep code **clean**, **organized**, and **reusable**, so you don’t repeat the same lines again and again.

---

## Success Coach Challenge Steps (what you must demonstrate)

### Step 1–2: Setup
1. Launch **Anaconda Navigator**
2. Open **Spyder IDE**
3. Create a new script named **`functions_practice.py`**

### Step 3: Basic function (no arguments)
- Create a function named `greet_user()` that prints a simple welcome message.
- Call it once.
- Add a comment explaining why functions help reduce repeated code.

### Step 4: Function with arguments (dynamic)
- Create a function `greet_person(name)` that prints a greeting using the provided name.
- Call it 3 times with different names.
- Add a second parameter `role` and include it in the greeting.

### Step 5: Functions that do math
- Create `add_numbers(a, b)` that **returns** the sum.
- Store the result in a variable and print it.
- Create another function that multiplies **two** numbers and returns the result.
- Print: **"The sum is X and the product is Y."**

---

##  Code

```python
# Step 3: Functions help clean up repeated code because you write the steps once,
# then reuse them many times by calling the function.

def greet_user():
    # This function prints a simple welcome message.
    print("Welcome! Access check starting...")

# Call the function once (run it one time)
greet_user()


# Step 4: A function with arguments (inputs)

def greet_person(name, role):
    # name and role are inputs (arguments) we pass into the function
    print(f"Welcome {name}! Your role is {role}.")

# Call the function three times with different people
greet_person("David", "IT")
greet_person("John", "Admin")
greet_person("Lucas", "Cashier")


# Step 5: Math functions that return values

def add_numbers(a, b):
    # return sends the answer back to whoever called the function
    return a + b

def multiply_numbers(a, b):
    # multiply two numbers and return the product
    return a * b

# Store results in variables
sum_result = add_numbers(5, 7)
product_result = multiply_numbers(6, 4)

# Print results
print(f"The sum is {sum_result} and the product is {product_result}.")
```

---

## Explanation
Imagine you have a **robot helper**.

- A **function** is like giving the robot a **tiny instruction card**.
- Instead of telling the robot the same thing again and again…
  you say: “Robot, use instruction card #1!”

### What each function is doing:
- `greet_user()`  
  = robot says a simple welcome message.

- `greet_person(name, role)`  
  = robot says hello to a specific person and says their job.

- `add_numbers(a, b)`  
  = robot adds two numbers and gives you the answer.

- `multiply_numbers(a, b)`  
  = robot multiplies two numbers and gives you the answer.

---

## Every single line explained (line-by-line)

### Step 3 lines
- `# ...`  
  A **comment** for humans. Python ignores it when running.

- `def greet_user():`  
  “Define a function named `greet_user`.”  
  The `:` means “everything indented below belongs to this function.”

- `print("Welcome! Access check starting...")`  
  Show a message on the screen.

- `greet_user()`  
  **Call** (run) the function.

### Step 4 lines
- `def greet_person(name, role):`  
  Create a function that needs two inputs:
  - `name` (who)
  - `role` (their job)

- `print(f"Welcome {name}! Your role is {role}.")`  
  Print a message using the inputs.  
  The `f"..."` lets you insert variables using `{}`.

- `greet_person("David", "IT")` (and the other calls)  
  Run the function 3 times with different values.

### Step 5 lines
- `def add_numbers(a, b):`  
  Create a function that takes two numbers.

- `return a + b`  
  Add them and **send the answer back**.

- `def multiply_numbers(a, b):`  
  Another function that takes two numbers.

- `return a * b`  
  Multiply them and **send the answer back**.

- `sum_result = add_numbers(5, 7)`  
  Run the add function and save the answer in `sum_result`.

- `product_result = multiply_numbers(6, 4)`  
  Run the multiply function and save the answer in `product_result`.

- `print(f"The sum is {sum_result} and the product is {product_result}.")`  
  Print the final message using both answers.

---

## Screenshot of my work

<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/5d5747e1-7bd4-481d-a772-25f8301a318a" />

