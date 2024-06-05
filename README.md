# Project Documentation

This project uses MkDocs for generating documentation. Follow the instructions below to set up the environment, install dependencies, and run the project.

## Setup

### 1. Create a Virtual Environment

First, create a virtual environment to isolate your project's dependencies.

```sh
python3 -m venv venv
```

### 2. Activating the Virtual Environment

To activate the virtual environment, use the following commands based on your operating system:

#### On Unix or MacOS:

```sh
source venv/bin/activate

```

#### On Windows
```sh
.\venv\Scripts\activate
```

### 3. Installing Dependencies

Once the virtual environment is activated, install the required dependencies using the following command:

```sh
pip install -r req.txt
```

### 4. Running MkDocs
To serve the documentation using MkDocs on a specific port, use the following command:

```sh
mkdocs serve
```

To serve the documentation using MkDocs on a specific port, use the following command:

```sh
mkdocs serve -a 0.0.0.0:YOUR_PORT
```

Replace YOUR_PORT with the desired port number.

For example, to run MkDocs on port 8080:
```sh

mkdocs serve -a 0.0.0.0:8080
```
