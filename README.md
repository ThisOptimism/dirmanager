# DirManager

DirManager is a command-line interface (CLI) tool designed to help you manage directories efficiently. With DirManager, you can easily list directory contents, create directories, and create files within your directory structure.

## Installation

To install DirManager, simply clone this repository to your local machine:

```bash
git clone git@github.com:ThisOptimism/dirmanager.git
```

Once cloned, you can install the dirmanager globally using npm:

```bash
cd dirmanager
npm install -g .
```

## Usage

DirManager provides the following commands:

- `-l [value]`: List the contents of the specified directory. If no directory is provided, it defaults to the current directory.

  Example:

  ```bash
  dirmanager --ls ./path/to/directory
  ```

- `-m <alue>`: Create a new directory with the specified name.

  Example:

  ```bash
  dirmanager --mkdir new_directory
  ```

- `-t <value>`: Create a new file with the specified name.

  Example:

  ```bash
  dirmanager --t new_file.txt
  ```

## Options

- `--version`: Show version number
- `--help`: Show help

## Contributing

Contributions are welcome! If you have suggestions for improvements, please open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
