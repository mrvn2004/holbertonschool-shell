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
