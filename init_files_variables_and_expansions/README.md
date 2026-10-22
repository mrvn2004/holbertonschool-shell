# 0x03. Shell, init files, variables and expansions

## Description

This project introduces shell initialization files, variables, expansions, shell arithmetic, and aliases in Bash.

## Tasks

### 0. \<o>

**File:** `0-alias`

Creates an alias named `ls` that executes `rm -f *`.

The alias demonstrates how to define a custom command shortcut in Bash.
### 1. Hello you

**File:** `1-hello_you`

Prints `hello` followed by the current Linux user's name using the `USER` environment variable.
### 2. The path to success is to take massive, determined action

**File:** `2-path`

Adds `/action` to the end of the `PATH` environment variable so the shell searches this directory last when looking for a command.
### 3. If the path be beautiful, let us not ask where it leads

**File:** `3-paths`

Counts the number of non-empty directories listed in the `PATH` environment variable using `tr` and `grep`.
### 4. Global variables

**File:** `4-global_variables`

Displays all environment variables using the `printenv` command.
### 5. Local variables

**File:** `5-local_variables`

Displays all shell variables, environment variables, and Bash functions using the `set` command.
### 6. Local variable

**File:** `6-create_local_variable`

Creates a local variable named `BEST` and assigns it the value `School`.
### 7. Global variable

**File:** `7-create_global_variable`

Creates and exports a global environment variable named `BEST` with the value `School` using the `export` command.
### 8. Every addition to true knowledge is an addition to human power

**File:** `8-true_knowledge`

Prints the result of adding 128 to the value stored in the `TRUEKNOWLEDGE` environment variable using Bash arithmetic expansion.
### 9. Divide and rule

**File:** `9-divide_and_rule`

Prints the integer division of the `POWER` environment variable by the `DIVIDE` environment variable using Bash arithmetic expansion.
### 10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath

**File:** `10-love_exponent_breath`

Calculates the value of the `BREATH` environment variable raised to the power of the `LOVE` environment variable using Bash arithmetic expansion.
### 11. There are 10 types of people in the world -- Those who understand binary, and those who don't

**File:** `11-binary_to_decimal`

Converts the binary number stored in the `BINARY` environment variable to its decimal representation using Bash arithmetic expansion.
### 12. Combination

**File:** `12-combinations`

Prints all alphabetically ordered combinations of two lowercase letters, from `aa` to `zz`, excluding `oo`. Uses brace expansion, `tr`, and `grep` to generate and filter the output.
### 13. Print float

**File:** `13-print_float`

Prints the number stored in the `NUM` environment variable with exactly two decimal places using `printf`.
### 14. Decimal to Hexadecimal

**File:** `14-decimal_to_hexadecimal`

Converts the decimal number stored in the `DECIMAL` environment variable to lowercase hexadecimal using `printf`.
