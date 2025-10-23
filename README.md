# ICS-Quadratic-Grader--Shiyayi-Emmanuel-Kaseba-
# ICT251 – Web Technologies Assignment

## Project Title
*Single-File Web App: Quadratic Solver & Grade Converter*

## Description
This project is a *single-page web application (index.html)* built using *HTML and JavaScript* for the ICT251 – Web Technologies course.  
The application performs two key tasks:

1. *Solves a Quadratic Equation* of the form ax² + bx + c = 0
2. *Converts a Numeric Score (0–100)* into a *Letter Grade*

The web app runs completely offline — you only need to open the index.html file in any web browser.  
It is also published on GitHub for version control and submission.

---

## Features
- Solves quadratic equations and displays the *discriminant* and *nature of roots*.
- Converts numeric scores to letter grades using the provided grading scale.
- Validates inputs to ensure correctness and displays friendly error messages.
- Includes a *Reset/Clear* button for quick reuse.
- Simple, clean, and responsive design suitable for both desktop and mobile devices.

---

## Functionality Details

### Quadratic Solver
- *Inputs:* Three number fields for a, b, and c (each with labels).  
- *Validation:*  
  - a must not be zero.  
  - All inputs must be valid numbers.  
  - Clear error messages are displayed near invalid fields.  
- *Calculations:*  
  - Discriminant: D = b² − 4ac  
  - Nature of roots:
    - D > 0 → Two distinct real roots  
    - D = 0 → One real repeated root  
    - D < 0 → Two complex conjugate roots  
- *Output:* Neatly formatted results with reasonable decimal places.  
- *Extra:* A *Reset/Clear* button to clear all fields and results.

---

### Grading System
- *Input:* One number field for *Score* (integer between 0–100).  
- *Validation:*  
  - Only numbers within [0, 100] are accepted.  
  - Displays an error message if the input is out of range or empty.  
- *Output:*  
  - Displays the *letter grade* and a short message (e.g. Score 82 → Grade A).  
- *Grading Scale:*

| Score Range | Letter Grade |
|--------------|--------------|
| 85–100 | A+ |
| 75–84 | A |
| 65–74 | B+ |
| 60–64 | B |
| 55–59 | C+ |
| 50–54 | C |
| 0–49 | D |

- *Edge Cases:*  
  Boundary scores are correctly handled (e.g. 85 → A+, 0 → D, 100 → A+).

---

## Repository Structure
## How to Run
1. Clone or download the repository:
```bash
git clone https://github.com/<Shiyayi-Emmanuel-Kaseba->/ICS-Quadratic-Grader-
<Shiyayi-Emmanuel Kaseba>.git

