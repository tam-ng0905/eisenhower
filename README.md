# Focus

###A simple task tracking manager that helps you focus on what matter.

####This is an inspiration from the Eisenhower Matrix.

![Focus screenshot](screenshot.png)


## Usage

```
    🔎  eisenhower 

    Usage:

      node src/index.js  [<flags>] <command> [<args> ...]

    Flags:

      -h, --help                Output usage information.
      -v, --version             Show application version.

    Commands:

      h, help                   Output usage information.
      n, new                    Create a new project.
      v, view                   View a project's information.
      l, list                   View all project information.
      c, complete               Mark a project as completed.
      f, finish                 Mark a project as completed.
      d, delete                 Delete an existing project.
      r, remove                 Delete an existing project.

    Examples:

      Create a new project.
      $ node src/index.js new

      View the 'laundry' project.
      $ node src/index.js view laundry

      Delete the 'laundry' project.
      $ node src/index.js delete laundry

      List all projects.
      $ node src/index.js
        or
      $ node src/index.js list
```
