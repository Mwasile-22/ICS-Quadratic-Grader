# ICS-Quadratic-Grader-

## Project Description
This is a single-page web application that allows users to:  
1. Solve a quadratic equation of the form *ax² + bx + c = 0*.  
2. Convert a numeric score (0–100) into a letter grade based on a specific grading scale.

The application is built using **HTML** and **JavaScript** in a single file (`index.html`) and can run offline in any browser.

---

## How to Run
1. Download or clone this repository.  
2. Open the `index.html` file by **double-clicking it** in your file explorer or opening it in a browser.  
3. Use the Quadratic Solver section to enter values for `a`, `b`, and `c`, then click **Compute Roots**.  
4. Use the Grading System section to enter a score (0–100), then click **Compute Grade**.  
5. Use the **Reset** buttons to clear inputs if needed.

---

## Test Cases

### Quadratic Solver
| a | b | c | Expected Result |
|---|---|---|----------------|
| 1 | -3 | 2 | Roots: 2, 1 (D > 0) |
| 1 | 2 | 1 | Root: -1 (D = 0) |
| 1 | 1 | 1 | Complex roots (D < 0) |
| 0 | 2 | 1 | Error: a cannot be 0 |

### Grading System
| Score | Expected Grade |
|-------|----------------|
| 100   | A+             |
| 85    | A+             |
| 75    | A              |
| 65    | B+             |
| 60    | B              |
| 55    | C+             |
| 50    | C              |
| 49    | D              |
| 0     | D              |

---

## Author
Emmanuel Mwasile Chitundu 
202304663

