# sticks

Sticks is a Rust command-line tool for managing C and C++ projects. It simplifies the process of creating new projects and managing dependencies in your Makefile.

## Features

- Create new C and C++ projects with a single command.
- Generate a basic project structure with source files and a Makefile.
- Automatically set up "Hello, World!" code in the chosen language.
- Easily add and remove dependencies in your Makefile.

## Quick Install

```bash

```

## Installation

To use `sticks`, you'll need to build the project:

1. Clone the repository:

    ```bash
    git clone https://github.com/mAmineChniti/sticks.git
   ```

2. Change the current directory to the project folder:

    ```bash
    cd sticks
    ```

3. Build the project using cargo:

    ```bash
    cargo build --release
    ```

4. Once the build is complete, you can find the binary in the target/release directory. You can add this directory to your system's PATH for convenient usage.

## Usage

### Creating a New Project

To create a new C project, use the following command:

```bash
sticks c <project_name>
```

To create a new C++ project, use the following command:

```bash
sticks cpp <project_name>
```

Replace <project_name> with the name of your project.

These commands will create a new project directory with the specified name, set up a source file, and create a basic Makefile. The source file will contain a "Hello, World!" program in C++ or C.

### Adding a Dependency

To add a dependency to your project's Makefile, use the following command:

```bash
sticks add <dependency_name>
```

Replace <dependency_name> with the name of the dependency you want to add. Sticks will automatically modify your Makefile to include the new dependency. If the install-deps rule doesn't exist in your Makefile, Sticks will create it for you.

## Contributing

If you'd like to contribute to Sticks or report issues We welcome contributions and feedback from the community.

## License

This project is licensed under the MIT License. See the [LICENSE file](https://github.com/mAmineChniti/sticks/LICENSE) for details.

For any inquiries, feel free to email us at [emin.chniti@esprit.tn](mailto:emin.chniti@esprit.tn).
