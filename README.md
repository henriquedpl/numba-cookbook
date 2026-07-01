# Numba Cookbook

A practical collection of examples, recipes, and benchmarks demonstrating the capabilities of **Numba** for writing high-performance Python.

Whether you're just getting started or looking for advanced optimization techniques, this repository provides self-contained examples that showcase how to accelerate numerical Python code with minimal changes.

---

## Features

* JIT compilation with `@njit`
* Automatic parallelization
* `prange`
* `fastmath`
* Universal functions (`@vectorize`)
* Generalized ufuncs (`@guvectorize`)
* Typed containers
* `jitclass`
* CUDA programming
* Function caching
* C callbacks (`@cfunc`)
* Performance benchmarking
* Common pitfalls and limitations
* Best practices

Each recipe is designed to be independent, making it easy to explore specific topics without reading the repository from beginning to end.

---

## Repository Structure

```text
recipes/
    01_jit_compilation/
    02_parallel/
    03_vectorize/
    ...
```

Every recipe contains:

* `example.py` – the core implementation
* `benchmark.py` – performance comparison
* `README.md` – explanation and discussion

---

## Installation

Clone the repository:

```bash
git clone https://github.com/henriquedpl/numba-cookbook.git
cd numba-cookbook
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

or

```bash
pip install numba numpy
```

---

## Running an Example

```bash
cd recipes/01_jit_compilation
python example.py
```

To compare performance:

```bash
python benchmark.py
```

---

## Topics Covered

* Basic JIT compilation
* Nopython mode
* Loop optimization
* Parallel execution
* SIMD and `fastmath`
* Vectorized functions
* Generalized ufuncs
* Typed lists and dictionaries
* jitclass
* Stencil computations
* CUDA kernels
* Function caching
* Calling compiled code from C
* Benchmarking methodologies
* Common mistakes
* Best practices

---

## Benchmarks

Several benchmark programs compare:

* Pure Python
* NumPy
* Numba
* Numba Parallel
* Numba CUDA (where applicable)

Example workloads include:

* Monte Carlo simulation
* Matrix multiplication
* Numerical integration
* Image filtering
* Fibonacci
* Mandelbrot generation

---

## Requirements

* Python 3.11+
* Numba
* NumPy

Some examples additionally require:

* CUDA Toolkit (optional)
* NVIDIA GPU (optional)

---

## Contributing

Contributions are welcome.

Feel free to submit new recipes, improve existing examples, or add benchmark results for different hardware.

---

## License

This project is licensed under the GNU General Public License.
