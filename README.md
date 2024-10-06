# Metric FF Installation

This project is a clone of Metric FF, a fast, deterministic, domain-independent planning system. The original Metric FF project can be found [here](https://fai.cs.uni-saarland.de/hoffmann/ff.html).

I made some corrections to the original Metric FF code to make it compile on modern systems. 

## Prerequisites

Make sure you have `git` and `make` installed on your machine.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/ThomasChourret/Metric-FF-v2.1.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Metric-FF-v2.1
    ```

3. Build the project using `make`:

    ```bash
    make
    ```

## Usage

To run Metric FF, use the following command:

```bash
./ff -o domain.pddl -f problem.pddl
```

Replace `domain.pddl` and `problem.pddl` with the paths to your domain and problem files.

You can also use the `-h` flag to display the help message:

```bash
./ff -h
```

## Contributing

Contributions are welcome! Feel free to submit pull requests.
