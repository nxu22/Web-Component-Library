# React App Development Environment

This project contains a React application set up in a Docker environment, ready to run on your local machine.

## Prerequisites

Before you begin, ensure you have Docker Desktop installed on your system.

## Installation

Clone the GitHub repository:



Navigate to the repository directory:

```
cd web3012_coding_assignment12
```

## Running the Application with Docker

To launch the app, run the following command in your terminal:

```
Build the Image Locally:
docker build -t nxu_storybook:1.0.0 .
Run the Container After Building:
docker run --name nxu_coding_assignment12 -d -p 8083:6006 nxu_storybook:1.0.0

```

The application will be accessible at `http://localhost:8083`.

## Features

- The page displays a single line: "Coding 1".


## Contributing

[Instructions for how to make contributions to the project.]

## License

This project is unlicensed.
