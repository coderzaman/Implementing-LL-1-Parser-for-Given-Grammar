# Implementing-LL-1-Parser-for-Given-Grammar
**LL(1) Parser Implementation**

This repository contains a C++ program implementing an LL(1) parser for a specific grammar. The LL(1) parser determines whether a given input string belongs to the language defined by the grammar.

### Grammar
The grammar implemented in this program is as follows:
```
X -> xYx
Y -> yY
Y -> ε
```

### Usage
1. Compile the program using a C++ compiler.
2. Run the compiled executable.
3. Enter the input string when prompted.

### Example
**Input:** `xyyx`

**Output:**
```
Enter your input: xyyx
Stack          Input:
X$             xyyx$
xYx$           xyyx$
yYx$           yyx$
yYx$           yx$
yx$            x$
x$             $
$              $
```

### Files
- `LL1_Parser.cpp`: The main C++ source code file implementing the LL(1) parser.
- `README.md`: This README file providing an overview of the project.

### Author
[Your Name]

### License
This project is licensed under the [MIT License](LICENSE).

Feel free to contribute or report any issues!
