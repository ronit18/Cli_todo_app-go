# Cli TODO app in GO

This is a simple CLI TODO app written in GO. It uses a file to store the TODOs. The file is created in the same directory as the executable.

## Usage

-   `todo -add <task>`: Add a task to the list
-   `todo -list`: List all the tasks
-   `todo -toggle <task number>`: Mark a task as done
-   `todo -del <task number>`: Delete a task from the list
-   `todo -edit <task number> <new task>`: Edit a task in the list

-   `todo -h`: Show help

## Installation

-   Clone the repository: `git clone https://github.com/ronit18/Cli_todo_app-go`
-   Navigate to the directory: `cd Cli_todo_app-go`
-   Run `go build`
-   Run `./todo -h` to see the help
